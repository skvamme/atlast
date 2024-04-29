# atlast

ATLAST Forth. Use it standalone, or as a programmable Erlang Port. 

Create graphics in an ordinary terminal emulator.

The following terminal emulators can do sixel graphics: XTerm (360 or later), KDE Konsole (latest), MLterm (3.8.4), Contour (0.1.1), WezTerm (20210502), Mintty (3.5.0), RLogin (2.25.3), XQuartz, MacTerm and Reflection Desktop (16.2.0).

Documentation: https://elinux.org/Forth

Note to self: If used as an erlang port, use the forth word CR or FLUSH to flush stdout (buffered output) to send complete messages back to erlang.

Check before first time compile that all extras are out-commented, like this, in atlast.c

	#define FILEIO			      /* File I/O primitives */
	//#define TCP		      		/* TCP functions */
	//#define WEBSOCKETS          /* Websockets functions */
	//#define GERTBOARD		      /* Gertboard functions */
	//#define I2C					/* I2C functions */
	//#define WIRINGPI			  /* WiringPi functions */
	//#define TELLDUS          		/* Tellstick functions */
	#define MATH			      /* Math functions */

