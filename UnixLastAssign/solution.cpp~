#include<iostream>

using std::cout;
using std::endl;

/**
	This function will return the max occurence of a
	a character in a word. This function only works for
	lower case alphabets
*/
char maxOccured(char* word)
{
	int alphabets[26];
	int i = 0;
	int index = 0;
	
	while(i < 26) // clearing the array to have values 0
	{
		alphabets[i] = 0;
		i++;
	}
	
	i = 0;

	while(word[i] != 0) //while u have not reached the end of the word
	{
		index = word[i] - 97;  // 97 is got from the ascii table
		alphabets[index] = alphabets[index] + 1;
		index = 0;
		i++;
	}

	i = 0;
	index = 0;
	int max = alphabets[0];

	while(i < 26)
	{
		if (max < alphabets[i])
		{
			max = alphabets[i];
			index = i;
		}

		i++;
	}

	return (char) (index + 97);
}

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

