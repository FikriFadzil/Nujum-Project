Nujum Project &#129497;
========================

   [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

 ## About

  Usually, a new version of software will be shipped together with hundreds (or thousands) of files. Upon installation, those files will be created and scattered around different paths. If we gather all of the default local file paths for every software version and compare the list between each of them, we should able to extract the fingerprint that holds the identity for the software version.

  __Nujum__ is a Malay word which means "fortune teller". This project aims to build a database of software fingerprints based on unique collections of default local file paths. With this, you only have to check for the existence of every of the suggested local file paths. If the collection of existed files match any of the list, you should able to learn the software version.

 ## How to Use It?

   Fingerprint databases are avaiable in JSON format. Parse any of them with your favourite programming language and use it in your exploitation script.

 ## Supported Software Versions
   The following table contains a list of supported software versions.
   
   | Type  | Software | Version      |
   | :---: | :---:    | :---:        |
   | OS    | CentOS   | CentOS 7     |
   | OS    | CentOS   | CentOS 8     |
   | OS    | Debian   | Debian 9     |
   | OS    | Debian   | Debian 10    |
   | OS    | Ubuntu   | Ubuntu 16.04 |
   | OS    | Ubuntu   | Ubuntu 18.04 |
   | OS    | Ubuntu   | Ubuntu 20.04 |

 # Things You've to Know

   This is a newly born project. Tons of work yet to be done to improve the fingerprint databases.

   1. Raw data are available in `.manuscript` directory. Feel free to amend with new data and contribute on new fingerprints.
   2. Fingerprint databases are available in `fingerprints` directory.
   3. The fingerprints are not yet fine tune. Your feedbacks are welcomed for improvements.