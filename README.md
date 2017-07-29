Flisomaker is a open-source graphical ISO builder written in c++ with FLTK toolkit library.
Flisomaker is based on bkisofs - a library for reading, modifying and writing ISO images.

Requirements for Compiling :
C/C++ compiler and FLTK library(version 1.3 or better).

Compiling from Source :
Type make

If you want a static program, you can change ldflags from the Makefile.
For example:
LDFLAGS =`fltk-config --use-images --ldstaticflags`

Installing from Source :
Type make install
Or
Type make [DESTDIR] install
Where DESTDIR is your destination location.

Uninstalling from Source :
Type make uninstall

If your distribution is Tiny Core Linux , you can create extension :
Type Make tcz


Contact and bug reports :
nimdays[at]gmail.com
Or visit 
https://sourceforge.net/projects/flisomaker/
https://github.com/nimday/flisomaker/

Credits :
Andrew Smith for his excellent bkisofs library.
http://littlesvr.ca/
FLTK developers for their nice toolkit.
http://www.fltk.org/

License :
The source code is distributed under the GNU General Public Licence version 2.
See license.txt for full text.



Thank you for reading.
Terima kasih sudah membaca.
