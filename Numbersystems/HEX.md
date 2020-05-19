# Hex
The base number of the hexadecimal system is 16,and its character set ranges from 0 to F. A is equivalent of a decimal 10 and F would be 15. The dollar sign($) indicates a hexadecimal number. The binary and hexadecimal systems are the most important numerical systems for assembly language programming.

The hexadecimal representation of a byte ranging from 0 to 256 always has two digits:$00 to $FF.A word ranges from $0000 to $FFFF and a longword from $00000000 to $FFFFFFFF.

Its quite easy to convert binary numbers into hexadecimal:simply split up the binary numbers into groups of four digits.Each of these groups of four digits then corresponds to one hexadecimal
digit.Heres an example:

             binary number  %110011101111
             split up       %1100 %1110 %1111
             result           $C    $E    $F
             thus:          %110011101111 = $CEF 


             %1100  8 + 4             =  12  =  C
             %1110  8 + 4 + 2         =  14  =  E
             %1111  8 + 4 + 2 + 1     =  15  =  F

