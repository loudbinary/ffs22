# ffs22
Farming Simulator 2022 - Server management help

- [ffs22](#ffs22)
  * [Current mod list](#current-mod-list)
  * [Managing the server](#managing-the-server)
  * [Connecting to Server](#connecting-to-server)
    + [Adding Mods to Server](#adding-mods-to-server)
    + [Uploading Mods](#uploading-mods)
      - [Mobile Uploads](#mobile-uploads)
      - [Filezilla Uploads](#filezilla-uploads)
      - [Restarting services](#restarting-services)
    + [Restarting Server](#restarting-server)
    + [Changing Server setttings (map, password, mods, farm type, etc)](#changing-server-setttings--map--password--mods--farm-type--etc-)


## Current mod list

```bash
Beehive 	1.0.0.0 	GBModding 	FS22_BeehiveGB.zip 	2.43 MB 	3 	No 		
Mahindra Retriever Plus 	1.0.0.0 	raulycristi1 [VSR Mod... 	FS22_Retriever_Plus.zip 	9.74 MB 	2 	No 		
Additional Decoration Package 	1.0.0.1 	Piesel 	FS22_AdditionalDecorationPackage... 	41.77 MB 	  	No 		
American Trucks 	1.0.0.0 	Adams Kong 	FS22_AmericanTrucks.zip 	34.16 MB 	  	No 		
Grimme SL8022 Quantum And TC816 Autoload 	1.0.0.0 	Dr.Drulia 	FS22_Autoload_Belt.zip 	5.89 MB 	  	No 		
AutoLoad IT-Runner Platform 	1.0.0.0 	erShaba 	FS22_Autoload_Platform_ITRunner.zip 	3.77 MB 	  	No 		
BR Small Shed 	1.0.0.0 	ML Modding, DH Modding 	FS22_BR_Small_Shed.zip 	2.96 MB 	  	No 		
Big Bag And Support Package 	1.0.0.0 	Farm Centro Sul 	FS22_Bags_and_Support_Package.zip 	3.58 MB 	  	No 		
Beehives Pack 	1.0.0.0 	Zoli708 	FS22_Beehives_Pack.zip 	0.44 MB 	  	No 		
BigBags Cattle Pack 	1.0.0.0 	FSG Modding 	FS22_BigBagCattlePack.zip 	0.96 MB 	  	No 		
Buyable Large Stack Of Bales 	1.0.0.0 	MechMods 	FS22_BuyableLargeStackBales.zip 	0.06 MB 	  	No 		
Cowshed Pack 	1.0.0.0 	[DMI]20mmNormandy 	FS22_CowshedsPack2.zip 	18.63 MB 	  	No 		
Decorative Details Pack 	1.1.0.0 	TrianglesTrouble 	FS22_DecorativeDetailsPack.zip 	11.36 MB 	  	No 		
Decorative Rock Pack 	1.0.0.0 	OlaHaldor 	FS22_DecorativeRocks.zip 	4.13 MB 	  	No 		
Field Creator 	1.0.0.0 	TF 2020 MODS 	FS22_FieldCreator.zip 	0.27 MB 	  	No 		
Flower Pots Pack 	1.0.0.0 	TrianglesTrouble 	FS22_FlowersPack.zip 	4.19 MB 	  	No 		
Forestry Bridge Pack 	1.0.0.0 	OlaHaldor 	FS22_ForestryBridges.zip 	1.67 MB 	  	No 		
Greenhouses With Seeds And Fertilizer 	1.0.0.0 	Happy_M0le 	FS22_GreenHousePack.zip 	3.78 MB 	  	No 		
Halogen Lamp 	1.0.0.0 	Piesel 	FS22_HalogenLamp.zip 	0.43 MB 	  	No 		
IBC And Pallets Stack 	1.1.0.0 	Adub Modding ABP Team 	FS22_IBCstack.zip 	1.15 MB 	  	No 		
Kombi 	1.0.0.0 	Erik isac, Agro Mods 	FS22_Kombi.zip 	5.54 MB 	  	No 		
Kroeger Agroliner Pack 	1.0.0.1 	HR Forst und Fahrzeugbau 	FS22_Kroeger_Pack.zip 	14.92 MB 	  	No 		
Lamps Elektrosvit CSSR 60 - 90 Years 	1.0.0.0 	Maca 	FS22_Lamp.zip 	3.77 MB 	  	No 		
Liftable Pallets And Big Bags 	1.1.2.0 	Jos 	FS22_LiftablePallets.zip 	3.46 MB 	  	No 		
Light Poles Package 	1.0.0.0 	erShaba (VSR Modiing ... 	FS22_LightPolesPack.zip 	0.73 MB 	  	No 		
Lizard TRA 500 	1.5.0.0 	Agro Tonho 	FS22_Lizard_TRA500.zip 	11.32 MB 	  	No 		
Multiplayer Sign Pack 	1.0.0.0 	FSG Modding 	FS22_MPsignPack.zip 	1.77 MB 	  	No 		
Multi Sign 	1.0.0.1 	Dominick 	FS22_Multi_Sign.zip 	0.11 MB 	  	No 		
Pigsty 	1.0.0.0 	MefiuFs 	FS22_OldDEPigShed.zip 	12.14 MB 	  	No 		
Workshop Pack 	1.0.0.0 	Fudzo 	FS22_PackOfWorkshops.zip 	19.64 MB 	  	No 		
Pickups Pack 	1.0.0.0 	Adams Kong 	FS22_PickupsPack.zip 	14.59 MB 	  	No 		
Placeable Street Lamps 	1.0.0.0 	MechMods 	FS22_PlaceableStreetLamps.zip 	1.70 MB 	  	No 		
Government Subsidy 	1.0.0.0 	Realismus Modding 	FS22_RM_Subsidy.zip 	2.35 MB 	  	No 		
Lizard RTV Max 6000 	1.0.0.0 	SleutjesModding 	FS22_RTV_MAX_6000.zip 	6.68 MB 	  	No 		
Randon Dolly 	1.0.0.0 	Erik Isac, Agro Mods 	FS22_RandonDolly.zip 	9.59 MB 	  	No 		
Brick Fence With Sliding Gates 	1.0.0.0 	Tarczi007 	FS22_SlideBrickFence.zip 	1.61 MB 	  	No 		
Animated Shed Pack 	1.0.0.0 	ALiEN JiM 	FS22_animatedShedPack.zip 	15.28 MB 	  	No 		
Bunker Silo Set 	1.0.0.0 	TopAce888 	FS22_bunkerSiloSet.zip 	2.35 MB 	  	No 		
Large Cow Barn - 240 Animals 	1.1.0.0 	FLusty94 	FS22_cowBarnLarge_MoreAnimals.zip 	9.14 MB 	  	No 		
Cow Breeding Pen 	1.0.0.0 	Brummie Farmer 	FS22_cowBreedingPen.zip 	0.29 MB 	  	No 		
Equestrian Arena 	1.0.0.0 	Black Swan Modding Team 	FS22_equestrianArena.zip 	6.15 MB 	  	No 		
Farm Supplies Production 	1.0.0.0 	OmaTana 	FS22_farmSupplyProduction.zip 	7.34 MB 	  	No 		
Garden Lights Pack 	1.0.0.0 	BlendArt 	FS22_gardenLightPack.zip 	0.69 MB 	  	No 		
Medieval Granary 	1.0.0.0 	OmaTana 	FS22_granary.zip 	3.85 MB 	  	No 		
Lizard Continental 	1.0.0.0 	Vector Man 	FS22_lizardContinental.zip 	12.32 MB 	  	No 		
Metal Fence With Gates 	1.0.0.0 	TopAce888 	FS22_metalFenceWithGates.zip 	2.54 MB 	  	No 		
Midwest Production And Feed Pack 	1.0.0.0 	Schultz Modding 	FS22_midwestProductionPack.zip 	7.12 MB 	  	No 		
No Mans Land 	1.2.0.0 	ALiEN JiM 	FS22_noMansLand.zip 	61.16 MB 	  	No 		
Old Pig Fattening Barn 	1.0.0.0 	Razak 	FS22_oldPigstable.zip 	7.72 MB 	  	No 		
Picnic Decoration Pack 	1.0.0.0 	OmaTana 	FS22_picnicPack.zip 	2.35 MB 	  	No 		
Seasonal Deco 	1.0.0.0 	OmaTana 	FS22_seasonalDecoration.zip 	8.89 MB 	  	No 		
Modern Shed 	1.0.0.0 	[DMI]20mmNormandy and... 	FS22_shedModernColourablePack.zip 	4.69 MB 	  	No 		
Placeable Snowmen 	1.0.0.0 	TopAce888 	FS22_snowmen.zip 	0.28 MB 	  	No 		
StalkBuster Pack 	1.0.0.0 	Ria Modding 	FS22_stalkBusterPack.zip 	0.02 MB 	  	No 		
Tensionbelt Support 	1.0.0.0 	Dor_Schmied 	FS22_tensionbelt.zip 	12.93 MB 	  	No 		
AGI Pack 	1.1.0.0 	GIANTS Software 	agiPack.dlc 	  	  	Yes 	  	
Antonio Carraro Pack 	1.1.1.0 	GIANTS Software 	antonioCarraroPack.dlc 	  	  	No 	  	
CLAAS XERION SADDLE TRAC Pack 	1.1.0.0 	GIANTS Software 	claasSaddleTracPack.dlc 	  	  	No 	  	
ERO Grapeliner Series 7000 	1.0.0.0 	GIANTS Software 	eroPack.dlc 	  	  	No 	  	
Kubota Pack 	1.1.0.0 	GIANTS Software 	kubotaPack.dlc 	  	  	No 	  	
Vermeer Pack 	1.0.0.0 	GIANTS Software 	vermeerPack.dlc 	  	  	No 	  	
```
## Managing the server

The [server management page](https://www.g-portal.com/int/f_s2022/FS2022PCConfigurations/getWiLink/829384) for Farming Simulator 2022.
The [HOME Page](http://45.35.207.49:8270/index.html?lang=en) you can change things like Server Load (CPU), Logged in Users, Game configuration, and Active Modes
The [MODS Page](http://45.35.207.49:8270/mods.html?lang=en) is where you can view actively loaded mods for currently running Farming Simulator services.

## Connecting to Server

To connect to the server, open Farming Simulator 2022 on our device.
Click *Multiplayer*
Click *Join Game*
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

To restart services to [HOME Page](http://45.35.207.49:8270/index.html?lang=en) and look for the RESTART Button, and click it, and a few seconds later it will be completed.  
You should now be able to see your new mod in the list on the [MODS Page](http://45.35.207.49:8270/mods.html?lang=en).

### Restarting Server
### Changing Server setttings (map, password, mods, farm type, etc)
