# Calculate eGFR using Excel.

## formula



Male

eGFR = 194 * Cr^-1.094 * Age^-0.287



Female

eGFR = 194 * Cr^-1.094 * Age^-0.287 * 0.739



Excel formula

=194*POWER(B3,-1.094)*POWER(A3,-0.287)*IF(C3=2,0.739,1)

B column : Cre

A Column: Age

C Column: Sex (1=male, 2=female)

