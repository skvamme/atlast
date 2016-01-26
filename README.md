# atlast
ATLAST Forth based programmable Erlang Port

Check before first time compile that all extras are out-commented, like this, in atlast.c

#define FILEIO			      /* File I/O primitives */
//#define TCP		      		/* TCP functions */
//#define WEBSOCKETS          /* Websockets functions */
//#define GERTBOARD		      /* Gertboard functions */
//#define I2C					/* I2C functions */
//#define WIRINGPI			  /* WiringPi functions */
//#define TELLDUS          		/* Tellstick functions */
#define MATH			      /* Math functions */
