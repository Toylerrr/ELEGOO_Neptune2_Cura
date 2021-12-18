## :warning: USE AT YOUR OWN RISK :warning:
Just to cover my ass


![Img of Cura with Neptune 2](https://i.imgur.com/2yjM7Hl.png) 
## Overview 

This is the Cura profile that was made by ELEGOO and I modified it to work with the newest version of cura and removed some unused defaults. I have also added the STL of the bed from the original Neptune 2 STEP files

## How to install
<b>Hard</b>: Just download the master zip and drop the contents into your cura install folder or Appdata

<b>Easy</b>: Download the plugin version from the [Releases](https://github.com/Toylerrr/ELEGOO_Neptune2_Cura/releases) section and drag and drop into the cura windows

## Better Profiles
Just-Trey made some printer profiles for this machine definition. 

Those can be found here: https://github.com/just-trey/elegoo_neptune_2_CHEP_cura_profiles

## Alternate Bed Mesh
 Merrik over on Thingiverse made an alternate bed mesh you can find that here: https://www.thingiverse.com/thing:5141570

## How to get icons on print screen

<ol>
<li>Install the MKS Wifi Plugin on the marketplace or here https://github.com/Jeredian/mks-wifi-plugin</li>
<li>Then after adding the printer click setting>printers>manage printers </li>
<li>Click the MKS Wifi Connection </li>
<li>Click add and when it promps for an IP address put 127.0.0.1</li>
<li>Then click image settings then click default</li>
</ol>

![Setting Picture](https://i.imgur.com/THrXDxr.png)


## How to get MKS Wifi to show up when outdated

Goto:
<ul>
<li>Windows: %AppData%\cura\<version>\plugins\MKSWifiPlugin\MKSWifiPlugin</li>
<li>macOS: /Users//Application Support/cura/plugins/MKSWifiPlugin/MKSWifiPlugin//</li>
<li>Linux: ~/.local/share/cura/plugins/MKSWifiPlugin/MKSWifiPlugin/</li>
</ul>
  
Open the plugin.json file <br>
Find the line that says maximum_cura_version<br>
Change that to "4.10" (or whatever is current)<br>
Save and restart Cura<br>

