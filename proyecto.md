
# TAREA DE PROCESADORES 

### CODIGO DE PROGRAMACION
```javascript
#pragma config FOSC = XT        // Oscillator Selection bits (XT oscillator: Crystal/resonator on RA6/OSC2/CLKOUT and RA7/OSC1/CLKIN)
#pragma config WDTE = OFF       // Watchdog Timer Enable bit (WDT disabled and can be enabled by SWDTEN bit of the WDTCON register)
#pragma config PWRTE = OFF      // Power-up Timer Enable bit (PWRT disabled)
#pragma config MCLRE = ON       // RE3/MCLR pin function select bit (RE3/MCLR pin function is MCLR)
#pragma config CP = OFF         // Code Protection bit (Program memory code protection is disabled)
#pragma config CPD = OFF        // Data Code Protection bit (Data memory code protection is disabled)
#pragma config BOREN = ON       // Brown Out Reset Selection bits (BOR enabled)
#pragma config IESO = ON        // Internal External Switchover bit (Internal/External Switchover mode is enabled)
#pragma config FCMEN = ON       // Fail-Safe Clock Monitor Enabled bit (Fail-Safe Clock Monitor is enabled)
#pragma config LVP = OFF        // Low Voltage Programming Enable bit (RB3 pin has digital I/O, HV on MCLR must be used for programming)

// CONFIG2
#pragma config BOR4V = BOR21V   // Brown-out Reset Selection bit (Brown-out Reset set to 4.0V)
#pragma config WRT = OFF        // Flash Program Memory Self Write Enable bits (Write protection off)

// #pragma config statements should precede project file includes.
// Use project enums instead of #define for ON and OFF.

#include <xc.h>

#define _XTAL_FREQ 8000000

void main(void) {
}


1
TRISB &= ~0x03;
    PORTB |= 0x01;
    ANSELH &= ~0xFF;
    while(1){
        PORTB = ~PORTB;
        __delay_ms(500);
    }
    return;

2
 TRISB &= ~0x07;
    PORTB |= 0x01;
    ANSELH &= ~0xFF;
    while(1){
        PORTB ^= 0x3;
        __delay_ms(2500);
        PORTB ^= 0x6;
        __delay_ms(5000);
        
        PORTB ^= 0x5;
        __delay_ms(5000);
        
    }
    return;

3
TRISB &= ~0x1F;
    PORTB |= 0x1F;
    ANSELH &= ~0xFF;
    while(1){
        int i=0;
        while(i<=4){
            PORTB = ~PORTB;
            __delay_ms(500);
            i++;
        }
        __delay_ms(300);
        while(i>=5 && i<=6){
            int n=0;
            int m=1;
            int r=1;
            while(n<10){
                while(n<5){
                    PORTB = PORTB+m; 
                    m=m*2;
                    __delay_ms(200);
                    n++;
                }
               PORTB = PORTB-r; 
               r=r*2;
               __delay_ms(200);
               n++;
            }
            i++;
        }
        while(i>=7 && i<=8){
            PORTB = PORTB +17;
            __delay_ms(200);
            PORTB = PORTB +10;
            __delay_ms(200);
            PORTB = PORTB +4;
            __delay_ms(200);
            PORTB = PORTB -4;
            __delay_ms(200);
            PORTB = PORTB -10;
            __delay_ms(200);
            PORTB = PORTB -17;
            __delay_ms(200);
            i++;
        }  
        __delay_ms(200);
        while(i>=9 && i<=10){
            PORTB = 1;
            __delay_ms(200);
            int f=0;
            int w=1;
            int e=8;
            while(f<9){              
                while(f<4){
                    PORTB = PORTB+w; 
                    w=w*2;
                    __delay_ms(200);
                    f++;
                }
                __delay_ms(200);
               PORTB = PORTB-e; 
               e=e/2;
               f++;
            }
            i++;
        }
        PORTB=0;
        PORTB = 21; 
        __delay_ms(200);
        while(i>=11 && i<=14){
            PORTB ^= 31;
            __delay_ms(200);
            i++;
        } 
        PORTB=31;
        __delay_ms(200);
        }
    return;
