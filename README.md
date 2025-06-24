# Location Decryption Script
String Problem
Description
In a certain encrypted message which has information about the location(area, city), the characters are jumbled such that first character of the first word is followed by the first character of the second word, then it is followed by second character of the first word and so on

In other words, let’s say the location is bandra,mumbai
The encrypted message says ‘bmaunmdbraai’.

Sample Input:
bmaunmdbraai

Sample Output:
bandra,mumbai

Let’s say the size or length of the two words wouldn’t match then the smaller word is appended with # and then encrypted in the above format.

With this in mind write a code to identify the right location and print it as place,city.
---

## 🧩 How It Works

- Two words (e.g., `"bandra"` and `"mumbai"`) are padded (if necessary) to the same length.
- Their characters are interleaved to form a scrambled string (e.g., `"bmaunmdbraai"`).
- The script reverses this process, removes padding, and prints the result as `place,city`.

- Input: bmaunmdbraai
- Output: bandra,mumbai
