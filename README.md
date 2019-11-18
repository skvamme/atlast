# atlast
ATLAST Forth. Use it standalone, or as a programmable Erlang Port. Documentation: https://elinux.org/Forth

Check before first time compile that all extras are out-commented, like this, in atlast.c

	#define FILEIO			      /* File I/O primitives */
	#define TCP		      		/* TCP functions */
	//#define WEBSOCKETS          /* Websockets functions */
	//#define GERTBOARD		      /* Gertboard functions */
	//#define I2C					/* I2C functions */
	//#define WIRINGPI			  /* WiringPi functions */
	//#define TELLDUS          		/* Tellstick functions */
	#define MATH			      /* Math functions */

