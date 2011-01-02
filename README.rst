FEMhub QT
=========

Install PySide
--------------

For Ubuntu::

    sudo add-apt-repository ppa:pyside
    sudo apt-get update
    sudo apt-get install python-pyside

For other distributions, see here:
http://developer.qt.nokia.com/wiki/PySideBinariesLinux

Install and Run FEMhub QT
-------------------------

In Ubuntu::

    git clone git@github.com:femhub/femhub-qt.git
    cd femhub-qt
    ./femhub-qt

This launches a Femhub desktop application (unfinished). To get some ideas how
a finished application could look like, do from the same directory::

    ./desktop-app

This launches an Ext JS demo, as a desktop application. To see how a mobile
application could look like, do::

    ./mobile-app

This creates a window with dimensions of the Nexus One phone and launches a
Sencha Touch demo. This is for debugging only, the real application will run on
the actual phone as a native app, using WebView, as described here in the
Android API:

http://developer.android.com/guide/webapps/index.html
