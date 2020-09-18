# Basic Pirate Literacy Guide

This guide will be explaining a few processes that will increase your overall computer literacy, as would be useful specifically for piracy. I'll explain terminology, file management, and transferable pirate skills. 

## Important Notes

- As with the rest of these guides, this will be very Windows 10 oriented. 
- EVERYTHING here is important, except the [torrenting](#Torrenting) section, which is an optional method.
- I created this guide with the very tech-illiterate in mind. If you sit down, really have a good read of this guide, and still feel like you're reading a foreign language? Perhaps piracy just is not for you. Few exceptions in mind, piracy is always going to be an involved process.

## Basic Terminology

- Directory: File folder.
- Parent folder/directory: The folder "1 level up" from the folder you are currently viewing. 

## File Extensions

File extensions are a label at the end of all file names, which mark what type of file one is. They consist of a ```.```, followed by an abbreviation for the type of file.

File name WITHOUT visible file extension | File name WITH visibile file extension | File Type | Media Type
-----------------------------------------|----------------------------------------|-----------|-----------
spongebobsquarepants-s03e19 | spongebobsquarepants-s03e19.mkv | Matroska Multimedia Container | Video
august.taylorswift | august.taylorswift.flac | Free Lossless Audio Codec | Audio

As you can observe from these examples, a file extention always starts with a ```.```, and the example file extensions are ```.mkv ``` and ```.flac```. The presence of a ```.``` earlier in the file name, like in the second example, does not effect the file extension. 

### Show File Extensions and Item Check Boxes

Being able to see file extensions and which files are currently selected will significantly reduce mistakes when working with files. To enable these (and please do):

1. Open File Explorer.
2. Click the ```View``` tab at the top.
3. Check the box next to ```View file extensions```.
4. Check the box next to ```Item check boxes```.

## Executable Files

An exactuable is an app file that runs on computers. Executables have a ```.exe``` file extension. Executables are generally safe to run if you know where they came from. But it is not uncommon for people to take advantage of those who know nothing of file extensions, and trick them into running an executable with viruses. So be wary of these files when pirating. If you intended to download a video or audio clip, and instead get a file with ```.exe``` at the end, DELETE IT. Unless it's the product of a mistake you made, it is almost certainly a virus. Never run executables that you don't trust. In general, if you dont recognize a file extension, look it up to make sure it is the media type you intended to download. For example, video files will almost always have ```.mp4``` and ```.mkv``` file extensions, NEVER ```.exe```. If you are pirating a videogame or software, an executable is what you SHOULD be getting, just make sure you trust it's source.

## Zip Folders

Note: The terms ```Zip Folder```, ```Zip File```, ```File Archive``` are **interchangeable**.

You will encounter zip folders A LOT as a pirate. ***File archiving***, or "zipping" is when a group of files is combined into a single file, so that they can be stored and transferred as one. By "combining", I mean compression, which simply makes files more compact, smaller. File systems treat zip folders as singular files, despite their name. That is, until they are unzipped and the contained files are seperated again.

The common types of zip folders can be indentified by their file extension. These are all zip folders, regardless of their different file extensions. Their different file extensions are indicative of a specific method of compression used to create the zip folder, each method having seperate origins.

Common Types of Zip Folder | Source
----------------------|------------
.zip | Basic format, default on most operating systems
.rar | Created by [WinRAR](https://www.rarlab.com/), paid software
.7z | Created by [7-Zip](https://www.7-zip.org/), free software

### 7-Zip and WinRAR

WinRAR is paid software, and is a tool for general zipping and unzipping purposes. RAR zip folders can only be properly **created** by WinRAR software, but can be unzipped with most other zip folder management applications. 7-Zip, like WinRAR, is a computer program for creating, viewing, and unzipping zip folders. The difference is that 7-Zip IS superior. It's free and easy to use. Please download it [here](https://mega.nz/file/xYREDATB#Ft19APie0V79WkZHh7UAX0oT5_RWLz8y4eH5EE_YwnI), as you WILL encounter zip folders as a pirate. To install, just open the file and follow the on screen installation instructions. Here's a quick reference to use it:

#### Viewing the Contents of Zip Folders

Right click the zip file, hover over ```7-Zip```, and select ```Open Archive```. You can select standard zip files in Windows 10 by simply double clicking them, but it is best practice to use the ```Open Archive``` option by default, to ensure support for non-standard zip files like ```.7z``` and ```.rar```. 

#### Zipping

1. Select the files or group of files you want to zip. 
   - You can select any group of files AND folders, all can be contained in a zip folder. 
2. Right click the files you want to zip.
3. Hover over ```7-Zip```.
4. You have 2 options.
  - Select ```Add to archive...``` to compress all selected files into a ```.zip``` zip folder.
  - Select ```Add to "<Name>.7z"``` to compress all selected files into a ```.7z``` zip folder.
    - \<Name\> here is a placeholder. For you, that space will display the name of the [parent directory](#Basic-Knowledge), or one of the files you are zipping. This is 7-Zip's attempt at giving a name to your zip folder, but you can change it once the zip folder is created.
    - I recommend using ```.7z```.

#### Unzipping (Extracting)

1. Right click the zip folder you want to unzip.
2. Hover over ```7-Zip```.
3. You have 2 options.
  - Select ```Extract files...```.
    - This will create a folder of the same name as the zip folder, with the zip folder's contents inside.  
  - Select ```Extract Here```.
    - This will extract the contents of the zip folder into the folder you are currently viewing, without creating any new folders.
4. Click ```OK```.

## IP Address

An IP address is very similar to a regular postal address. While a postal address labels where a location is in the world, an IP address labels "where" a computer is on the internet. It is a means by which computers identify and communicate with one another. An example of what an IP Address looks like is ```216.3. 128.12```, or ```209.43.71.34```. 

## File Hosters

File hosters have many names, such as cloud service, cloud, cloud hoster, file sharer, file sharing site, P2P site, etc. Any variation of these things is referring to the same thing, a service that stores files on their own computers, that can be accessed from anywhere. Because these file hosters allow users to not only store, but share files with others, they are used to by pirates to share content. The most well known example is Google Drive, other contendors being Onedrive, Box, Dropbox, Mediafire, etc. 

### MEGA

[MEGA](https://mega.nz) is the most popular file hoster among more experienced pirates. This is becaue of MEGA's end-to-end encryption, which means that no one can access stored content except for those with the link key. This secure-by-design security restricts even the MEGA company themselves from seeing your files, meaning that pirated content is much less likely to be discovered and removed from the site. Many of the tools, methods, and sites I reference through these guides will use MEGA, and so you should have some understanding of it specifically. 

A mega link, or link key, is a url that contains the key (kind of like a password) for a file or folder stored on MEGA. 

An example: ```https://mega.nz/folder/ObokBahB#8y4EKrQLVScGSx8WUitvpQ``` 

#### MegaDownloader

MegaDownloader is a download manager for MEGA. It is generally faster than downloading in-browser, and allows you to easily bypass download restrictions. Use is simple:

1. [Download MegaDownloader](https://mega.nz/file/xBYXSKYI#VCIwix0sZIpdXD_kGW_uV0pvAmU6c2rsZrXM2lE1zQ4), you can place it anywhere on your computer.
2. Open ```MegaDownloader.exe```.
    - Upon launching MegaDownloader for the first time, a settings menu will pop up. Click cancel in the lower right corner, as the default settings do not need to be touched.
3. Click the ```+``` button.
4. Paste the mega link into the box by pressing ```ctrl + v```.
    - You can add multiple links at once, just press ```Enter``` and paste again.
5. Click ```Browse``` and select where on your computer you want to place your downloads.
6. ```Start download``` and ```Create directory``` are enabled by default. I recommend keeping it that way.
7. Click ```Add links```.

You will see green progress bars fill up as your downloads go on. A green "Complete" and full progress bars will tell you that you downloads have finished. Right click on the name of any download and select ```Clean completed``` to clear out all finished downloads. 

#### Bypass MEGA download restrictions with MegaDownloader and a VPN

Should you be using MegaDownloader and your download comes to a hault, it is likely because MEGA has temporarily restricted downloads for your computer. They are able to identify you and your excess downloads by your IP address. To bypass this, you need to make your IP address appear different, which is the function of a VPN. Check out my [IPS Guide](ips-guide.md) for more info about VPNs and my recommendations/warnings concerning them. Note that this is a very involved process, and may not be worth it to some people. 

1. Though your downloads have been stopped, go ahead and click the stop button ```⬜```.
2. Open up the VPN of your choice and activate it.
3. Resume your download by clicking ```▶️```.
4. If your download is forced to a stop again, repeat steps 1-3 but with a different location selected on your VPN.
5. After a few cycles of this, you may be able to successfully download without a VPN again.

This is a wash-rinse-repeat type of thing. It is tedious and requires management, but it works.

## Torrenting

Typically, when you download anything off of the web, files are stored and distributed from one central server. That is called direct downloading, and is how all file hosters such as MEGA work. But with torrenting, a different download protocol, there is no central server. Rather, pieces of files are stored accross a network of computers, consisting of all the people who have downloaded from the torrent. The technology behind it is a little complicated, but you dont't need to understand it to use it. This download protocol is not necessarily tied to piracy, but rather is popular among pirates. I am putting this info here because you can use torrenting to download any media type, however, I personally recommmend it's use for movies ONLY. 

### Base Knowledge, Terminology, and Etiquette

- "Torrent" can be used as a noun or a verb. As a noun, a torrent is a file that you give to a torrent client, that then allows the torrent client to download the content associated with the torrent file. As a verb, a torrent refers to the act of downloading content using torrents. 
- The file extension of torrent files is ```.torrent```.
- A torrent client is a computer application for downloading and managing torrents. 
- A magnet link is a different way of torrenting. Rather than downloading a torrent file to give to your torrent client, magnent links can be clicked in-browser, prompting your torrent client to open, and start the download.

### WARNING

Torrenting is a legacy method of pirating, and while still very popular globally, there is no one touting it as the best and most modern way to pirate. Due to how torrenting works, with each torrent is a public list of all the IP addresses that interacted with the torrent. Because this list is so public, copyright owners of popular and current TV shows, movies, music, and video games will often sift through these IP addresses, locate the owners of said IP addresses, and send them complaint letters. The letters claim that the copyright violators owe a fine, or worse. This issue is easily circumvented by using a VPN, which obscures one's IP address. [Read more about VPNs here.](ips-guide.md#Virtual-Private-Networks-VPN) While **IT IS SAFE** to torrent **with a VPN**, I generally don't need it unless my usual sources don't have something specific I'm looking for. 

Do not let the special case of torrenting scare you from pirating, as this is literally the ONLY way you could ever face a consequence for pirating. And even as is, it is an easily solved issue. All other methods are safe, if you follow my instructions. 

### qBittorrent

#### Installation and Configuration

#### Use
