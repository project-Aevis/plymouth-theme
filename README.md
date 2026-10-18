# Aevis Plymouth Boot Theme

Animated Plymouth boot splash theme for the Aevis Desktop Environment.

Part of the **[Project Aevis](https://github.com/project-Aevis)** suite.

## Installation

```shell
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX=/usr ..
make
sudo make install
```

Set as default Plymouth theme:

```shell
sudo plymouth-set-default-theme aevis -R
```

## License

This project is licensed under the GNU General Public License v3.0 (GPLv3).
