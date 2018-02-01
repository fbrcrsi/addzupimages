# addzupimages
Add ZupImages service on phpBB 3.1.x and phpBB 3.2.x message editor

## Quick Install
You can install this on the latest release of phpBB 3.1.x phpBB 3.2.x by following the steps below:

1. [Download the latest release](https://github.com/fbrcrsi/addzupimages).
2. Unzip the downloaded release, and change the name of the folder to`addzupimages`.
3. In the `ext/` directory of your phpBB board, create a new directory named `fbrcrsi` (if it does not already exist).
4. Copy the `addzupimages` folder to `ext/fbrcrsi/` directory of your phpBB board.
5. Navigate in the ACP to `Customise -> Manage extensions`.
6. Look for `Add ZupImages service` under the Disabled Extensions list, and click its `Enable` link.


Remember to purge cache each time you edit the templates after the installation

## Uninstall

1. Navigate in the ACP to `Customise -> Extension Management -> Extensions`.
2. Look for `Add ZupImages service` under the Enabled Extensions list, and click its `Disable` link.
3. To permanently uninstall, click `Delete Data` and then delete the `/ext/fbrcrsi/addzupimages` directory.

## Version History

 - 2018.02.01
 - 1.0.0 : Stable version