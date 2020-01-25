# Bulk tinyPNG

Unofficial Drupal 7 module that implements [tinyPNG](https://www.drupal.org/project/tinypng) and [File Entity](https://www.drupal.org/project/file_entity) to provide mass ("batch / bulk") compression of images via fileEntity UI. **WIP!**
 
## INSTALLATION

Install and configure tinyPNG for Drupal 7 as [explained here](https://www.drupal.org/project/tinypng#d7-installation). Install "Bulk tinyPNG" and move to "Administration > Content > Files". You should now be able to select a bunch of images and compress them by selecting the "Compress selected files (non-images will be skipped)" update action.


## TODO

* The module does **not** yet skip images that have already become compressed. Such functionality would require a further field on the file entity and an integration with tinyPNG via [Drupal hooks](https://www.drupal.org/docs/7/creating-custom-modules/creating-drupal-7-hooks). 

* Refactor percentage calculation ("Compressed image by 23%").

Felix Albroscheit 2020, GNU GENERAL PUBLIC LICENSE (Version 2, June 1991).
