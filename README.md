The purpose of this utility is to list all the files responsible for a Magento extension and their locations. Think of it as an experiment in building a automatic modman file generator. Key word "experiment" :)

####Usage:
Simple clone this repo and run the meff.php file via the command line passing it a extension name and full path to your Magento root directory.
```bash
php meff.php Extension_Name MagentoDir
```

####Caveats:
There is lots to refactor and places where I'm not doing stuff correctly. Submit a PR if you want to help.