# MageHost_Cm_Cache_Backend
MageHost extended version of Colin Mollenhour's Cm_Cache_Backend_File and Cm_Cache_Backend_Redis

## Installation using Composer
* `cd` to your Magento 2 root dir
```
composer config repositories.magehost_cm_cache_backend-m2 vcs git@github.com:magehost/magehost_cm_cache_backend-m2.git
composer require magehost/magehost_cm_cache_backend-m2
```
* Edit `app/etc/env.php`: set *cache > frontend > default > backend* to `MageHost_Cm_Cache_Backend_Redis`


## Uninstall using Composer
```
composer remove magehost/magehost_cm_cache_backend-m2
composer config --unset repositories.magehost_cm_cache_backend-m2
```