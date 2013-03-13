All the development happens on SmalltalkHub: XXX
Github is only used to sync the development en files, for doing CI and store the issues list.

#How to install Calder ?

* Download the last dev MOOSE 4.7 image: http://ci.moosetechnology.org/job/moose-latest-dev/
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