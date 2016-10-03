# router-config
Our new infrastructure for Freiunk has two redundant routing VMs, based on [VyOS](https://vyos.io/). We don't use bird instead of the build-in Quagga, because we need features like multiple routing tables. Also bird is more stable than Quagga. For more information see [here](https://wiki.freifunk-bielefeld.de/doku.php?id=ffbimesh).
