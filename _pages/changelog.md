---
layout: page
title: What's New
include_in_header: true
include_in_footer: false
locale: en
---

# Changelog

## **Version 1.1.13**

Developing...

- ADDED: add emby support
- IMPROVED: improve view information of remote files
- IMPROVED: improve movie playback rate up to 4.0x
- FIXED: fix issue that incorrect file content after remote file update
- FIXED: fix issue that batch rename will crash on iOS 14

## **Version 1.1.12**

date: 2021-11-03 (build 62)

- ADDED: add batch rename
- ADDED: add drag and drop support to local file browser
- ADDED: add drag and drop files from other applications for upload
- ADDED: add delete confirmation switch
- FIXED: fix issue that folder size always calculating
- FIXED: fix issue that upload small file to OneDrive always fails

## **Version 1.1.11**

date: 2021-10-27 (build 61)

- ADDED: add picture in picture support for local video files
- IMPROVED: improve user experience of moving remote files
- FIXED: fix issue that some video files can not be played
- FIXED: fix issue that progress of remote video not updated when play video from remote list
- FIXED: fix issue that background audio glitch issue

## **Version 1.1.10**

date: 2021-10-23 (build 60)

- ADDED: add icon size picker to files
- FIXED: fix issue that share action always shown in photo browser
- FIXED: fix issue that can not turn off app lock when FaceID is enabled
- FIXED: fix issue that when app lock enabled, presented view will be dismissed when come back from background
- FIXED: fix issue that progress of recent movie not updated

## **Version 1.1.9**

date: 2021-10-20 (build 59)

- ADDED: add lyrics editor
- FIXED: fix issue that ID3 information not updated immediately
- FIXED: fix occasional crash when closing movie player
- FIXED: fix crash that playing a movie with AutoRotate switch turned off

## **Version 1.1.8**

date: 2021-10-17 (build 58)

- IMPROVED: improve access to select audio track in video player
- IMPROVED: improve access to select subtitle in video player
- FIXED: fix issue that access token of OneDrive expires not correctly handled
- FIXED: fix issue that artwork cloud not automatically updated when metadata is missing
- FIXED: fix issue that video streamed from AliyunDrive cloud not resumed from playback history
- FIXED: fix issue that recent history not removed when the source file deleted from remote server

## **Version 1.1.7**

date: 2021-10-13 (build 57)

- ADDED: add server type indicator to recent history
- IMPROVED: improve performance of playing large amounts music
- FIXED: fix issue that shuffle folder not working
- FIXED: fix thumbnail load issue with Dropbpx
- FIXED: fix title display issue with remote grid mode

## **Version 1.1.6**

date: 2021-10-10 (build 56)

- ADDED: add grid mode to remote browser
- ADDED: add thumbnail for cloud service
- ADDED: add thumbnail support for Text and PDF files
- ADDED: add Laboratory to explore experimental features
- FIXED: fix issue that delete video from video player does not clear playback history

## **Version 1.1.5**

date: 2021-10-06 (build 54)

- ADDED: add app lock
- ADDED: add a switch for whether to pop up the player in the music player
- ADDED: add thumbnail switch to video, audio and image files
- FIXED: fix issue incorrect display of play button status after switching videos
- FIXED: fix issue that the video player did not load the progress after switching videos


## **Version 1.1.4**

date: 2021-09-28 (build 53)

- FIXED: fix crash issue with iOS 14

## **Version 1.1.3**

date: 2021-09-27 (build 52)

- ADDED: add upload queue 
- ADDED: add large file upload support
- FIXED: fix issue that load non-image files when browsing local images
- FIXED: fix issue that audio and video files of WebDAV(HTTPS) can not be played under LAN
- FIXED: fix issue that remove file/folder not working with NFS

## **Version 1.1.2**

date: 2021-09-19 (build 50)

- FIXED: fix issue that copy to Filebox not working
- FIXED: Fix issue that video cannot be played with SMB connected through discovery
- FIXED: fix issue that the error "Socket is not connected" may appear for SMB connection
- FIXED: fix crash issue with non-exist nfs server

