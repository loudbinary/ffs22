# ffs22

## Quick Links

* [Farming Simulator 2022 Server Management webpage](https://www.g-portal.com/int/f_s2022/FS2022PCConfigurations/getWiLink/829384) *NOTE REQUIRES https://g-portal.com* account, and permissions assigned by Loudbinary

Farming Simulator 2022 - Server management help

- [ffs22](#ffs22)
  * [Managing the server](#managing-the-server)
  * [Connecting to Server](#connecting-to-server)
    + [Adding Mods to Server](#adding-mods-to-server)
    + [Uploading Mods](#uploading-mods)
      - [Mobile Uploads](#mobile-uploads)
      - [Filezilla Uploads](#filezilla-uploads)
      - [Restarting services](#restarting-services)
    + [Restarting Server](#restarting-server)
    + [Changing Server setttings (map, password, mods, farm type, etc)](#changing-server-setttings--map--password--mods--farm-type--etc-)

## Managing the server

The [server management page](https://www.g-portal.com/int/f_s2022/FS2022PCConfigurations/getWiLink/829384) for Farming Simulator 2022.
The [HOME Page](http://45.35.207.49:8270/index.html?lang=en) you can change things like Server Load (CPU), Logged in Users, Game configuration, and Active Modes
The [MODS Page](http://45.35.207.49:8270/mods.html?lang=en) is where you can view actively loaded mods for currently running Farming Simulator services.

## Connecting to Server

To connect to the server, open Farming Simulator 2022 on our device.

Click *Multiplayer*

Click *Join Game*

When the server list shows up, look the right and select the *Game Name* box, and type and hit enter when done.

You can enter the server by double click on it.

*You will be prompted for a password*

Ask one of the other folks for that, and walla.

```
!!Bullyard
```

*NOTE* Before DOUBLE Clicking to enter the game, click X for details and then you'll notice (I Think X Again) will allow you to download all the DLC's in use without doing them one at a time.


### Adding Mods to Server

Installing from your *Mobile* device required you to download the mod to your phone, upload to server, and finally restart the server.

Uploading mods from your phone *can only be done one at a time*. 

While, uploading mods from a computer can be done many at one.
First you're going to need to install Filezilla on your computer, you can do quickly through [clicking this link](https://ninite.com/filezilla/ninite.exe)

Doing so, will download a file, you need to run, which will then install Filezilla for you with all sane defaults.

Once you have Filezilla installed, you will need to log into the [mod directory on server](ftp://45.35.207.49:50211/)

You will need to get the username and password from myself, or someone in the know.

Once that is processing, you will be asked to choose an application to open site.  Here you will select Filezilla.

Browse to *C:\Program Files\FileZilla FTP Client* and select application *filezilla.exe* - which will open it up, connected to server.

NOW that the hard part is out of the way, lets upload some files.

Go to the [Farming Simulator MODHUB](https://www.farming-simulator.com/mods.php?lang=en&country=us&title=fs2022)

Next select a category to filter mods.  

Find the mod you want making sure of these two important details for any mob you're uploading.

Using the *government subsidy mod* as an example: [click here](https://www.farming-simulator.com/mod.php?lang=en&country=us&mod_id=223367&title=fs2022)

Check out the details about its use:

* Platform *PC/MAC, PS4, PS5, XB1, XBS*
* Game Farming Simulator 22

Once that is verified click the DOWNLOAD BUTTON. 

The mod will be downloaded to your device. 

### Uploading Mods

#### Mobile Uploads

Using mobile device means you must use the [MODS Page](http://45.35.207.49:8270/mods.html?lang=en) listed above, go to bottom, and click browse and select the file downloaded.

#### Filezilla Uploads

using the already opened application, use these settings:

Local Site: *%HOMEPATH%\Downloads* (Downloads folder for user)

Remote Site: */profile/mods*

Then click upload.  

#### Restarting services

Before restarting, you need to active the mods you want enabled.
At the [HOME Page](http://45.35.207.49:8270/index.html?lang=en), you must first STOP the server.
Then on same page, click ALL Button at bottom to select all.  
SAVE Settings
Start server.
Again all from the [HOME Page](http://45.35.207.49:8270/index.html?lang=en)

You should now be able to see your new mod in the list on the [MODS Page](http://45.35.207.49:8270/mods.html?lang=en).

### Restarting Server
### Changing Server setttings (map, password, mods, farm type, etc)
