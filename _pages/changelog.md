---
layout: page
title: What's New
include_in_header: true
include_in_footer: false
locale: en
---

# Changelog

## **Version 1.0.19**

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