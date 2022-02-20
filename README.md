# atlast

UPDATE: Trying to implement mouse support, not perfect at the moment. Start atlast with ./atlast -i7-seg.atl and then type MOUSE
to get X and Y plus mouseup/down info for each mouse button. Redefine the word KLICK for other behaviour. To turn it off type RESET

ATLAST Forth. Use it standalone, or as a programmable Erlang Port. Documentation: https://elinux.org/Forth

Note to self: If used as an erlang port, use the forth word CR or FLUSH to flush stdout (buffered output) to send complete messages back to erlang.

Check before first time compile that all extras are out-commented, like this, in atlast.c

	#define FILEIO			      /* File I/O primitives */
	#define TCP		      		/* TCP functions */
	//#define WEBSOCKETS          /* Websockets functions */
	//#define GERTBOARD		      /* Gertboard functions */
	//#define I2C					/* I2C functions */
	//#define WIRINGPI			  /* WiringPi functions */
	//#define TELLDUS          		/* Tellstick functions */
	#define MATH			      /* Math functions */

