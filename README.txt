1. For the 'Two Strings' exercise, only two test cases gave an error, and they
both due to time limit exceeded.

2. Mars Exploration:
	- Time complexity: The loop that iterates over each character of the 
input string s to compare it with the corresponding character in the word string 
takes O(s.length()) time. Therefore, the total time complexity of this code is 
O(s.length()), which is essentially O(n).

	- Space Complexity: The space complexity is O(s.length()) + O(numWord), 
and since numWord is related to the length of the input string s, we can 
simplify this to O(s.length()), or O(n).