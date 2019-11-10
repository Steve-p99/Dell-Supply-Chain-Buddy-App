## Team Name - Project Name

The participants are required to clone this repository and create a private Gitlab repository under their own username (Single repository per team). The following created sections in this README.md need to be duly filled, highlighting the denoted points for the solution/implementation. Please feel free to create further sub-sections in this markdown, the idea is to understand the gist of the components in a singular document.

### Project Overview
----------------------------------
A functional flow on how Dell’s  Supply Chain works which includes several departments and their interconnection.
 Department Specific information  along with recommended videos, user manuals to be followed by a fresher joining the company.

### Solution Description
----------------------------------
This website is a one stop platform for Dell developers.
-Easily share domain knowledge among different team members 
-Reduces the  time spent  in explaining new members
-Built with keeping user education in mind,
-Aims to provide accurate technical solutions.
-Helps to maintain Consistency and   Uniformity across teams.

Main Features : 
SUPPLY CHAIN FUNCTIONAL FLOW
CODING STANDARDS
DISCUSSION FORUM
POST SECTION
USER MANUALS
RESPONSIVE UI

#### Architecture Diagram

Affix an image of the flow diagram/architecture diagram of the solution

#### Technical Description
How To Install

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

All files required are included in the Application Code folder
### Team Members

Stevens Philip - stevensp99@gmail.com - UI design Implementing Functionalities
Ambarish Dutta - ambarish.dutta1010@gmail.com - UI design Implementing Functionalities
Kritika Garg - kritikagarg.16@gmail.com - UI Design
Ananya Sarkar - anusid257@gmail.com - Database manipulation

K
----------------------------------

List of team member names and email IDs with their contributions
