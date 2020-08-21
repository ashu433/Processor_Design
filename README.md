# Scaled Down Version of 8085 Microprocessor
Scaled Down Version of 8085 Microprocessor 
The following design contain the hardware flow chart implementation of the 8085 Microprocessor which can implement the function given in the Assignment 1 of the Processor design . In addition to that level 2 flow chart have been provided for each and every instruction with data path orgination and the controller orgination . It also contain the complete control word along with decode logic for instructions . 

Instructions set used are :
1. MOV Rg, Rg
2. MOV Rg, M
3. MOV M, Rg
4. MVI Rg, D08
5. LXI Rp/SP, D16
6. LDA D16
7. STA D16
8. ADC Rg
9. ACI D08
10. SBB Rg
11. ANA Rg
12. CMP Rg
13. JMP D16
14. JC D16
15. CALL D16
16. CZ D16
17. RET
18. RZ


Notations:
Rg – Register (A, B, . . . )
Rp – Register Pair (BC, DE, . . . )
SP – Stack pointer
D08: 8 bit data
D16: 16-bit data/address
M – Memory
