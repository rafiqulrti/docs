Put the file in magento_root_directory/patches folder.
add the "cweagans/composer-patches": "^1.7", module in coposer file or add it with composer require cweagans/composer-patches
run composer update
Add the code in conposer.json in *extras* section. 
"composer-exit-on-patch-failure": false,
        "patches": {            
            "vendor/composer-module-name": {
                "Patch_file_name":"patches/Patch_file_name.patch"
            }           
        }
