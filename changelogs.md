---
title: Changelogs
description: All changelogs of Durty Cloth Tool
published: true
date: 2023-02-11T18:13:21.497Z
tags: durtyclothtool, changelog
editor: markdown
dateCreated: 2023-02-11T18:13:21.497Z
---

# Durty Cloth Tool v2.5.0

## ??Important Project Migration Note
This update changes the way your cloth project is saved and referenced cloth models and textures are managed internally. 
Due to this change, on first time loading a older project, it will be automatically migrated to the new project format without any needed input from you. As this could take some while, you will be prompted with a dialog to confirm this. 

In this process all your previously added, 'linked', clothes will be copied to a by Cloth Tool managed "data" folder.

[![](https://assets.plebmasters.de/durtyclothtool/images/v25/durty-cloth-tool-project-migration.gif)](#)
_Read more "technical information" about the changed project new projects formats in the end of this post._

## ?Update highlights
This is **the biggest cloth tool update** so far, almost one year of work, lots of research and testing went into this. Thanks to every suggestion on this GitHub or my Discord and special thanks to the @Clothes-Experts that decided on helping testing and improving this version.

Lets dive into some of the highlighted features and additions of this new version.

### ?? 3D Previewer
Introducing the 3D Preview Feature. This exciting new feature allows you to **easily visualize and analyze your cloth models and textures** in a whole new dimension. With the Cloth 3D Preview Feature, you can:

 - **Preview model and texture combinations with ease**, using the context menu options, the preview button or by simply double clicking any item.
 - Get a full **preview of your ped models and see cloth models in motion**, allowing you to test whether clothes are correctly rigged.
 - **Apply animations** to your ped models and see the clothes in motion for an even more comprehensive analysis.
 - Benefit from **different render modes** that help you identify any cloth model issues.
 - Take advantage of the **wireframe option to see the model structure**, and the ped skeleton option to see the ped bones.
 - **Switch between different levels of detail (LOD)** to preview the models in a range of resolutions.
 - **Explore the Models & Texture data** tabs for a more in-depth analysis of your cloth models.

This feature is an essential tool for anyone looking to bring their models and textures to life and is sure to take your 3D modeling to the next level. 

### Example of male clothes, changing light direction, switching thru different Level of Details & animating ped
[![](https://assets.plebmasters.de/durtyclothtool/images/v25/3d-preview-male-example.gif)](#)

### Example of female clothes, animating, showing grid, wireframe & only selected cloth
[![](https://assets.plebmasters.de/durtyclothtool/images/v25/3d-preview-female-example.gif)](#)

### Example of different rendermodes allowing deeper texturing insights
[![](https://assets.plebmasters.de/durtyclothtool/images/v25/3d-preview-rendermode.gif)](#)


### ?? Tops with working duffel Bags, Hoodie hairs & Masks that cut or remove hairs 
This update introduces various new options to **make use of even more GTA V cloth related game mechanics**. Find out more about all new clothing options below.

### Cut hairs for hoodie clothes (tops & undershirts)
Configure whether your **hoodie top / undershirt should cut hairs** to make hoodies not glitch.

[![](https://assets.plebmasters.de/durtyclothtool/images/v25/showcase-hoodie-hairs-option.png)](#)

### Remove hat in vehicle
Set **hats to automatically be removed when the player enters a vehicle** and reapplied when he leaves it again. Making it not glitch thru the vehicle roof.

[![](https://assets.plebmasters.de/durtyclothtool/images/v25/showcase-removehatvehicle-option.png)](#)

### Without 'Remove hat in vehicle' option, hat will possibly glitch thru roofs
[![](https://assets.plebmasters.de/durtyclothtool/images/v25/durty-cloth-tool-removehatinvehicle_flag_off.gif)](#)

### 'Remove hat in vehicle' option enabled, hat will be unequipped in vehicle
[![](https://assets.plebmasters.de/durtyclothtool/images/v25/durty-cloth-tool-removehatinvehicle_flag_on.gif)](#)

### Cut or remove hairs for masks (berds)
Configure **masks (berds) to automatically cut or remove hairs completely** whenever needed to perfectly fit your masks without glitching hairs.

[![](https://assets.plebmasters.de/durtyclothtool/images/v25/showcase-mask-hair-options.png)](#)

### Fixed addon tops (jbib) vanilla game duffel bags invisible
Previously all vanilla game duffel bags would not work (be invisible) with all your addon tops (jbibs), this is now **automatically fixed** and will work after regenerating your cloth pack with this new update.

### Previously 'unfixed' addon top with duffel bag combined
[![](https://assets.plebmasters.de/durtyclothtool/images/v25/durty-cloth-tool-addonjbib_duffelbag_notfixed.gif)](#)

### Now 'fixed' addon top with duffel bag combined
[![](https://assets.plebmasters.de/durtyclothtool/images/v25/durty-cloth-tool-addonjbib_duffelbag_fixed.gif)](#)


### ? Tons of automatic error analyzing
Introducing a new and improved error handling system, you can now **easily identify and fix issues that could potentially break your clothes**, before you build.

With this new feature, you'll be able to:
  - **Quickly categorize issues** as Errors, Warnings, or Informations.
  - **Identify and fix Errors that could break your clothes**, ensuring that your projects are always in tip-top shape.
  - Take advantage of **various Warnings, ranging from missing LOD levels**, invalid model files, missing embedded textures, and more, to improve the quality of your cloth models and textures.
  - Receive **Informational hints that provide valuable insights** into your cloth projects.

Elevate your cloth projects and stay ahead of the game with our new error handling system.


### Example of some information, warnings & errors
[![](https://assets.plebmasters.de/durtyclothtool/images/v25/durty-cloth-tool-errors-warnings-infos.gif)](#)


### ?? Easy optimizing of cloth textures and embedded model textures
Say goodbye to manual texture optimization and hello to effortless efficiency with this update. The Texture Optimization Feature is here to **revolutionize the way you optimize your textures and models** with ease.

With a range of easily optimizations and edits to apply, including:
  - **Automatic optimization of the compression format** for your textures, ensuring the best quality with the smallest file size, or choose your own compression format to be applied.
  - **Automatic generation of the suggested amount of mipmap levels** for your texture, providing the perfect balance between quality and performance.
  - Seamless adjustments to your textures with the **automatic adjustment to the next power of two** width and height.
  - **Easy downscaling of your textures** to your preferred size, ensuring that your models look great at any resolution.
  - Effortless compatibility with **embedded model textures and cloth texture variations**, without the need for any other tools or manual editing.

With the Texture Optimization Feature, you can streamline your workflow and focus on creating the best GTA V cloth pack possible.

### Example of easily optimizing compression format, mipmaps, power of two & more
[![](https://assets.plebmasters.de/durtyclothtool/images/v25/durty-cloth-tool-texture-optimizing.gif)](#)


### ?? Drag & Drop
Making it **easier than ever to import files**. With this new feature, you can:
  - **Effortlessly import files by simply dragging and dropping** them into the tool, whether they're from Windows File Explorer, OpenIV, or CodeWalker.
  - Save time and streamline your workflow by **eliminating the need to manually export & import files** one-by-one.
  - Enjoy a **more user-friendly and intuitive experience adding files** from GTA V file explorers

### Example of dragging and dropping files from OpenIV and CodeWalker
[![](https://assets.plebmasters.de/durtyclothtool/images/v25/durty-cloth-tool-dragndrop.gif)](#)


### ??? Various new import & export formats
We're excited to announce a suite of **new import and export file formats that make it easier than ever** to work with clothes.

With this new update, you can:
  - Enjoy faster workflows (especially when using Blender) with the **addition of CodeWalker XML import and export support** for cloth drawables and textures.
  - Have more flexibility when editing your cloth textures with **new DDS and PNG export options**.
  - **Quickly add cloth textures straight from a image**, from a variety of image formats including PNG, JPG, TGA, and BMP, which will automatically be converted to YTD.

### Example of exporting to & importing from different new file formats: CodeWalker XML, PNG, DDS
[![](https://assets.plebmasters.de/durtyclothtool/images/v25/durty-cloth-tool-new-file-formats.gif)](#)


### ??? New projects format & file/data handling
All **files related to a cloth project will be saved & managed in one single folder**, that could easily be shared & does prevent accidentally building files to some unwanted location, deleting hundreds of files in advance (People selected Desktop as output and files got deleted there..).

  - Durty Cloth Tool will manage all files added to your project on its own, which **takes you the hassle to manage all imported files on your own** and removes cases where you accidentally deleted a file used in any of your cloth projects, breaking it completely.
  - Files that are added to the project will now be imported to a "data" subfolder of your output folder defined in the build settings


### ?? Dynamic config builders
The Dynamic Config Builder options are here to **provide you all the configuration files** you need to work with framework plugins like xnTattoos, qb-tattooshop, ESX-TattooShop, or any other similar config files. 

With this powerful new feature, you can:
  - **Easily provide example configuration entries** for various framework plugin configurations, making the setup process a breeze.
  - **Access clothes and tattoos info dumps** filled with valuable information for your developers, such as scripting IDs, types, and names.

[![](https://assets.plebmasters.de/durtyclothtool/images/v25/showcase-dynamic-config-builders.png)](#)

### Example of generating different config files and viewing them in Visual Studio Code
[![](https://assets.plebmasters.de/durtyclothtool/images/v25/durty-cloth-tool-dynamic-config-builders.gif)](#)

---

### ?? Technical explaination for new project data keeping
In previous versions, as soon as you add any drawable or texture file, a reference to this file has been saved. This reference is the full file path leading to the file you have selected. 
Basically it is not adding the drawable, its just _linking_ to it. This behaviour is not common for applications that look like managing files, like Durty Cloth Tool does. 

**This can and does cause issues like**
- moving the whole clothes project file is nearly to impossible if not properly managed on your own
- you will have to take care of managing files properly, because if not done properly you could end up deleting files from your disk that are used in any cloth project
- new people can run into issues like; downloading clothes from the internet, then selecting the drawable file in the downloads folder. When file gets overwritten or deleted in the future, it will just break cloth projects

**It does bring some pros tho**
- "Experienced" users that are aware of the possible issues can manage clothes for multiple cloth projects that share the same cloth files (If this is a use case?) 
- Possible duplicate of same cloth files on the disk can be prevented (saves some disk space)


The **change introduced with this version** is that adding a drawable or texture file, will basically import (copy) the file into a by the cloth tool managed "data" folder.
This will make managing clothes files a no-brainer as people will not have to pay any attention to that anymore. The cloth tool will manage all files in a folder and delete them there if they are unused, while making sure to not delete it instantly (so you could still delete clothes from your project for testing, exit the tool and load the project again and they would be there again.). 

People could still setup & manage "raw/source" folders if wanted to keep the original files somewhere, to add from that. Imported / managed files by Durty Cloth Tool will receive cryptic hash names like `936DA01F-9ABD-4D9D-80C7-02AF85C822A8.ydd` as it is not meant to manually delete, edit or replace files in the data folder.

## ??Full Changelog:
```markdown
# Added 3D Previewer
  - Easily 3D preview model & texture combinations using the context menu options, the preview button or double clicking any item
  - Full ped preview & cloth model only preview
  - Apply animations to the ped and see clothes in motion to test whether clothes are correctly rigged
  - Different render modes that help analyzing cloth model issues
  - Wireframe option to see model structure
  - Ped skeleton option to see ped bones 
  - Level of Detail switch to preview different level of detail (LOD) models of your cloth model
  - Models & Texture data tabs to get more deep insights
 
# Added new projects format & file handling
  - Durty Cloth Tool will manage all files added to your project on its own, which takes you the hassle to manage all imported files on your own and removes cases where you accidentally deleted a file used in any of your cloth projects, breaking it completely.
  - Files that are added to the project will now be imported to a "data" subfolder of your output folder defined in the build settings
  - Manually editing any files in this directory is not recommended, please use either "Remove" or "Replace" context menu options to edit any files
  - When first time loading old / previous cloth project, they will automatically be migrated to the new project type
 
# Added tons of error analyzing and features to warn about possible cloth issues
  - Durty Cloth Tool now treats issues in the category of errors, warnings and informations. Errors will possibly break / make your clothes not work and therefore need to be fixed before build, where as warnings are just personal recommendations to improve any cloth model or texture and informations are just small informational hints.
  - There are different kinds of warnings now ranging from missing LOD levels, possibly invalid model files, missing embedded textures or textures that are not pow2, too big or have no mip map levels and tons more

# Added easy optimizing of cloth textures and embedded model textures
  - Automatically optimize compression format to the best choice for the given texture, or select your own compression format to be applied
  - Automatically generate the suggested amount of mipmap levels for your texture
  - Automatically adjust textures to the next power of two width & height
  - Easily downscale textures to the preferred size
  - Works for embedded model textures & cloth texture variations, magically without the need to edit anything in any other tool

- Added dynamic config builders, easily provide example configuration entries for xnTattoos, qb-tattooshop, ESX-TattooShop or any other similar config files. Also provides clothes & tattoos info dumps that contain all scripting ids & information needed for your developers to work with the new clothes
- Added options to create complete GTA DLC replace resource, by allowing to assign different male & female cloth collection names or select from a list of GTA 5 dlcs to automatically set the names
- Added drag & drop support from windows file explorer, OpenIV or CodeWalker, just drag your files into the tool and it will automatically import them
- Added facial overlays support (beards, makeup, aging, body hair, eyebrows etc), easily add any facial overlay texture and let the Durty Cloth Tool to the rest (very experimental, known to not work as addons... need more investigation)
- Added warning before trying to exit application when project is not saved, also adds more information to the app title bar
- Added multi selection support to remove project items or textures
- Added absolute & relative drawable id generation in the tool, the tool will now automatically calculate the target absolute drawable id (This only works when the cloth pack will be the first or only cloth pack to be loaded)
- Added context menu for project items & textures, with options to quickly Remove, Replace, Export, Copy Names or 3D preview
- Added option to customize high heel height, alternatively to the default high heel height value
- Added option to set custom cut value for hairs, alternatively to the default cut value
- Added support for RageMp as official target resource type 
- Added BERD drawable type option to "Remove hat in vehicle", will automatically remove the hat while in vehicle and put on when exiting vehicle
- Added DEL hotkey for quickly deleting selected items / textures (Confirmation dialog will still open)
- Added options for masks to cut hairs or remove hairs completely when worn
- Added option for "Hoodie hairs" on tops (jbibs) and undershirts (accs)
- Added support for all basegame duffel bags to properly work with addon tops (jbibs), they should not be invisible weared in combination with addon jbibs now
- Added CodeWalker XML import & export support for cloth drawables + cloth textures, enabling faster workflows when working with Blender
- Added DDS & PNG export options for cloth textures for more easier editing of your clothes
- Added support for adding cloth textures from png, jpg, tga & bmp images directly (They get auto converted to YTD)
- Added various new file formats for importing cloth textures from, like png, jpg, tga & bmp
- Improved logging overall, previous session logs are now saved, all logs in general provide more information 
- Improved mass adding from folders (previously taking ages & freezing application), Performance increases, can understand and import much more file naming schemas, will not only search top directory
- Improved various messages & dialogs like item duplicate & license error dialogs. Buttons should be better understandable now
- Improved alt:V resources configs, from old .cfg file schema, to new .toml file schema
- Fixed SP cloth packs not working
- Fixed possible crash cause when using decorations (tattoos) meta
```