## **Version 1.1.1**

date: 2021-09-17 (build 48)

- ADDED: add preview remote text files
- ADDED: add upload file support to BaiduPan
- FIXED: fix issue that favorites folder may not be canceled
- FIXED: fix download issue with BaiduPan and Dropbox 

## **Version 1.1.0**

date: 2021-09-14 (build 47)

- ADDED: add auto discover network share services
- ADDED: add search files to remote server
- ADDED: add keybobard control for iPad when playing video
- ADDED: remember last side bar selection for iPad
- FIXED: fix issue that pull down to refresh arrow shown behind navigation bar
- FIXED: fix issue that subtitle shown in search scopes
- FIXED: fix issue that can not upload file with WebDAC connection
- FIXED: fix issue that duration always been zero when playing video from pCloud
- FIXED: fix list some folder issue with FTP connection

## **Version 1.0.24**

date: 2021-09-03 (build 45)

- ADDED: add MEGA support
- IMPROVED: optimze filename order
- FIXED: fix brightness view does not show while adjust screen brightness

## **Version 1.0.23**

date: 2021-09-01 (build 43)

- ADDED: add pull to refresh to cloud service
- IMPROVED: remember collapsed setting of connection entry
- FIXED: fix issue that OneDrive can not list folder

## **Version 1.0.22**

date: 2021-08-26 (build 42)

- ADDED: add import videos and photos from Photos app
- ADDED: add WMV video format support
- IMPROVED: improve favorite folders from cloud service 

## **Version 1.0.21**

date: 2021-08-23 (build 41)

- ADDED: add Baidu Pan support
- ADDED: add pCloud support
- ADDED: add long press folder to shuffle
- ADDED: add batch upload files and folders
- IMPROVED: improve video player adjust volume experience
- FIXED: fix issue that load subtitle from remote server can only load subtitle within root folder
- FIXED: fix issue that remember video play history switch does not work

## **Version 1.0.20**

date: 2021-08-17 (build 40)

- ADDED: add upload context menu to local files
- IMPROVED: improve search subtitle experience
- FIXED: fix issue that remote connect account maybe saved twice
- FIXED: fix issue that connect to server that does not have a nfs server will be crashed

## **Version 1.0.19**

date: 2021-08-14 (build 39)

- ADDED: add ability to preview local HTML files
- IMPROVED: connect with SMB that address contains share name now automatically connects the specified share
- FIXED: fix issue that move remote files only moves the first file
- FIXED: fix issue that playing ts format video get duration wrong
- FIXED: fix issue that can not play video with some SMB connection

## **Version 1.0.18**

date: 2021-08-08 (build 38)

- ADDED: add Box support
- ADDED: add Google Drive support
- ADDED: add photo browser to OneDrive and Dropbox
- IMPROVED: Hide video controls when swipe to forward and backward
- FIXED: fix some folder could not list files with OneDrive connection

## **Version 1.0.17**

date: 2021-08-06 (build 37)

- ADDED: add Dropbox support
- FIXED: fix issue that recent movie title wrong with OneDrive

## **Version 1.0.16**

date: 2021-08-02 (build 36)

- ADDED: add OneDrive support
- ADDED: add local photo browser

## **Version 1.0.15**

date: 2021-07-30 (build 35)

- ADDED: add option to select audio track in video player
- ADDED: add option to turn off auto save video playback history
- FIXED: fix issue that remote audio file
- FIXED: fix issue that remember video play history not working at iPad

## **Version 1.0.14**

date: 2021-07-22 (build 34)

- ADDED: add NFS remote protocol support
- ADDED: add subtitle abilities to video player
- ADDED: add file sort menu to remote files
- ADDED: add flac and caf audio file format support
- ADDED: add webm and ogg video file format support
- FIXED: fix connection issue with Synology which enables 2-Step verification

## **Version 1.0.13**

date: 2021-07-16 (build 33)

