## Additional Documentation

>Install Xampp
>Go to C:\xampp\htdocs
>Create a folder with your website name
>Extract wordpress folder contents to that folder
For further details on how to get the site running refer:
https://themeisle.com/blog/install-xampp-and-wordpress-locally/

>Admin login into your website and go to dashboard
>Go to add new plugins in the Plugin Section
>Search, Install and Activate All-in-One WP Migration
>Go to import Section of All-in-One WP Migration
>If Maximum upload file size: 40 MB.
then,
1. Update .htaccess file
php_value upload_max_filesize 256M
php_value post_max_size 256M
php_value memory_limit 512M
php_value max_execution_time 300
php_value max_input_time 300
Change the numbers to the values that you need. The max execution time and max input time values are in seconds and might need to be increased further if your internet connection is slow.

2. Update wp-config.php file
@ini_set( 'upload_max_filesize' , '256M' );
@ini_set( 'post_max_size', '256M');
@ini_set( 'memory_limit', '512M' );
@ini_set( 'max_execution_time', '300' );
@ini_set( 'max_input_time', '300' );

Refer : https://help.servmask.com/2018/10/27/how-to-increase-maximum-upload-file-size-in-wordpress/

>Click on Import from and select the file i.e. localhost-dellprob-20191031-014613-185.wpress
> After Importing click on proceed
>Admin login details:
Email: dellprob2@gmail.com
Password: Probdell2
>Go to permalinks section in settings and save changes

In case of the team comes up with multiple solutions to the problem statement, irrespective of the implementation please document the same on a high level and upload the supporting documents (if any) in this section.