# cassandra-driver-wheels

cassandra-driver takes a long time to compile if you compile it with Cython for better performance.

This repo provides pre-compiled wheels for MacOS 10.14 (untested with previous versions) and Linux x86_14 (tested in Ubuntu Xenial and Debian Stretch). By using the wheels provided in this repository you achieve faster installation and you do not need to install build requirements at all.

To use it, simply use pip: `pip install wheel_file.whl`
