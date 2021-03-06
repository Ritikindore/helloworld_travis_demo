# Travis_Demo_KPIT

 [![Build Status](https://travis-ci.org/rutujar/helloworld_travis_demo.svg?branch=master)](https://travis-ci.org/rutujar/helloworld_travis_demo)   [![CircleCI](https://circleci.com/gh/rutujar/helloworld_travis_demo.svg?style=svg)](https://circleci.com/gh/rutujar/helloworld_travis_demo)  [![Build status](https://ci.appveyor.com/api/projects/status/2wp50shl25yfw19q?svg=true)](https://ci.appveyor.com/project/rutujar/helloworld-travis-demo)  [![codecov](https://codecov.io/gh/rutujar/helloworld_travis_demo/branch/master/graph/badge.svg)](https://codecov.io/gh/rutujar/helloworld_travis_demo) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/0c0be9dca0474d9ea18d6e65c70c0514)](https://app.codacy.com/app/rutujar/helloworld_travis_demo?utm_source=github.com&utm_medium=referral&utm_content=rutujar/helloworld_travis_demo&utm_campaign=Badge_Grade_Dashboard) 


[![GitHub last commit](https://img.shields.io/github/last-commit/rutujar/helloworld_travis_demo.svg)](https://github.com/rutujar/helloworld_travis_demo) 
[![GitHub repo size in bytes](https://img.shields.io/github/repo-size/rutujar/helloworld_travis_demo.svg)](https://github.com/rutujar/helloworld_travis_demo) 
[![GitHub stars](https://img.shields.io/github/stars/rutujar/helloworld_travis_demo.svg)](https://github.com/rutujar/helloworld_travis_demo) 
 
 
 
 
 
 
 
 

 
In this project, your goal is to write a program and implement various Continous Integration tools using Travis, Jenkins,Appveyor,Circle CI for my Internship @KPIT.


## DOCUMENTATION

Nothing to <STRONG>INSTALL</STRONG> it is easy to use.

# STEPS

* add code to the github file.
* follow travis syntax and refer to [travis documentation](https://docs.travis-ci.com/)
* run the code.

# To run and test my project
*  Fork the document 
*  open travis website, enable the repository
*  build the project

# TRAVIS CI SYNTAX

## C 

```
language: c  
sudo: false # only for faster builds  
compiler:
   - clang
   - gcc
script:  
   - gcc -o test test.c #test is filename.c
   - ./test
```

## CPP(C++)

```
language: cpp  
compiler: gcc  
dist: trusty  
before_install:  
 - sudo add-apt-repository -y ppa:ubuntu-toolchain-r/test
 - sudo apt-get update -qq  
install:   
 - sudo apt-get install -qq g++-6  
 - sudo update-alternatives --install /usr/bin/g++ g++ /usr/bin/g++-6 90  
script:   
 - g++ swap.cpp -std=c++17 -o travis_gcc_cpp17  
 - ./travis_gcc_cpp17 
```

## JAVA

```
language: java
jdk: oraclejdk8
script: 
  - javac test.java
  - java test
```

## PYTHON

```
language: python
python: 3.6
cache: pip
before_script:
 - easy_install distribute
 - pip install -r requirements.txt
script: 
 - python test.py
```

## RUBY

```
language: ruby
sudo: false
script: 
 - ruby hello.rb
rvm:
 - 1.9.3
```

# How to contribute
Fork the repository, read the rest of the file and make some changes. Once you're done with your changes send a pull request. I will merge it. Thanks!

# LICENSE

[![](https://img.shields.io/github/license/sourcerer-io/hall-of-fame.svg?colorB=ff0000)](https://github.com/rutujar/helloworld_travis_demo/blob/master/LICENSE)

## Support Me
If you liked this, leave a star and fork it! :star: 

If you liked this and also liked my other work, be sure to follow me for more! :slightly_smiling_face:

