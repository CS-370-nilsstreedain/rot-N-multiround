# Decode Rot-N (Multi-round)
Let's break rot-N encryption multiple times.

Please proceed to the `rot-N-multiround` folder. You will find the following files after the ls command:
```
flag quotes.txt rot-N-multiround template.py
```

Please fix the `template.py` file. This file runs `rot-N-multiround` file, which iteratively reads one of the quotes from the `quotes.txt, encrypts it by shifting the text by N, and returns the ciphertext. You are required to edit the TODO parts to reverse-engineer the plaintext from the ciphertext. Once you're successful over the entire rounds, you will get the flag
