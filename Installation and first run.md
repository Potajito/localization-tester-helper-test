# Installation and first run

## Requirements
- Mongo DB Community Server 5.0.x

## Installation
1. Set up your MongoDB Community Server with access control disabled, commenting the following lines on file ```mongod.cfg``` in your Mongo Server directory (it should be like this by default):
```
#security:
#    authorization: enabled
```
2. Install and run Localization Tester Helper. You will be prompted with a login screen:
      - Press 'Settings', insert your mongo server address ('mongodb://localhost:27017', for example)
      - If the Mongodb server is empty and access control is disabled, a skeleton for the tool and a super user 'LocAdmin' account will be created.
3. Exit Localization Tester Helper and enable Mongo access control, un-commenting the previous lines on ```mongod.cfg``` file:
```
security:
    authorization: enabled
```
4. Restart Mongo DB Server.
5. Run Localization Tester Helper and login with the super user 'LocAdmin' (First time password is 'LocAdmin', you will be asked for a new password on login).
6. Create manager/testers accounts as needed. Please note that 'LocAdmin' account is not meant for regular use, and you should instead create manager accounts for normal use.

## Importing files

## Importing glossaries/termbases

## Exporting files

