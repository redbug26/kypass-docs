# KyPass \(iOS\)

## 5.3 - 2020-05-29

#### Added

* Year is now selectable in expiration date
* Added count in shortcuts section
* Added cloud provider icon in file list
* Added empty trash function
* Browse history entries
* Added database title in the bottom bar
* Allow certificates in O365 login

#### Fixed

* Autofill function is back for ios12 users
* Fix box.com sync
* Fix size display for local files
* Fix large file \(&gt;4mb\) upload with MSGraph
* Digits argument is now supported in OTP uri
* Fix the UIViewcontroller bug \(when the use shortcut option was not set\)

## 5.2 - 2020-04-19

#### **Fixed**

* Fix Dropbox sync

## 5.1 - 2020-04-18

#### Added

* Improve password generator
* O365 support rewriting

#### **Fixed**

* Fix autofill function

## 5.0 - 2020-03-09

#### Added

* Dark mode support
* Remove folder change in quick view
* Added reveal password button in the master password view

#### **Fixed**

* Fix O365 default folder creation

## **4.5.3** - 2019-09-10

#### Added

* Added personnalisation for the AutoFill QuickType bar cache
* Added Quick view in search panel
* Revamp synchronisation panel
* Added Shortcut list by default \(out of beta\)

#### **Fixed**

* Fix magnified password change when OTP changes

## **4.5.2 - 2019-04-10**

#### Added

* Added support to the AutoFill QuickType bar

## **4.5.1 - 2019-03-31**

#### Added

* Edition is working again with kdb v1.x file

#### **Fixed**

* Fix UI bug in file view on iOS&lt;11.0
* Fix msgraph \(and sftp\) bug when user is offline \(files are not removed anymore\)
* Fix deletion of local files

## **4.5.0 - 2019-03-22**

#### Added

* Refreshing UI
* New file view
* Sort filter
* Tags editor
* InputStick support

## **4.4.3 - 2018-10-21**

#### **Fixed**

* Fix internal browser for iPhone X and later
* Fix bluetooth popup at start
* Fix search when used with KDB v1 \(definitively\)

## **4.4.2 - 2018-10-04**

#### Added

* Allow password to be copied in clipboard from password generator

#### **Fixed**

* Fix the autocapitalize of the title field
* Fix creation\(modification\) date when create\(modify\) entry
* Fix search when used with KDB v1

## **4.4.1 - 2018-09-21**

#### **Fixed**

* Fix language in old autofill extension
* Fix paste of {REF} field in autofill extension
* Fix iCloud support in autofill extension

## **4.4.0 - 2018-09-18**

#### **Fixed**

* Added autofill extension \(goto the accounts and password iOS Setting and activate Kypass support there\)
* Passing theme option from beta to release and added the blue theme
* Tag/keyword view \(Edit of Tags in the next release\)

#### **Fixed**

* Fix a webdav bug
* Fix alignement of editable cell in configuration form

## **4.3.2 - 2018-06-03**

#### **Fixed**

* Fix FaceID bug

## **4.3.1 - 2018-05-28**

#### Added

* Added custom extension synchronisation
* New tools menu \(in group form\) with password generator \(more to come\)
* Folder tree \(expandable\)
* Import barcode directly in any field \(via tools menu\)
* Added time in the expiration time field
* SSH: added the pipe key

#### **Fixed**

* Fixed background color of the navigator in preview attachment
* Fix « open in » menu

## **4.3.0 - 2018-04-24**

#### Added

* Added OneDrive Enterprise \(msgraph\) as sync
* Show shared folder in OneDrive
* improved ssh client
* Add Hide expired entries in search as beta feature
* Add backup as a beta feature

#### **Fixed**

* Fix a bug in WebDav sync when device is offline

## **4.2.1 - 2017-12-19**

#### Added

* New chinese translation \(thanks to Licong Liu\)

#### **Fixed**

* Fix attachments view
* Fix a bug when you cancel the pincode/faceid/touchid window when returning to KyPass

## **4.2 - 2017-11-29**

#### Added

* OneDrive is now supported as cloud provder
* Display information instead of Empty screens in file view, group view & entry view
* Template edition could be choosing for an entry
* Add folder name in file list \(if cloud provider has more than one folder in configuration\)
* New share entry button
* Logging system to help developer to improve KyPass
* Add OTP key support from the plugin KeeOTP
* When adding an additional field, you could now choose one of the already used fields
* Hide folder if cloud provider is off in configuration
* Add reset theme in iOS preferences main page
* Color scheme designer \(beta\)
* Night theme \(beta\)
* iPhone X notch support
* Added contact form
* New webdav username/password bug fixed
* Flat icon in entry list

#### **Fixed**

* Fix copy/paste in ssh
* Dropbox: sync now works with database in the root folder.

## **4.1.1 - 2017-10-20**

#### Added

* Capture QR Code now save database immediately
* Added option to clear search at start
* Expiration date could be modified
* Attachments could be added/deleted
* Database is not reloaded anymore after uploading
* Fix dropbox folder in configuration
* Google Drive: Hide trashed file
* Google Drive: Erase local file if deleted on server
* Google Drive: Display modification date from server
* Webdav: Erase local file if deleted on server
* iCloud Files are now shown in browser extension
* Move Key Files to its own section in the file list
* New duplicate entry menu
* Dropbox: Migrate to new the official API v2 \(verify if you need to make a new connection ?\)
* Dropbox: Removing a folder from the list of Sync folders remove the files
* Modified date to relative
* Removed ASIHTTPRequest dependency. Fix some WebDAV problem with SSL.
* VNC: enabled server to client clipboard
* Key file could be used with any cloud provider
* Folder selection in cloud provider

#### **Fixed**

* Fix key file with that are 64 bytes long without hexadecimal content
* Fixed bug in the tools menu
* Fixed the copy comments bug.
* Fix some font in the entry view
* Fixed a **crash** in search panel with entry that have no username

## 4.0 - 2017-09-24

Paid upgrade

Revamped application and iPad support

## 3.0 - 2013-09-19

## 2.0 - 2012-09-12

Paid upgrade

## 1.0 - 2011-06-24

First version

