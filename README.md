# Decipher 75th Australian Signals Directorate (ASD) 50 cents Coin
Solving 75th Australian Signals Directorate 50 cents Coin
https://www.asd.gov.au/75th-anniversary/events/2022-09-01-75th-anniversary-commemorative-coin

# What We know from the Coin

## Heads
![Heads](/0002517_75th-anniversary-of-the-australian-signals-directorate-50c-uncirculated-coin-2022.jpeg)

### Braille in Coin
![BrailleCoin](/BrailleCoin.png)

### Logo in Queen Elizabeth
> JC

JC is initial for the coin designer Jody Clark 

## Tails
![Heads](/0002515_75th-anniversary-of-the-australian-signals-directorate-50c-uncirculated-coin-2022.jpeg)

### Outer Ring
#### Lower
> URMWXOZIRGBRM7DRWGSC5WVKGS

#### Bolded
> URWOIRDWCWG

#### Striped
> MXRBRSV

### Upper
> DVZIVZFWZXRLFHRMXLMXVKGZMWNVGRXFOLFHRMVCVXFGRLM

#### Bolded
> DRFHRMVKGNVRXFFHRVXGR

#### Striped
> ZLLZMGOMVL

## Inner Ring
> BGOAMVOEIATSIRLNGTTNEOGRERGXNTEAIFCECAIEOALEKFNR5LWEFCHDEEAEEE7NMDRXX5

#### Bolded
> GOAMVITSNGTNEGREREAICIEALFN5LFCHDEEE7NRX5

### Inner Symbol
![CoinSymbol](/CoinASD.png)

#### Cipher Text on Rigth
> E3B8287D4290F7233814D7A47A291DC0F71B2806D1A53B311CC4B97A0E1CC2B93B31068593332F10C6A3352F14D1B27A3514D6F7382F1AD0B0322955D1B83D3801CDB2287D05C0B82A311085A033291D85A3323855D6BC333119D6FB7A3C11C4A72E3C17CCBB33290C85B6343955CCBA3B3A1CCBB62E341ACBF72E3255CAA73F2F14D1B27A341B85A3323855D6BB333055C4A53F3C55C7B22E2A10C0B97A291DC0F73E3413C3BE392819D1F73B331185A3323855CCBA2A3206D6BE3831108B


## Solution
In Heads we got the on some of the characters with braille
Reorder the character based on the Braille we will get the result

![BrailleResult](/BrailleResult.png)


## Answer 1
> ATBASH

Search "Atbash" on Google you will found Atbash Cipher

Lets open Atbash Decoder https://www.dcode.fr/atbash-cipher

Time to decode all what we know from the coin

### Outer Ring Result
#### Lower
> FINDCLARITYIN7WIDTHX5DEPTH

#### Upper
> WEAREAUDACIOUSINCONCEPTANDMETICULOUSINEXECUTION

## Answer 2
> FIND CLARITY IN 7 WIDTH X 5 DEPTH

> WE ARE AUDACIOUS IN CONCEPT AND METICULOUS IN EXECUTION

Only this two we can decipher with Atbash decoder

### Inner Ring
From the clue we can create a matrix with 7 x 5 dimmension to a find the clarity
so lets make one on spreadsheets

![Matrix](/Matrix.png)

from the coloured text on the matrix we can see the result

## Answer 3
> BELONGING TO A GREAT TEAM STRIVING FOR EXCELLENCE WE MAKE A DIFFERENCE XOR HEX A5D75

From the next clue we need to xor the cipher with A5D75

Xor calculator https://xor.pw/

Cipher (382 characters) put it in the "I. Input: hexadecimal (base 16)"

> E3B8287D4290F7233814D7A47A291DC0F71B2806D1A53B311CC4B97A0E1CC2B93B31068593332F10C6A3352F14D1B27A3514D6F7382F1AD0B0322955D1B83D3801CDB2287D05C0B82A311085A033291D85A3323855D6BC333119D6FB7A3C11C4A72E3C17CCBB33290C85B6343955CCBA3B3A1CCBB62E341ACBF72E3255CAA73F2F14D1B27A341B85A3323855D6BB333055C4A53F3C55C7B22E2A10C0B97A291DC0F73E3413C3BE392819D1F73B331185A3323855CCBA2A3206D6BE3831108B

XOR Hex A5D75 put it in the "I. Input: hexadecimal (base 16)" make sure we have the same character wth the cipher text (382 characters)

> A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5D75A5

Finally, you will get the final text
![FinalText](/FinalText.png)

## Answer 4
> For 75 years the Australian Signals Directorate has brought together people with the skills, adaptability and imagination to operate in the slim area between the difficult and the impossible.

## Bonus
### Symbol in Coin
From the official website the meaning of the symbol is ASD
![ASDWeb](/ASDWeb.png)


### Inner Coin
The text in inner coin only have nornal and bold text
its a clue that it can be transtaled into 1 and 0 with 7 digit
so it comes up with binary ASCII code
based on the table from https://www.dcode.fr/ascii-code and my previous spreadsheets

we can see the text result
![ASCII](/CodeASCII.png)

### Bonus Text
> ASDCbr2022


### Outer Coin
The text on outer layer have 3 type characters normal, bold and stripe
from this we can guess its a morse code because it have dot, dash and space

> Bold = dot
> Normal = dash
> Stripe = space

from the outer text
> **D**VZIV*Z*FWZX**R***L***FHRM**X*L*MX**VKG***ZM*W**NV***G***RXF***O*L**FHR***M***V**C*V***X**F**GR***L*M**.UR***M***W***X***O**Z**I***R*G*B***R**M7**D***R***W**G*S***C**5**W***V*K**G**S



