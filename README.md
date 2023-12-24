Requirements

Download and Install any local web server such as XAMPP.
Download the provided source code zip file.

Generate Pexel API Key
Login or Register on pexels.com
 - Upon successful login, click the user avatar icon in the navigation bar. From the dropdown menu, select `Image and Video API`.
 - Click the `Your API Key` button to generate your API key.
 - Save API key.

Open your XAMPP Control Panel and start Apache.
Extract the downloaded source code zip file.
Copy the extracted source code folder and paste it into the XAMPP's "htdocs" directory.
Browse the PHPMyAdmin in a browser. i.e. http://localhost/phpmyadmin
Locate and Open the `stackAPI.class.php` file with your preferred code editor.
Replace the `$this->apiKey` value with you Pexels API Key and save it.
Browse the Simple Image Stack Website in a browser. i.e. http://localhost/php-image-stack/
