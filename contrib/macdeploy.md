# MacDeploy \#\#\#

For Snow Leopard \(which uses [Python 2.6](http://www.python.org/download/releases/2.6/)\), you will need the param\_parser package:

```text
sudo easy_install argparse
```

This script should not be run manually, instead, after building as usual:

```text
make deploy
```

During the process, the disk image window will pop up briefly where the fancy settings are applied. This is normal, please do not interfere.

When finished, it will produce `Dogecoin-Core.dmg`.

