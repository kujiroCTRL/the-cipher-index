|Field|Value|
|---|---|
|**Name**|Bird's Mind Boggles #6|
|**Author**|Illyngo (Bird)|
|**Difficulty**|⭐️⭐️⭐️|
|**Solved**|Yes|
|**Original**|https://discord.com/channels/1042924100760391710/1153018894005567498|

**Prompt**
> My first attempt at a multi-stage puzzle. Feel free to work together to solve this!
> 
> ![here](../attachments/Birds_Basics.pdf) 

<details>
<summary>Solution</summary>
Since the cipher is multi-staged I strongly suggest you to open the file in question and follow the solutions to each ciphers on the file itself

1. 
	
	```
	DASH1 DOT4 DOT1
	DASH1 DOT4 D0T1
	DASH1 DOT4 DOT1
	```

	can be read in morse as 3 copies of "- .... ." which translate to "THE"

2.
	`11 01 100 ?` can be read in morse as "-- .- -.. ." where "?" has been substituted with the stray "0" in the previous puzzle
	
	Translating this message we get "MADE"

3.
	`5-2 ?? 4-3` can be translated using the Polybius square cipher as "WAS", where "??" has been substituted with the stray "11" from the previous puzzle

4.
	`HNUMJW` can be translated using a Caeser cipher into "CIPHER"
	
	The key is the stray digit "5" from the previous puzzle

5.
	Each row corresponds to a letter from the military phonetic, thus we can fill the rows 
	
	```
       FOXTROT
    CHARLIE
      VICTOR
    ROMEO
     TANGO
     INDIA
    WHISKEY
	``` 
    The letter "W" is the key from the previous puzzle
    
    The pointed column reads "FRIENDS"

6.
    Converting the numbers to decimal and then to the corresponding letter of the latin alphabet we read 
    
    ```
    ALONG0WAY
    ```
    The letters "A" are the highlighted letter of the previous puzzle
    
7.
    Placing the keys "1" and "7" from the previous puzzle respectively to the right of the truncated "R" and to the left of the "V" the word "REAL" can be read upside-down
    
8. 
    Writing the words obtained in the previous codes in the specified order we read
    
    ```
    THE
    REAL
    CIPHER
    WAS
    THE
    FRIENDS
    MADE
    ALONG
    THE
    WAY
    ```
Thus the solution to the code is "The real cipher was the friends along the way"
</details>
