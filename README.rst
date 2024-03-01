Google Images Download
######################

This project is a clone of Joeclinton1/google-images-download with some modifications to address certain issues. Before using this script, it is necessary to download the ChromeDriver that matches the version of your local Chrome browser. This ensures that the script can control the browser correctly for image downloads.

ChromeDriver Download
=============
To download the appropriate version of ChromeDriver, please visit the ChromeDriver download page at https://googlechromelabs.github.io/chrome-for-testing/#stable. Select the version that corresponds to your Chrome browser's version to ensure compatibility.

Configuration
=============
Users can modify the config.json file included in the google_images_download directory to customize their download preferences. One important step is to specify the absolute path to the ChromeDriver executable (including the .exe extension for Windows users). This path needs to be accurate for the script to initiate and control the browser properly.

Running the Script
=============
After setting up the ChromeDriver path in config.json, you can download images by executing the following command in your terminal or command prompt:

bash
Copy code
python .\google_images_download.py -cf config.json
This command initiates the script with the configurations specified in config.json, and it will start downloading images based on your specified parameters.

Please ensure that you have Python installed on your system and that you have followed the installation instructions for this script as outlined in the Installation section of the documentation.

Python Script for 'searching' and 'downloading' hundreds of Google images to the local hard disk!

Documentation
=============

* `Documentation Homepage <https://google-images-download.readthedocs.io/en/latest/index.html>`__
* `Installation <https://google-images-download.readthedocs.io/en/latest/installation.html>`__
* `Input arguments <https://google-images-download.readthedocs.io/en/latest/arguments.html>`__
* `Examples and Code Samples <https://google-images-download.readthedocs.io/en/latest/examples.html#>`__


Disclaimer
==========

This program lets you download tons of images from Google.
Please do not download or use any image that violates its copyright terms.
Google Images is a search engine that merely indexes images and allows you to find them.
It does NOT produce its own images and, as such, it doesn't own copyright on any of them.
The original creators of the images own the copyrights.

Images published in the United States are automatically copyrighted by their owners,
even if they do not explicitly carry a copyright warning.
You may not reproduce copyright images without their owner'self permission,
except in "fair use" cases,
or you could risk running into lawyer'self warnings, cease-and-desist letters, and copyright suits.
Please be very careful before its usage! Use this script/code only for educational purposes.
