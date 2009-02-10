TinyMCE CF GZIP gzips all javascript files in TinyMCE to
a single stream able file. This makes the overall download
size 75% smaller and the number of requests will also be
reduced. The overall initialization time for TinyMCE will
be reduced dramatically if you use this script. 

Copyright (c) 2009 Jules Gravinese (http://www.webveteran.com/)

TinyMCE CF GZIP by Jules Gravinese is licensed under a Creative
Commons Attribution-Share Alike 3.0 United States License.
Based on a work at tinymce.moxiecode.com.

The gzip functions were adapted and incorporated by permission
from Artur Kordowski's Zip CFC 1.2 : http://zipcfc.riaforge.org/

REQUIREMENTS:
• CF/Java write permission to the directory tinyMCE is in.
• CF Permission to CFObject tag.