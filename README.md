# Opgave-8
FrankenText

This code is **supposed** to randomly generate a sentence from randomly picked out tokens from the book Frankenstein.
I could not get it to work.


1. I remove the non-printable chars and replace them with a space
2. We find the delimiters (. ! ? \n\r)
3. connect each token to the next
4. Print a randomly generated sentence (from the tokens/book) based off of the delimiters

I could never test my code with #embed, nor could I run my code with:
  clang --target=x86_64-w64-windows-gnu -fuse-ld=lld -Wall -Wextra -g .\opgave-8\Frankentext.c -o .\opgave-8\Frankentext.exe 
  .\opgave-8\Frankentext.exe
so I could never test my code to see what I was missing
