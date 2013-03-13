All the development happens on SmalltalkHub: http://bit.ly/12Qvo8s

Github is only used to sync the development en files, for doing CI (continuous integration) and store the issues list.

#How to install Calder ?

* Download the last Pharo 1.4 image: http://gforge.inria.fr/frs/download.php/31258/Pharo-1.4-14557-OneClick.zip
* Load last stable version of Calder:

```Smalltalk
Gofer it
      url: 'http://smalltalkhub.com/mc/UMMISCO/Calder/main';
      package: 'ConfigurationOfCalder';
      load.
((Smalltalk at: #ConfigurationOfCalder) project version: #'stable') load.
```

#Install GitHub version

```Smalltalk
Gofer new
      url: 'http://ss3.gemstone.com/ss/FileTree';
      package: 'ConfigurationOfFileTree';
      load.
((Smalltalk at: #ConfigurationOfFileTree) project version: #'stable') load.
```