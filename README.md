#ACF image cropper

This is an image cropping field for WordPress. It gives you a preview of the image, and if you click on it, the WordPress Media-Upload box opens.
Here you can edit the file by clicking on `edit image` and crop it to any size you want.

##Installation
* Go to your htdocs or /var/www/ folder
* move the `image-crop.php` file to `wp-content/themes/YOUR-THEME/fields/` (where YOUR-THEME is the theme you are using)
* Go to `wp-content/themes/YOUR-THEME/functions.php` file and put this right below the `<?php` tag:
* `register_field('acf_Image_Crop', dirname(__FILE__).'fields/image_crop.php');`
You now have a field type called Image Crop.
