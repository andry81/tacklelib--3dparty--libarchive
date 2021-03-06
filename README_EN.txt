* README_EN.txt
* 2020.02.10
* tacklelib--3dparty--libarchive

1. DESCRIPTION
2. LICENSE
3. REPOSITORIES
4. INSTALLATION
5. AUTHOR

-------------------------------------------------------------------------------
1. DESCRIPTION
-------------------------------------------------------------------------------
libarchive patched sources fork from:
https://github.com/libarchive/libarchive

From authors:

  Welcome to libarchive!
  The libarchive project develops a portable, efficient C library that can read
  and write streaming archives in a variety of formats. It also includes
  implementations of the common tar, cpio, and zcat command-line tools that use
  the libarchive library.

  Supported Formats
  Currently, the library automatically detects and reads the following fomats:

  * Old V7 tar archives
  * POSIX ustar
  * GNU tar format (including GNU long filenames, long link names, and sparse files)
  * Solaris 9 extended tar format (including ACLs)
  * POSIX pax interchange format
  * POSIX octet-oriented cpio
  * SVR4 ASCII cpio
  * Binary cpio (big-endian or little-endian)
  * ISO9660 CD-ROM images (with optional Rockridge or Joliet extensions)
  * ZIP archives (with uncompressed or "deflate" compressed entries, including support for encrypted Zip archives)
  * ZIPX archives (with support for bzip2, ppmd8, lzma and xz compressed entries)
  * GNU and BSD 'ar' archives
  * 'mtree' format
  * 7-Zip archives
  * Microsoft CAB format
  * LHA and LZH archives
  * RAR and RAR 5.0 archives (with some limitations due to RAR's proprietary status)
  * XAR archives

The original library patched to add these files:

  * changelog file
  * readme file

-------------------------------------------------------------------------------
2. LICENSE
-------------------------------------------------------------------------------
The libarchive distribution as a whole is Copyright by Tim Kientzle.
(see included text file "COPYING" or
`View License` section on the site https://github.com/libarchive/libarchive )

-------------------------------------------------------------------------------
3. REPOSITORIES
-------------------------------------------------------------------------------
Primary:
  * https://sf.net/p/tacklelib/3dparty--libarchive/HEAD/tree/trunk
    https://svn.code.sf.net/p/tacklelib/3dparty--libarchive/trunk
First mirror:
  * https://github.com/andry81/tacklelib--3dparty--libarchive/tree/trunk
    https://github.com/andry81/tacklelib--3dparty--libarchive.git
Second mirror:
  * https://bitbucket.org/andry81/tacklelib-3dparty-libarchive/src/trunk
    https://bitbucket.org/andry81/tacklelib-3dparty-libarchive.git

-------------------------------------------------------------------------------
4. INSTALLATION
-------------------------------------------------------------------------------
N/A

-------------------------------------------------------------------------------
5. AUTHOR
-------------------------------------------------------------------------------
Andrey Dibrov (andry at inbox dot ru)
