# FFE Blockchain
![alt text](assets/FFE.Logo.png)

## Overview

Blockchain for seemless exchange of travel points, rewards, miles, etc. Built using the AKR ecosystem.

## Installation
`git clone [this repo]`

BLOCKCHAIN SETUP:\
`cd blockchain/; ./setup.sh`\
`testrpc`\
`run truffle commands`\

DATABASE SETUP:\
Must have cockroachdb installed!
`cd to db`\
`cockroach start --insecure` *must be done in separate terminal\
`cockroach sql --insecure --database=drill < schema.sql` *Initializing the db's and tables\

# Try it!

Take a look at our Beta web app [HERE!](http://www..com/)

[![Build Status](https://travis-ci.org/coderrick/drill.svg?branch=master)](https://travis-ci.org/coderrick/drill)
