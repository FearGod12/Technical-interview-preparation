# Technical-interview-preparation

## 0. Write a function in C that checks if a singly linked list has a cycle in it.

	Prototype: int check_cycle(listint_t *list);

	Return: 0 if there is no cycle, 1 if there is a cycle

### 	Requirements:

	Only these functions are allowed: write, printf, putchar, puts, malloc, free
## 1. Write a function in C that inserts a number into a sorted singly linked list.

	Prototype: listint_t *insert_node(listint_t **head, int number);

	Return: the address of the new node, or NULL if it failed
## 2. Write a function in C that checks if a singly linked list is a palindrome.

	Prototype: int is_palindrome(listint_t **head);
	Return: 0 if it is not a palindrome, 1 if it is a palindrome
	An empty list is considered a palindrome
## 3. Create a function def roman_to_int(roman_string): that converts a Roman numeral to an integer.

	You can assume the number will be between 1 to 3999.
	def roman_to_int(roman_string) must return an integer
	If the roman_string is not a string or None, return 0
