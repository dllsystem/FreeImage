What is FreeImage?

FreeImage is an Open Source library project for developers who would like to support popular graphics image formats like PNG, BMP, JPEG, TIFF and others as needed by today's multimedia applications. FreeImage is easy to use, fast, multithreading safe, compatible with all 32-bit or 64-bit versions of Windows, and cross-platform (works both with Linux and Mac OS X).
 
Thanks to it's ANSI C interface, FreeImage is usable in many languages including C, C++, VB, C#, Delphi, Java and also in common scripting languages such as Perl, Python, PHP, TCL or Ruby.
 
The library comes in two versions: a binary DLL distribution that can be linked against any WIN32 C/C++ compiler and a source distribution. Workspace files for Microsoft VS.Net 2003, VS.Net 2005 and VS.Net 2008 are provided, as well as makefiles for Linux, MinGW and Mac OS X.
 
From january 2000 to july 2002, FreeImage was designed and mainly developed by Floris van den Berg. FreeImage is now maintained by Hervé Drolon.


<h4>FreeImage uses:</h4>

LibJPEG 9a
LibPNG 1.6.12
LibTIFF 4.0.3 (CVS patch 2013-11-30)
LibRaw 0.16.0
OpenJPEG 2.1.0 (SVN patch 2748)
ZLib 1.2.8
LibWebP 0.4.0 (GIT patch 2014-06-26)
LibJXR 1.1 (GIT patch 2014-01-31)

<h4>Supported formats:</h4>

RAW camera files [reading] (CRW/CR2, NEF, RAF, DNG, MOS, KDC, DCR, etc)
PSD Photoshop files [reading]
WebP files [reading, writing]
JPEG-XR files [reading, writing] (jxr,wdp,hdp)
HDR files [reading, writing]
BMP files [reading, writing]
Dr. Halo CUT files [reading] *
DDS files [reading]
EXR files [reading, writing]
Raw Fax G3 files [reading]
GIF files [reading, writing]
ICO files [reading, writing]
IFF files [reading]
JBIG files [reading, writing] **
JNG files [reading, writing]
JPEG/JIF files [reading, writing]
JPEG-2000 File Format [reading, writing]
JPEG-2000 codestream [reading, writing]
KOALA files [reading]
Kodak PhotoCD files [reading]
MNG files [reading]
PCX files [reading]
PBM/PGM/PPM files [reading, writing]
PFM files [reading, writing]
PNG files [reading, writing]
PICT Macintosh files [reading]
Sun RAS files [reading]
SGI files [reading]
TARGA files [reading, writing]
TIFF files [reading, writing]
WBMP files [reading, writing]
XBM files [reading]
XPM files [reading, writing]

<h4>Features:</h4>
 
Ease of use
The library has been designed to be extremely simple in use. Our motto is: make difficult things simple instead of simple things difficult.
 
Not limited to the local PC
The unique FreeImageIO structure makes it possible to load your images from virtually anywhere. Possibilities include standalone files, memory, database and the Internet, all this without recompiling the library!
 
Plugin driven
The internal engine is made completely modular using a clever plugin system. Easily write new plugins and store them in DLL files or embed the plugins directly into your application!
 
Color conversion
FreeImage provides many functions to convert a bitmap from one bitdepth to another. The library supports 1-, 4-, 8-, 16, 24- and 32-bit standard images, as well as integer, real and complex images.
 
Common image manipulations
Provides basic image manipulation routines such as rotation, resizing, flipping or color adjustments, as well as lossless JPEG transformations.
 
Directly access bitmap bits and palette
Functions are provided which allow you to directly access the bitmap palette (if available) and bitmap bits.
 
Metadata support
Parse common metadata models attached to your bitmap. FreeImage supports Comments, Exif (including GPS and maker notes), IPTC, Adobe XMP, GeoTIFF and GIF animation metadata models.
 
Support for High Dynamic Range images
FreeImage supports RGB float images as well a 48-bit HDR images and provides tone mapping operators to convert these images to 24-bit LDR images.
 
Support for RAW files from digital photo cameras
FreeImage can load RAW files from digital photo cameras (CRW/CR2, NEF, RAF, DNG, MOS, KDC, DCR, etc), virtually all RAW formats are supported.
 
Full source code is provided.
Written in portable C++, the library should compile on all 32-bit or 64-bit Windows, Linux and Mac OSX systems.
FreeImage also includes comprehensive documentation to help you work with and learn about the code provided.
 
Open Source Dual-License
You can choose the license that has the most advantages for you: Use the liberal FreeImage Public License to use FreeImage commercially or the GNU General Public License to use FreeImage into your open source project.
 
Easily integrates into DirectX and OpenGL.
Only a minimum of programming is necessary to store a FreeImage bitmap into a DirectDraw surface or to use FreeImage to load your Direct3D/OpenGL textures.
 
Provides test programs to "show-off" the library, compilable and startable on Windows 95, 98, NT, 2000 or on Linux.
