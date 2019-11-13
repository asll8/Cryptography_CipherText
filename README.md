**Cryptography_CipherText**

Cryptography is the practice and study of techniques for secure communication in the presence of third parties called adversaries. In classic cryptography, one of the main cipher types is the substitution cipher, which systematically replaces letters with other letters. Following is one such cipher: you can take the alphabet and map it to its reverse so that the first letter becomes the last letter, the second letter becomes the second to last letter, and so on (see Figure 1 and Figure 2 below). For example, when you encrypt "asli" using this cipher, you will end up with "zhor", or if you encrypt "github", you will get "trgsfy". In this particular cipher, the decryption method is the same as the encryption method; for each letter, you just need to find the respective mapped letter.

The program will start by displaying a menu of options, where the user can select to (1) encrypt a plaintext, (2) decrypt a ciphertext, or (3) exit. Then, the program will prompt for the choice of the user and check the validity of this input. At this point, the user is expected to enter either "1", "2" or "3". Any other value entered by the user should be considered as an incorrect input. If the user enters an invalid input, the program should repeatedly display the menu and prompt for a choice until the user enters a valid value as his/her choice. 

When the user enters a valid input, if (s)he selects the last option, then the program will display a goodbye message and terminate its execution. Otherwise, the program will prompt for either the plaintext or the ciphertext, depending on the choice of the user. Once the program gets the text to be encrypted or decrypted, it will then perform the respective operation by following the algorithm of the cipher described above and display the result of the required encryption or decryption. The text provided by the user may contain any characters, but only the English letters (either lowercase or uppercase) should be encrypted or decrypted, the rest (digits, empty space, punctuations or any other characters) should simply be repeated in the encrypted/decrypted version of the given text. In other words, the characters other than English uppercase/lowercase letters should stay same with he encrypted/decrypted version.

<img width="648" src="https://github.com/asll8/Cryptography_CipherText/blob/master/img.jpg">

**Sample Runs**

Please select one of the options below:
1-Encrypt the text
2-Decrypt the text
3-Exit
Enter your choice: a
Invalid input!

Please select one of the options below:
1-Encrypt the text
2-Decrypt the text
3-Exit
Enter your choice: 10
Invalid input!

Please select one of the options below:
1-Encrypt the text
2-Decrypt the text
3-Exit
Enter your choice: 3
Bye...

Please select one of the options below:
1-Encrypt the text
2-Decrypt the text
3-Exit
Enter your choice: 1
Please enter the plaintext: tsubasa ve misaki
Encryption of 'tsubasa ve misaki' is 'ghfyzhz ev nrhzpr'.

Please select one of the options below:
1-Encrypt the text
2-Decrypt the text
3-Exit
Enter your choice: 2
Please enter the ciphertext: pzio svrma hxsmvrwvi10
Decryption of 'pzio svrma hxsmvrwvi10' is 'karl heinz schneider10'.

