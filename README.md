# Ansible Role: Google Chrome  
[![Build Status](https://travis-ci.org/brentwg/ansible-role-google-chrome.svg?branch=master)](https://travis-ci.org/brentwg/ansible-role-google-chrome)

Ansible role that installs the Google Chrome browser.  

## Requirements  

None.  

## Role Variables  

User modifiable variables and defaults are listed below. (For all variables, see `defaults/main.yml`):  
```
chrome_package_name: "google-chrome-stable" 
```  
You can specify which verson of Chrome that you wish to run. Other options include: `google-chrome-beta` or `google-chrome-unstable`, if that's your thing.  

The rest of the defaults are used to create the YUM repo and provide URLs to gpg keys.  

## Dependencies

None.

## Sample Playbook

```
- hosts: all
  
  roles:
    - brentwg.google-chrome
```  