- ADDED: add delete file action to movie player
- ADDED: add remote music file playback support
- IMPROVED: remember last expand or collapse behavior of saved accounts and favorited folders
- IMPROVED: improve reveval search result
- FIXED: fix issue that can not search song when music player is not playing
- FIXED: fix crash when using guest mode to connect to SMB server
- FIXED: fix crash when taking snapshot of a video but current player does not has a video output
- FIXED: fix issue that connect without username and password using WebDAV may cause crash
- FIXED: fix connecting issue with FTP

## **Version 1.0.12**

date: 2021-07-03 (build 32)

- ADDED: add now playing music bar to iPad
- ADDED: add auto update music metadata switch toggle
- IMPROVED: Reduce the size of app
- FIXED: fix issue that compressed file can not be decompressed for the second time
- FIXED: fix issue that folder cannot be compressed

## **Version 1.0.11**

date: 2021-06-30 (build 30)

- ADDED: add movie playlist in movie player
- ADDED: add more swipe actions to file
- FIXED: fix issue that music player maybe presented twice
- FIXED: fix issue that 7z and tar files do not decompress when tap the file

## **Version 1.0.10**

date: 2021-06-18 (build 28)

- add movie playlist in library when they are tv series
- improve library movie artwork load performance
- fix issue that auto fetch metadata not working as expected
- fix issue that movies with uppercased extension can not be played
- fix change play mode not working when playing music

## **Version 1.0.9**

date: 2021-06-13 (build 27)

- redesign the UI of file information viewer
- add image browser to remote images (WebDAV/Synology/SMB/FTP)
- add now playing item animation in playlist
- add information viewer to remote files
- fix issue that invalid address may cause crash when connect with SMB connection
- fix issue that compress file always fails

## **Version 1.0.8**

date: 2021-06-09 (build 26)

- add rating information to movie metadata
- add multiple selection support to add file from Files
- fix issue that in certain scenario WebDAV can not be connected
- fix rename file and move file issue with WebDAV connection
- fix issue that advanced information not loaded when editing saved network share account
- improve performance

## **Version 1.0.7**

date: 2021-06-05 (build 25)

- add a way to edit metadata of library recent played movies
- add a new network share protocol: WebDAV(HTTPS)
- fix connection issue with WebDAV server
- fix download file issue with WebDAV and FTP connections
- fix now playing bar music artwork not clipped issue
- improve recent played movie title to two lines to display more information


## **Version 1.0.6**

date: 2021-06-03 (build 24)

- Add playback list to recent played videos
- fix issue that toolbar will overlaped by now playing bar when editing remote server files
- fix issue that download nested folder will always failed
- fix issue that when files removed but recent played videos not updated


## **Version 1.0.5**

date: 2021-05-31 (build 22)

- Redesign Library tab
- Redesign now playing bar of music player
- add context menu to file search result
- add goto folder to file search result
- improve music player last playlist

## **Version 1.0.4**

date: 2021-05-26 (build 20)

- add movie playback history progress to remote video
- add multiple selection operations to remote files
- fix issue with deleting folder with SFTP connection

## **Version 1.0.3**

date: 2021-05-14 (build 16)

- add download HTTP resources directly
- now you can play previous/next video in video player when playing folders contains multiple videos
- fix smb path issue cause can note create folder and delete files
- optimize remote login error message
- add website in about page
- fix page control color issue in onboarding page
- fix the problem that remote folders are not updated when moving files in some cases
- fix address and protocol not saved when edit remote account

## **Version 1.0.2**

date: 2021-05-12 (build 15)

- add onboarding screen
- add home screen quick action to shuffle music
- add transfer files via AirDrop
- add sleep timer to music player
- add get started documents
- fix markdown export pdf page size issue
- fix orientation issue with video player when returned from background


## **Version 1.0.1**

date: 2021-05-09 (build 11) 

- add more icon in remote browser to trigger contextual menu
- improve video play history managment
- fix mail feedback cancel button tapped has no effect issue
- fix video can not played in downloading page
- fix font setting value not updated when new font selected
- fix airdrop cold launch files not copied issue

## **Version 1.0.0**

date: 2021-05-04 (build 10) 

* initial release