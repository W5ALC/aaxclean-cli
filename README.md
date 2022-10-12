# aaxclean-cli
Command line interface for [AAXClean](https://github.com/Mbucari/AAXClean)

## Currently Supports:
- Aax and Aaxc files
- List chapters in Aax(c) file from metadata
- User-defined chapters
  - Entered manually as arguments
  - From a chapter_info json file
- Input Aax(c) files
  - From local file system
  - From an http(s) url
    - Custom user-agent string
    - User-defined web cookies
- Output
  - Single m4b file to local file system 

## Binary Releases:

Binaries are published for:
 - Windows x64
 - Windows x86
 - Linux x64

## Install and run instructions

- pip install audible-cli
- setup audible with your user name and password with
- audible-quickstart
- wget -O ~/bin/aaxclean-cli https://github.com/w5alc/aaxclean-cli/releases/download/v.0.1.5/aaxclean-cli && chmod +x ~/bin/aaxclean-cli
- wget -O ~/bin/audible-extracto https://github.com/w5alc/aaxclean-cli/releases/download/v.0.1.5/audible-extracto && chmod +x ~/bin/audible-extracto
- then download your library. Note, this will take time.
- audible download --all --aax-fallback
- once all files are downloaded
- you'll have 2 files with the same file name and different file extension
- xxxxxxx.aaxc and xxxxxxx.voucher
- Now you are ready to run the script it will run fast.
- audible-extracto
- Enjoy all the free content
- from audible without the content expiring

All credit to the people who wrote the programs that make this possible
