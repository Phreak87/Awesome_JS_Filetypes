# Awesome_JS_Filetypes

Awesome list of open source (not commercial!) Javascript Web-Frontend Librarys for handling different filetypes directly in the Browser.
This means that the files should never leave the own webserver.
Please extend this list if you miss something.

## Browser-native handlings (you don´t need Javascript, no Browser plugins!)
| Library     | Description                | Postfixes                                                |
|:------------|:---------------------------|:--------------------------------------------------------:|
| Chromium 85 | Video                      | ogv, mp4, webm
| Chromium 85 | Audio                      | mp3, mp4, wav (pcm), ogg, aac, webm, flac
| Chromium 85 | Images                     | png, ico, bmp, jpg, gif, webm
| Chromium 85 | Documents                  | pdf

## Compression
| Library                                                           | Description             | Postfixes                                                |
|:------------------------------------------------------------------|:------------------------|:--------------------------------------------------------:|
| [ArchiveJS](https://github.com/nika-begiashvili/libarchivejs)     | WASM-Port of [libarchive](https://github.com/libarchive/libarchive) | Tested: Zip, 7Zip, Rar (V4,V5), TAR
| RarJS         | RarJS                   | Rar (V4,V5)                                              |                                                             |
| ZipJS         | ZipJS                   | Zip                                                      |                                                             |
| TarJS         | TarJS                   | Tar                                                      |                                                             |

## 3D
| I | Library                                                 | Description             | Postfixes                                                |
|:--|:--------------------------------------------------------|:------------------------|:--------------------------------------------------------:|
| X | [ThreeJS](https://threejs.org/)                         | 3D-Library              | stl, obj, gltf, assimp, babylon, collada, awd, svg, vrml, vtk, tga, pdb, ply, ,  ...?
| X | GCodeReader                                             | 3D-Print Library        | g, gco, gcode (and all GCode types)                      
| X | Hangar                                                  | 3D-View of Hangar Files | ac3d (.ac)
| X | [NGLViewer](https://github.com/nglviewer/ngl)           | Atoms, molecules        | .pdb,.cif,.cif.gz, mmtf,gro,mtl,ply,kin,pqr,dx.gz,dxbin,ccp4, sdf,obj,cub,map.gz, ctm,cns,xml,brix,dsn6,ctm,cns,xml,brix,dsn6prmtop,mol2,dcd,psf,cube,cube.gt,ent,pdbqt, mrc,dcd,dcd.gz
| X | OpenJSCad                                               | CAD-Modelling           | jscad, openscad                                          
| X | SceneJS                                                 | 
| X | ThreeDXF                                                | DXF
| X | WebXF                                                   | 
| X | [WEXBIM](https://github.com/xBimTeam/XbimWebUI)         | Wexbim building information | IFC, ifcZIP, ifcXML
| X | X3Dom                                                   | 
| _ | PlasIO                                                  | PointCloud

## AI
| Library                                                           | Description             | Postfixes                                                |
|:------------------------------------------------------------------|:------------------------|:--------------------------------------------------------:|
| Netron                                                            | AI-Model Inspector      | Netron supports ONNX (.onnx, .pb, .pbtxt), Keras (.h5, .keras), Core ML (.mlmodel), Caffe (.caffemodel, .prototxt), Caffe2 (predict_net.pb), Darknet (.cfg), MXNet (.model, -symbol.json), Barracuda (.nn), ncnn (.param), Tengine (.tmfile), TNN (.tnnproto), UFF (.uff) and TensorFlow Lite (.tflite).Netron has experimental support for TorchScript (.pt, .pth), PyTorch (.pt, .pth), Torch (.t7), Arm NN (.armnn), BigDL (.bigdl, .model), Chainer (.npz, .h5), CNTK (.model, .cntk), Deeplearning4j (.zip), MediaPipe (.pbtxt), ML.NET (.zip), MNN (.mnn), PaddlePaddle (.zip, __model__), OpenVINO (.xml), scikit-learn (.pkl), TensorFlow.js (model.json, .pb) and TensorFlow (.pb, .meta, .pbtxt, .ckpt, .index).                                                         |

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
| SQLite (WASM)                                                     | SQLIte Database         | .sqlite, (or each sqlite postfix you use)

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
| OpentypeJS | | .ttf, ...
| SVGFont    | | .svg
| TTFFont    | | .ttf

## Network packets
| Library    | Description             | Postfixes                                                |
|:-----------|:------------------------|:--------------------------------------------------------:|
| packetPeek | |
| webshark   | |

## Video
| I | Library    | Description             | Postfixes                                                |
|:--|:-----------|:------------------------|:--------------------------------------------------------:|
| X | PopCorn    |                         | Browser-native Videos (e.g. MP4,OGV,WEBM)
| X | Projekktor |                         | Browser-native Videos (e.g. MP4,OGV,WEBM)
| X | VideoJS    |                         | Browser-native Videos (e.g. MP4,OGV,WEBM)
| _ | FFMPEGJS   | different WASM-Ports    | Audio / Video files based on Port

## Image
| I | Library                                                 | Description             | Postfixes                                                |
|:--|:--------------------------------------------------------|:------------------------|:--------------------------------------------------------:|
| X | [IMMagick](https://github.com/KnicKnic/WASM-ImageMagick)| ImageMagick in the Browser (WASM) | jpg,png,psd,tiff,xcf,gif,bmp,tga,miff,ico,dcm,xpm,pcx,fits,ppm,pgm,pfm,mng,hdr,dds,otb,txt, psb, (list maybe incomplete. check other formats)
| X | GraphicsMagick                                          | GraphicsMagick in the Browser (WASM)
| X | OCracy                                                  | AI Text detection
| X | OpenCV                                                  | Open Computer Vision
| X | PSDJS                                                   | Photoshop PSD-Viewer
| X | RawsonJS                                                | View Raw Camera Images   | jpeg, .jpg, .jpe, .png, .3fr, .ari, .arw, .bay, .crw, .cr2, .cap, .dcs, .dcr, .dng, .drf, .eip, .erf, .fff, .iiq, .k25, .kdc, .mef, .mos, .mrw, .nef, .nrw, .obm, .orf, .pef, .ptx, .pxn, .r3d, .raf, .raw, .rwl, .rw2, .rwz, .sr2, .srf, .srw, .x3f
| X | Tesseract                                               | Text detection (WASM)    | Webbrowser-native images (jpg, png, bmp)
| X | ZXing                                                   | 2D and 3D Barcode reader | can read QR, DataMatrix from jpg, png, bmp, ...
| _ | [openseadragon](https://openseadragon.github.io)        | HD-Image Viewer          | iiif, dzi, osm, tms
| _ | [Med3Ved](https://med3web.opensource.epam.com/)         | Dicom                    | ktx,dcm,mii,hdr,h,img
| _ | SliceDrop                                               | Medical DICOM-Viewer     | Fibers (.trk,.tko), Volumes (.mgh,.mgz,.nrrd,.nii,.nii.gz,DICOM) 
| _ | ...                                                     | ...                      | Models(.obj,.vtk,.stl) and Freesurfer-Models (gca, bshort, bfloat, COR, surface, curv, w, annot, patch, gcs, dat, xfm, m3d and lta)

## Documents
| I | Library                                                 | Description             | Postfixes                                                |
|:--|:--------------------------------------------------------|:------------------------|:--------------------------------------------------------:|
| X | DJVU                                                    | Ebooks                  | .djvu
| X | EPubJS                                                  | Ebooks                  | .epub
| X | LatexMathML                                             |                         | .???
| X | RTF                                                     | Rich-text format        | .RTF
| X | SheetJS                                                 |                         | .xls, .odf
| X | ViewerJS                                                |                         | .pdf
| X | [RAWGraphs](https://rawgraphs.io/)                      | Visualize text data     | TSV, CSV, DSV, JSON and Excel files (.xls, .xlsx)
| X | [VizJs](https://github.com/mdaines/viz.js)              | Graphwiz Dot Viewer     | .dot                                                     

## Others
| I | Library                                                 | Description             | Postfixes                                                |
|:--|:--------------------------------------------------------|:------------------------|:--------------------------------------------------------:|
| X | Cyberchef                                               | Can read and decode based on your needs | All Files (Binary)
| X | CryptoJS                                                | Can Create Hashes from all Files        | 
| X | PASM                                                    | Assembly                                | .asm
| X | EXIFJS                                                  | Parse Exif Informations                 | All Files (Binary)
| X | HexView                                                 | View Binarys                            | All Files (Binary)
| X | ical                                                    | Calendar files           
| X | icebuddha                                               | View Binarys                            | All Files (Binary)
| X | KNWL                                                    | Reads address, dates, ... from text     | All Text-based Files.
| X | MathJax                                                 | Math Expressions                       
| X | Mermaid                                                 | 
| X | MSGReader                                               | Mail reader                             | .msg
| X | QMLWeb                                                  |                                         |.qml
| X | Skulpt                                                  | Imaging                                 | 
| X | [WebGerber](https://github.com/attie/webgerber)         | CNC-based Gerber files                  | drl, drd, txt, .out, gml, outline, gbl, sol, gbs, sts, gbp, crs, gbo, pls, gtl, cmp, gts, stc,gtp, crc, gto, plc

## Sort
| I | Library        | Description                             | Postfixes                                                |
|:--|:---------------|:----------------------------------------|:--------------------------------------------------------:|










