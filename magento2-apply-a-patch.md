 1. Put the file in <magento_root_directory>/patches folder.
 2.  add the `"cweagans/composer-patches": "^1.7",` module in coposer file or add
    it with `composer require cweagans/composer-patches`
 3. run **composer update**
 4. Add the code in conposer.json in **extras** section.
 `"composer-exit-on-patch-failure": false,
    "patches": {
	    "vendor/composer-module-name": {
		    "Patch_file_name":"patches/Patch_file_name.patch"
	    }
    }`
