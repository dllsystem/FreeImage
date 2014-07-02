<h4>What is FreeImage?</h4>

FreeImage is an Open Source library project for developers who would like to support popular graphics image formats like PNG, BMP, JPEG, TIFF and others as needed by today's multimedia applications. FreeImage is easy to use, fast, multithreading safe, compatible with all 32-bit or 64-bit versions of Windows, and cross-platform (works both with Linux and Mac OS X).
 
Thanks to it's ANSI C interface, FreeImage is usable in many languages including C, C++, VB, C#, Delphi, Java and also in common scripting languages such as Perl, Python, PHP, TCL or Ruby.
 
The library comes in two versions: a binary DLL distribution that can be linked against any WIN32 C/C++ compiler and a source distribution. Workspace files for Microsoft VS.Net 2003, VS.Net 2005 and VS.Net 2008 are provided, as well as makefiles for Linux, MinGW and Mac OS X.
 
From january 2000 to july 2002, FreeImage was designed and mainly developed by Floris van den Berg. FreeImage is now maintained by Hervé Drolon.


<h4>FreeImage uses:</h4>

LibJPEG 9a<br>
LibPNG 1.6.12<br>
LibTIFF 4.0.3 (CVS patch 2013-11-30)<br>
LibRaw 0.16.0<br>
OpenJPEG 2.1.0 (SVN patch 2748)<br>
ZLib 1.2.8<br>
LibWebP 0.4.0 (GIT patch 2014-06-26)<br>
LibJXR 1.1 (GIT patch 2014-01-31)<br>

<h4>Supported formats:</h4>

RAW camera files [reading] (CRW/CR2, NEF, RAF, DNG, MOS, KDC, DCR, etc)<br>
PSD Photoshop files [reading]<br>
WebP files [reading, writing]<br>
JPEG-XR files [reading, writing] (jxr,wdp,hdp)<br>
HDR files [reading, writing]<br>
BMP files [reading, writing]<br>
Dr. Halo CUT files [reading] *<br>
DDS files [reading]<br>
EXR files [reading, writing]<br>
Raw Fax G3 files [reading]<br>
GIF files [reading, writing]<br>
ICO files [reading, writing]<br>
IFF files [reading]<br>
JBIG files [reading, writing] **<br>
JNG files [reading, writing]<br>
JPEG/JIF files [reading, writing]<br>
JPEG-2000 File Format [reading, writing]<br>
JPEG-2000 codestream [reading, writing]<br>
KOALA files [reading]<br>
Kodak PhotoCD files [reading]<br>
MNG files [reading]<br>
PCX files [reading]<br>
PBM/PGM/PPM files [reading, writing]<br>
PFM files [reading, writing]<br>
PNG files [reading, writing]<br>
PICT Macintosh files [reading]<br>
Sun RAS files [reading]<br>
SGI files [reading]<br>
TARGA files [reading, writing]<br>
TIFF files [reading, writing]<br>
WBMP files [reading, writing]<br>
XBM files [reading]<br>
XPM files [reading, writing]<br>

<h4>Features:</h4>

<b>Ease of use</b><br>
The library has been designed to be extremely simple in use. Our motto is: make difficult things simple instead of simple things difficult.
 
<b>Not limited to the local PC</b><br>
The unique FreeImageIO structure makes it possible to load your images from virtually anywhere. Possibilities include standalone files, memory, database and the Internet, all this without recompiling the library!
 
<b>Plugin driven</b><br>
The internal engine is made completely modular using a clever plugin system. Easily write new plugins and store them in DLL files or embed the plugins directly into your application!
 
<b>Color conversion</b><br>
FreeImage provides many functions to convert a bitmap from one bitdepth to another. The library supports 1-, 4-, 8-, 16, 24- and 32-bit standard images, as well as integer, real and complex images.
 
<b>Common image manipulations</b></br>
Provides basic image manipulation routines such as rotation, resizing, flipping or color adjustments, as well as lossless JPEG transformations.
 
<b>Directly access bitmap bits and palette</b><br>
Functions are provided which allow you to directly access the bitmap palette (if available) and bitmap bits.
 
<b>Metadata support</b><br>
Parse common metadata models attached to your bitmap. FreeImage supports Comments, Exif (including GPS and maker notes), IPTC, Adobe XMP, GeoTIFF and GIF animation metadata models.
 
<b>Support for High Dynamic Range images</b><br>
FreeImage supports RGB float images as well a 48-bit HDR images and provides tone mapping operators to convert these images to 24-bit LDR images.
 
<b>Support for RAW files from digital photo cameras</b><br>
FreeImage can load RAW files from digital photo cameras (CRW/CR2, NEF, RAF, DNG, MOS, KDC, DCR, etc), virtually all RAW formats are supported.
 
<b>Full source code is provided.</b><br>
Written in portable C++, the library should compile on all 32-bit or 64-bit Windows, Linux and Mac OSX systems.
FreeImage also includes comprehensive documentation to help you work with and learn about the code provided.
 
<b>Open Source Dual-License</b><br>
You can choose the license that has the most advantages for you: Use the liberal FreeImage Public License to use FreeImage commercially or the GNU General Public License to use FreeImage into your open source project.
 
<b>Easily integrates into DirectX and OpenGL.</b><br>
Only a minimum of programming is necessary to store a FreeImage bitmap into a DirectDraw surface or to use FreeImage to load your Direct3D/OpenGL textures.
 
Provides test programs to "show-off" the library, compilable and startable on Windows 95, 98, NT, 2000 or on Linux.
