The different data preprocessing techniques include: 

* blanks.sh     - all supplementary data is blank (" ")
* duplicate.sh  - all supplementary data is just a copy of the input
* encipher.sh -  supplementary input is encoded using a ROT-k cipher (same as origianl paper)
* random.sh - each character in supplementary input is replaced with a randomly chosen character
* reverse.sh - each word in the supplementary input is the input reversed ( "the cat" &rarr; "eht tac")
* shuffle.sh - each word's characters are randomly shuffled ( "the cat" &rarr; "eht act"

Each of the aforementioned scripts follow the format of **bash [file].sh -s [src] -t [target] -x src**, e.g. **encipher.sh -s de -t en -x src**
