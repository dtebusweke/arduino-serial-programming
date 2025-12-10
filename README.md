Code Explanation
• 	The program starts by opening a serial connection at a speed of 9600 bits per second.
• 	In the , it keeps checking if any text has been typed into the Serial Monitor.
• 	If text is available, it reads the whole string and stores it in .
• 	Then it prints back the message with the word “Input:” in front of it.

In summary:
This code lets you type something into the Arduino Serial Monitor, and the Arduino will echo it back to you with a label.
Example:
If you type , the Serial Monitor will show:
Input: Hello
