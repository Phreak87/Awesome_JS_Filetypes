# Awesome_JS_Filetypes

Awesome list of open source (not commercial!) Javascript Web-Frontend Librarys for handling different filetypes directly in the Browser.
Please extend this list if you miss something.

## Browser-native handlings (you don´t need Javascript, no Browser plugins!)
| Library     | Description                | Postfixes                                                |
|:------------|:---------------------------|:--------------------------------------------------------:|
| Chromium 85 | Video                      | ogv, mp4, webm
| Chromium 85 | Audio                      | mp3, wav, ogg
| Chromium 85 | Images                     | png, ico, bmp, jpg, gif
| Chromium 85 | Documents                  | pdf

## Compression
| Library                                                           | Description             | Postfixes                                                |
|:------------------------------------------------------------------|:------------------------|:--------------------------------------------------------:|
| [ArchiveJS](https://github.com/nika-begiashvili/libarchivejs)     | WASM-Port of [libarchive](https://github.com/libarchive/libarchive) | Tested: Zip, 7Zip, Rar (V4,V5), TAR                      |
| RarJS         | RarJS                   | Rar (V4,V5)                                              |                                                             |
| ZipJS         | ZipJS                   | Zip                                                      |                                                             |
| TarJS         | TarJS                   | Tar                                                      |                                                             |

## 3D
| I | Library                                                 | Description             | Postfixes                                                |
|:--|:--------------------------------------------------------|:------------------------|:--------------------------------------------------------:|
| X | [ThreeJS](https://threejs.org/)                         | 3D-Library              | stl, obj, gltf, assimp, babylon, collada, awd, svg, vrml, vtk, tga, pdb, ply, ,  ...?
| X | GCodeReader                                             | 3D-Print Library        | g, gco, gcode (and all GCode types)                      
| X | Hangar                                                  | 3D-View of Hangar Files | ac3d (.ac)
| X | [NGLViewer](https://github.com/nglviewer/ngl)           | Atoms, molecules        | .pdb,.cif,.cif.gz, mmtf,gro,mtl,ply,kin,pqr,dx.gz,
| X | ...                                                     | ...                     | dxbin,ccp4, sdf,obj,cub,map.gz, ctm,cns,xml,brix,dsn6,
| X | ...                                                     | ...                     | ctm,cns,xml,brix,dsn6prmtop,mol2,dcd,psf,cube,cube.gt,ent,pdbqt, mrc,dcd,dcd.gz
| X | OpenJSCad                                               | CAD-Modelling           | jscad, openscad                                          
| X | SceneJS                                                 | 
| X | ThreeDXF                                                | DXF
| X | WebXF                                                   | 
| X | WEXBIM                                                  | Wexbim
| X | X3Dom                                                   | 
| _ | PlasIO                                                  | PointCloud

## AI
| Library                                                           | Description             | Postfixes                                                |
|:------------------------------------------------------------------|:------------------------|:--------------------------------------------------------:|
| Netron                                                            | AI-Model Inspector      |                                                          |                                                             |

## AUDIO
| Library                                                           | Description             | Postfixes                                                |
|:------------------------------------------------------------------|:------------------------|:--------------------------------------------------------:|
| Wavesurfer                                                        | Waveform-Display        | wav,mp3,ogv,ogg (Browser-natives)                        |     
| Soundmanager2                                                     | Audio player            | wav,mp3,ogv,ogg (Browser-natives)                        |
| Jasmid                                                            | midi player             | midi,mid                                                 |
| Wavesurfer                                                        | Waveform-Display        | wav,mp3,ogv,ogg (Browser-natives)                        |


## Database
| Library                                                           | Description             | Postfixes                                                |
|:------------------------------------------------------------------|:------------------------|:--------------------------------------------------------:|
| SQLite (WASM)                                                     | SQLIte Database         | sqlite

## Download
| Library                                                           | Description             | Postfixes                                                |
|:------------------------------------------------------------------|:------------------------|:--------------------------------------------------------:|
| TorrentJS                                                         | Torrent Downloader      | .torrent

## Emulators
| Library                                                           | Description             | Postfixes                                                |
|:------------------------------------------------------------------|:------------------------|:--------------------------------------------------------:|
| DOSEMU                                                            |
| JSDosbox                                                          |
| GameBoy / Gameboy Color                                           | can play Gameboy-Roms   | .gb, .gbc
| GameBoy advanced                                                  | can play Gameboy-Roms   | .gba
| jsnes                                                             | can play NES-Roms       | .nes
| Playstation portable                                              | can play PSP games      | .psp
| V86                                                               | can run Win95,Linux     | .iso, .bin 


## Fonts
| Library    | Description             | Postfixes                                                |
|:-----------|:------------------------|:--------------------------------------------------------:|
| OpentypeJS |
| SVGFont    | | .svg
| TTFFont    | | .ttf

## Network packets
| Library    | Description             | Postfixes                                                |
|:-----------|:------------------------|:--------------------------------------------------------:|
| packetPeek | |
| webshark   | |

## Video
| Library    | Description             | Postfixes                                                |
|:-----------|:------------------------|:--------------------------------------------------------:|
| PopCorn    | |
| Projekktor | |
| VideoJS    | |


## Image
| I | Library                                                 | Description             | Postfixes                                                |
|:--|:--------------------------------------------------------|:------------------------|:--------------------------------------------------------:|
| X | IMMagick                                                | ImageMagick in the Browser (WASM)
| X | GraphicsMagick                                          | GraphicsMagick in the Browser (WASM)
| X | OCracy                                                  | AI Text detection
| X | OpenCV                                                  | Open Computer Vision
| X | PSDJS                                                   | Photoshop PSD-Viewer
| X | RawsonJS                                                | View Raw Camera Images
| X | Tesseract                                               | Text detection (WASM)    | Webbrowser-native images (jpg, png, bmp)
| X | ZXing                                                   | 2D and 3D Barcode reader | can read QR, DataMatrix from jpg, png, bmp, ...
| _ | SliceDrop                                               | Medical DICOM-Viewer     | Fibers (.trk,.tko), Volumes (.mgh,.mgz,.nrrd,.nii,.nii.gz,DICOM) 
| _ | ...                                                     | ...                      | Models(.obj,.vtk,.stl,FreeSurfer)

## Documents
| Library     | Description             | Postfixes                                                |
|:------------|:------------------------|:--------------------------------------------------------:|
| DJVU        | | .DJVU
| EPubJS      | | .Epub
| LatexMathML | | .???
| RTF         | | .RTF
| SheetJS     | | .xls, .odf
| ViewerJS    | | .pdf

## Others
| I | Library        | Description                             | Postfixes                                                |
|:--|:---------------|:----------------------------------------|:--------------------------------------------------------:|
| X | Cyberchef      | Can read and decode based on your needs | All Files (Binary)
| X | CryptoJS       | Can Create Hashes from all Files        | 
| X | PASM           | Assembly                                | .asm
| X | EXIFJS         | Parse Exif Informations                 | All Files (Binary)
| X | HexView        | View Binarys                            | All Files (Binary)
| X | ical           | Calendar files           
| X | icebuddha      | View Binarys                            | All Files (Binary)
| X | KNWL           |
| X | MathJax        | Math Expressions                       
| X | Mermaid        | 
| X | MSGReader      | Mail reader                             | .msg
| X | QMLWeb         |                                         |.qml
| X | Skulpt         | Imaging                                 | 
| X | WebGerber      | CNC-based Gerber files                  | .gbr, .drl












