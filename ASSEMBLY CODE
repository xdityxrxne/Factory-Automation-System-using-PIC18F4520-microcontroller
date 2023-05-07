# include <xc.h>
#define _XTAL_FREQ 20000000


// BEGIN CONFIG
#pragma config BOREN = ON 
#pragma config LVP = OFF
//END CONFIG


void main(void) {
    
    TRISD = 0;
    LATD = 0;
    TRISB = 0x00;
    PORTB = 0x00;
    
    
    while(1){
        LATD = 0X3F;
        __delay
        
        
        _ms(200);
        LATD = 0X06;
        __delay_ms(200);
        LATD = 0x5B;
        __delay_ms(200); 
        LATD=0X4F;
        __delay_ms(200);
        LATD=0X66;
        __delay_ms(200);
        LATD=0X6D;
        __delay_ms(200);
        LATD=0X7D;
        __delay_ms(200);
        LATD=0X07;
        __delay_ms(200);
        LATD=0X7F;
        __delay_ms(200);
        LATD=0X67;
        __delay_ms(200);
        
        PORTB = 0b00000001;
        __delay_ms(200);
        PORTB = 0b0010;
        __delay_ms(200);
        PORTB = 0b0100;
        __delay_ms(200);
        PORTB = 0b1000;
        __delay_ms(200);

        PORTB = 0b1000;
        __delay_ms(200);
        PORTB = 0b0100;
        __delay_ms(200);
        PORTB = 0b0010;
        __delay_ms(200);
        PORTB = 0b0001;
        __delay_ms(200);
    }
    return;
}
