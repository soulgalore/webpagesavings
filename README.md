Check how much you can save in kb for one page
==============

Background:
The project has been built to check how much web pages can save by following performance best practices rules like optimize images,
minify html/js/css and compress html/js/css.  The original idea was to check the largest sites in Sweden (according to http://kiaindex.se), 
but now you can also check how one specific page is doing.

The backend is Google Page Speed API and the following rules are checked:
* MinifyCss
* MinifyHTML
* MinifyJavaScript
* EnableGzipCompression
* OptimizeImages
* ServeScaledImages

You can run it like this (the kiafile is the kiaindex excel file, saved as csv with only the relevant columns):
<pre>KiaIndexSavings pathToKiaFile GoogleAPIKey</pre>

or
<pre>SavingsForOneURL URL GoogleAPIKey</pre>

