This tool can extract a .car archive: https://github.com/steventroughtonsmith/cartool

Steps to extract archive:

Once you've downloaded the zip from github, compile it in Xcode (Xcode 9) to generate the command line tool. Then expand the Products group and right click on the cartool file and locate it in finder. You can then run the tool like so:

open terminal

```cd /path/to/cartool```

```./cartool /path/to/Assets.car /path/to/outputDirectory```
