Assignment

Write a c++ function that takes in a character array as an argument and returns the character that occured the most in the array.
You may assume that the array contains only lower case alphabets. You may also assume that if there are two or
characters that have the same number of occurence then the character that is returned in the first character that occured
the most first.


Put your function in a cpp file. Test your cpp file in this main function or in your own. Make sure if you are using
your own main function then you include certain files before using cout and endl.

int main()
{
	char maxOccured(char* word);

	char *word1 = "aaaabbbccc";
	char *word2 = "aaabbbbccc";
	char *word3 = "aaabbbcccc";
	char *word4 = "aabbbccc";

	cout << "Character that occured most in " << word1 << " : " << maxOccured(word1) << endl;
	cout << "Character that occured most in " << word2 << " : " << maxOccured(word2) << endl;
	cout << "Character that occured most in " << word3 << " : " << maxOccured(word3) << endl;
	cout << "Character that occured most in " << word4 << " : " << maxOccured(word4) << endl;
}


If you are using this main function then the expected output is

Character that occured most in aaaabbbccc : a
Character that occured most in aaabbbbccc : b
Character that occured most in aaabbbcccc : c
Character that occured most in aabbbccc : b


