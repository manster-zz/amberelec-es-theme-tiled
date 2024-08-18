# Edited ES-Theme-Tiled for 4:3 handheld devices

Edited [ES-Theme-Tiled](https://github.com/GeekRhapsody/es-theme-tiled) theme to have better compatibility for 4:3 devices (640x480) with AmberELEC firmware. 

Tested on R36S with AmberELEC-RG351MP.aarch64-prerelease-20240804_1341.img.

<table>
  <tr>
    <td><a href='https://github.com/user-attachments/assets/5c2547f6-31e7-4841-b7d7-adf93a99e5fb'><img src="https://github.com/user-attachments/assets/5c2547f6-31e7-4841-b7d7-adf93a99e5fb"  width="300" /></a></td>
    <td><a href='https://github.com/user-attachments/assets/22f1c453-5aa8-4ca7-bf83-b776fa16e89f'><img src="https://github.com/user-attachments/assets/22f1c453-5aa8-4ca7-bf83-b776fa16e89f"  width="300" /></a></td>
    <td><a href='https://github.com/user-attachments/assets/c80fdc0a-0d59-494d-b1a5-d4dc4ae53a68'><img src="https://github.com/user-attachments/assets/c80fdc0a-0d59-494d-b1a5-d4dc4ae53a68"  width="300" /></a></td>
  </tr>
</table>

## Changes:
* Changed default gamelist view style to "detailed"
* Adjustments in the detailed game list view (sizes and positions)
* added options for preview video in the detailed view (game list)
  * no
  * yes
  * yes (1s delay)
  * yes (2s delay)
* added options for displayed metadata in the detailed view (game list)
   * Style 1 (play time, times played, last played, developer, publisher, release date)
   * Style 2 (play time, times played, last played, release date)
   * game description
   * no

## Files changed
* theme.xml
* gamelistview/detailed.xml
* gamelistview/detailedmd.xml (new file)
* video.xml (new file)

## Credits
GeekRhapsody for [ES-Theme-Tiled](https://github.com/GeekRhapsody/es-theme-tiled)

>Assets for the Modern style and controller icons taken from Alekfull-NX: https://github.com/fagnerpc/Alekfull-NX

>Assets for the Carbon style taken from es-theme-carbon: https://github.com/fabricecaruso/es-theme-carbon

>Assets for the Controllers style taken from es-de-moderntheme-nsoicons: https://github.com/szymon-kulak/es-de-moderntheme-nsoicons by Szymon Kulak

>Assets and code structure for system indicators taken from canvas-es: https://github.com/Siddy212/canvas-es by Siddy212

>Used screenshots for systems : https://www.screenscraper.fr/

>Thanks to mikakunin for the additional system art



***

# Original readme:

# ES-Theme-Tiled 
A simple, clean, grid-based EmulationStation theme designed for Steam Deck and other Handhelds running Batocera or RetroBat

## **System Grid**
![System Grid](./screenshots/systemgrid.png)

## **Default Grid**
![Game Grid](./screenshots/gamegrid.png)

## **Box Grid**
![Box Grid](./screenshots/gamegrid2.png)

## **Marquee Grid**
![Marquee Grid](./screenshots/gamegrid3.png)

## Colorways
- Extra Dark
- Dark
- Steam OS

## **Acknowledgments**
Assets for the Modern style and controller icons taken from Alekfull-NX: https://github.com/fagnerpc/Alekfull-NX

Assets for the Carbon style taken from es-theme-carbon: https://github.com/fabricecaruso/es-theme-carbon

Assets for the Controllers style taken from es-de-moderntheme-nsoicons: https://github.com/szymon-kulak/es-de-moderntheme-nsoicons by Szymon Kulak

Assets and code structure for system indicators taken from canvas-es: https://github.com/Siddy212/canvas-es by Siddy212

Used screenshots for systems : https://www.screenscraper.fr/

Thanks to mikakunin for the additional system art
