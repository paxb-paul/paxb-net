## Paxb Network

Official golang implementation of the Paxb Network protocol.

## Building the source

Building requires both a Go (version 1.18 or later) and a C compiler.
Once the dependencies are installed, run the following.

```shell
make geth
```

After a successful build, executable binaries are installed in `build/bin/` .

## License

The paxb network library (i.e. all code outside of the `cmd` directory) is licensed under the [GNU Leaser General Public License v3.0](https://www.gnu.org/licenses/lgpl-3.0.en.html), also included in our repository in the `COPYING.LESSER` file.

The paxb network binaries (i.e. all code inside of the `cmd` directory) are licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html), also included in our repository in the `COPYING` file.
