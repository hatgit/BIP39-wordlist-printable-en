### BIP39-wordlist-printable-en

A handy compact printable BIP39 mnemonic wordlist containing index values in base 10 and 11-bit binary base 2 format, based off the BIP-39 english word list found at: https://github.com/bitcoin/bips/blob/master/bip-0039/english.txt

NOTE: While valid BIP39 mnemonics recovery phrases are derived from this list programatically, that specific process involves generating cryptographically secure random numbers (initial entorpy) as well as the use of converting binary numbers to bytearrays, and applying a cryptographic hash function and thereore must rely on software code (you cannot create a valid mnemonic manually without software). That is, ***this word list cannot be used - on its own - to generate valid BIP39 mnemonics*** because the last word must be derived from a checksum that involves a hash function to determine the last groups of bits that must be concatenated to the end the initial string of random bits. Instead, this word list is reference for converting an existing valid mnemonic into its corresponding index values and their respective 11-bit binary numbers which can be used as an additional means of backup/recovery to reconstruct the mnemonic phrase.

In addition to copying the underlying text, the below images can also be printed direclty (although they are put here for descriptive purposes).

#Page 1: 

<img width="965" alt="bip39_printable_page_1" src="https://user-images.githubusercontent.com/5213035/46573154-a8902b80-c999-11e8-8847-c8490ce89d18.png">

#Page 2:

<img width="969" alt="bip39_printable_page_2" src="https://user-images.githubusercontent.com/5213035/46573155-aa59ef00-c999-11e8-8d81-bf598a243241.png">


