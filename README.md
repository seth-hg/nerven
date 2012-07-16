Nerven
======

nerven is a visualisation and capture utility for the Emotiv EPOC. It
was written by Sharif Olorin, who can be reached at sio@tesser.org. 

Requirements
============

* An unencrypted stream of EEG data (this can be obtained using nervend 
  at https://github.com/fractalcat/nervend)
* wxmpl (http://agni.phys.iit.edu/~kmcivor/wxmpl/)
* Cython (http://www.cython.org/)

In addition, python-edf (my fork at https://bitbucket.org/fractalcat/python-edf)
is required to capture to EDF files.

Installation
============

Linux
=====

sudo python setup.py install

Other platforms
===============

I haven't tested nervend on other platforms yet (it's on the todo list).
