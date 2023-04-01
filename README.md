# Binary-to-Decimal-Conversion-Mobile-App-using-JAVA-SDK
This is Binary to Decimal number conversion App using Java SDK
            int binary = 1010;
            int decimal=0;int i=0;
            while (binary!=0){
                int reminder = binary%10;
                binary /=10;
                decimal += reminder*Math.pow(2,i);
                ++i;
            }
 For this purpose Magnitude formula is best to convert Binary to decimal
 First find the position of the each digits 
 Binary Number = 1010
 1          0            1             0          Each Digit of the binary number
 3          2            1             0          Positions of the each binary number digit
 2^3        2^2          2^2           2^0        Weight of each digit actually base^position
 1x2^3  +   0x2^2   +    1x2^2   +     0x2^0      Magnitude formula is sum of (digitxweight)
 **********************************************************
                          Result
 **********************************************************
 Decimal = 10 
 
