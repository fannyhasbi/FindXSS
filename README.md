# FindXSS
FindXSS is a brute forcer for a Cross-Site Scripting

Facebook : https://fb.me/novan.rmd1
Instagram : https://instagram.com/novan.rmd

###Requirements:

    Python 2.7

    Wordlist included(wordlist.txt)

    Modules required: Colorama, Mechanize

###Modules Required:

    Colorama: https://pypi.python.org/pypi/colorama/

    Mechanize: https://pypi.python.org/pypi/mechanize/


How to use :

apt-get install python2
cd FindXSS
pip2 install colorama
chmod +x FindXSS.py
python2 FindXSS.py

###Usage(GET Method):

COMMAND:  python findxss.py
METHOD:   g
URL:      http://www.site.com/?parameter=value
WORDLIST: list.txt

###Usage(POST method):

COMMAND:   python findxss.py
METHOD:    p
URL:       http://www.site.com/file.php
POST DATA: parameter=value&parameter1=value1
WORDLIST:  list.txt

