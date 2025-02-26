# Enigma codebook generator

## About codebooks 

An Enigma codebook was a secret document used by the German military during World War II to set up the Enigma machine for encrypted communication. It contained daily settings for the machine. 

Each day, operators would configure their Enigma machine according to the codebook, ensuring secure communication (ref: https://www.ciphermachinesandcryptology.com/en/enigmaproc.htm).

## The codebook generator

This repo contains a Single Page Application (literally, a single index.html file) used to randomly generate a codebook for an entire month.

Other than within this repo, the page is publicly available here https://denismaggior8.github.io/enigma-codebook-generator. 

By opening that URL in a browser, you get something similar to:

```
+----+---------------------+----------------+-------------------------------+---------------------+
|Day |       Rotors        |    Ring Set    |     Plugboard Connections     |   Indicator groups  |
+----+---------------------+----------------+-------------------------------+---------------------+
| 31 | IV   II   III  I    | 10  13  05  11 | IZ YQ TR BA JK CS GL VD MU WN |   QYZ ZSB BTP PRX   | 
+----+---------------------+----------------+-------------------------------+---------------------+
| 30 | II   I    III  IV   | 26  13  03  23 | VY FZ GH EB DR AC ON PJ LK SI |   DCG GBA AFE EHL   | 
+----+---------------------+----------------+-------------------------------+---------------------+
| 29 | III  V    I    VI   | 15  01  23  19 | ED FI JL GH MC AP KN OB RS TQ |   ACB BDF FEH HGJ   | 
+----+---------------------+----------------+-------------------------------+---------------------+
| 28 | I    II   III  IV   | 26  03  09  22 | ED AH BC FG LI JK NM OP QR ST |   FKY YJQ QEL LIS   | 
+----+---------------------+----------------+-------------------------------+---------------------+
| 27 | I    II   VI   III  | 08  21  24  04 | JN FM CG QE AV DS PR IO BX HL |   DSY YCT TRB BQA   | 
...................................................................................................
+----+---------------------+----------------+-------------------------------+---------------------+
| 01 | II   I    III  IV   | 14  13  15  20 | BC DA FE GH MI KN PJ OL YZ QS |   WPV VIA ACU UDB   | 
+----+---------------------+----------------+-------------------------------+---------------------+
```

> [!NOTE]  
> Each time you refresh the page you get a new codebook with no-way to recover the previous one (as the app does not maintain a state of previous generations)... unless you saved it locally or printed it.

## Supporting

Found it useful/funny/educational? Please consider to [![Buy Me a Coffee](https://img.shields.io/badge/buy_me_a_coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/denismaggior8)