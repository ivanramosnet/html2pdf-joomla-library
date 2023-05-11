# Html2Pdf Library for Joomla!

**Html2Pdf Library for Joomla! 3.x**

If you already know how to use Html2Pdf and you need it for a Joomla! project, than this is a library package to be used in Joomla! Easy to install and update.

Download
--------

You can download the current version / older version of Html2Pdf-Joomla-Library using the [html2pdf-joomla-library download page](https://github.com/ivanramosnet/html2pdf-joomla-library/releases).

Version
-------

* The current Joomla! Library is using Html2Pdf 5.2.7.

Usage
-----

    require_once JPATH_LIBRARIES . '/html2pdf/html2pdf.php';
    use Spipu\Html2Pdf\Html2Pdf;


Now you can create a new Pdf document:

    $html2pdf = new Html2Pdf();


Documentation
-------------

* [Html2Pdf Read the Docs page](https://github.com/spipu/html2pdf/blob/master/doc/README.md)
* [Html2Pdf github page](https://github.com/spipu/html2pdf)

Bugs? Problems? Feedback?
-------------------------

If you have any problems installing / updating Html2Pdf Library in Joomla! feel free to [Add a New issue](https://github.com/ivanramosnet/html2pdf-joomla-library/issues)

If you are having problems with Html2Pdf itself and you think is a bug or something, check the [Html2Pdf Issue Tracker](https://github.com/spipu/html2pdf/issues)

Credits
-------

* Special thanks to the [Html2Pdf contributors](https://github.com/spipu/html2pdf/graphs/contributors) which put the Html2Pdf library together.
* Also thanks to Joe for the [inspiration](https://www.joomlashack.com/blog/how-tos/development/how-to-package-joomla-libraries/).


License
-------
Html2Pdf is licensed under [OSL License](https://github.com/spipu/html2pdf/blob/master/LICENSE.md)

Note
----

The library folder was build using the given composer.json file and executing:

    composer update --no-dev --prefer-dist