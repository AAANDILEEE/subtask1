# Morse Code Translator in C++

## Overview

This is a C++ program that allows users to translate short English messages into Morse code using ASCII characters for dots and dashes.

## Historical Context

Morse code was developed in the 1830s by Samuel Morse for long-distance telegraph communication. It uses combinations of dots (`.`) and dashes (`-`) to represent each letter and number. Originally used for telegraphs, it's still used in aviation and emergency signaling.

## How the System Works

Each English letter or number is mapped to a unique Morse code symbol. For example:
- A = .-
- B = -...
- C = -.-.
- 1 = .----
- 2 = ..---
- Space = /

The program converts every character of a user-input message to its Morse code equivalent using a dictionary in C++.

## Example

**Input**: `HELLO WORLD`  
**Output**: `.... . .-.. .-.. --- / .-- --- .-. .-.. -..`

## How to Run

```bash
g++ morse_translator.cpp -o morse_translator
./morse_translator
```

## GitHub Practices

This project includes:
- Version control using GitHub.
- At least 5 commits to show the coding process.
- This README for documentation and context.

## References

- [Wikipedia - Morse code](https://en.wikipedia.org/wiki/Morse_code)
- [International Morse Code Chart](https://morsecode.world/international/morse.html)
