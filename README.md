# Talkify
[![Build Status](https://travis-ci.org/mrchainman/Talkify.svg?branch=master)](https://travis-ci.org/mrchainman/Talkify)
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)  

A python script that fetches notifications from the nextcloud talk api and pushes them to a gotify server.

### Usage
Just adapt the settings in the settings.py file and start run the script.
A working Nextcloud talk instance and a working gotify setup ist needed.

### TODO
- [x] Currently the number of conversations must be specified manually. It would be cool to parse the number of conversations from the json data.
- [ ] Handle Calls
- [ ] Check how it works with group chats
- [ ] Find a better way for authentication, as username and password are stored in plaintext in the settings.py file
