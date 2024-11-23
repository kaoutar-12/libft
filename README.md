libft: My C Library That Does it All (Seriously, It Does)
Welcome to libft—my very own C library! It does everything you need, from checking characters to managing memory and even creating linked lists. If you’re just starting out with C programming, this post is for you. Let’s dive in! 😎

1. Functions from <ctype.h> (For Testing Characters)
ft_isascii: Checks if a character is an ASCII character (basically, the characters you see on your keyboard). 🅰️
ft_isalnum: Checks if a character is a letter or a number. 🔢🔠
ft_isalpha: Checks if a character is a letter (A-Z or a-z). 📚
ft_islower: Checks if a character is a lowercase letter. 🔤
ft_isupper: Checks if a character is an uppercase letter. 🔠
ft_isdigit: Checks if a character is a number. 🔢
ft_isprint: Checks if a character can be printed on the screen (including spaces). 🖨️
ft_tolower: Converts an uppercase letter to lowercase. 🖤
ft_toupper: Converts a lowercase letter to uppercase. ✨
2. Functions from <stdlib.h> (For Numbers and Memory)
ft_atoi: Turns a string (like "42") into an integer (42). 🔢✨
ft_calloc: Allocates memory for storing data. Think of it as buying space to keep your stuff. 🏠
3. Functions from <strings.h> (For Working with Strings)
ft_bzero: Sets a chunk of memory to zero. It’s like cleaning up a messy room. 🧼
ft_memset: Sets a chunk of memory to a specific value. 🖋️
ft_memchr: Finds a specific byte in a chunk of memory. 🔍
ft_memcmp: Compares two chunks of memory to see if they’re the same. ⚖️
ft_memmove: Moves data around in memory safely. 🏃‍♂️
ft_memcpy: Copies data from one place in memory to another. 📋
ft_strlen: Finds out how long a string is (number of characters). 📏
ft_strchr: Finds the first occurrence of a character in a string. 🔎
ft_strrchr: Finds the last occurrence of a character in a string. ⬅️
ft_strstr: Finds a smaller string inside a bigger one. 🕵️‍♂️
ft_strnstr: Same as ft_strstr, but with a size limit. ⏱️
ft_strcmp: Compares two strings to see if they’re the same. 🥇
ft_strncmp: Compares the first part of two strings. 🔥
ft_strcpy: Copies one string into another. 📤
ft_strncpy: Copies a limited number of characters from one string to another. 🛑
ft_strdup: Makes a copy of a string and stores it in a new memory location. 🔄
ft_strlcpy: Safely copies a string into another, limiting the size. 🔒
ft_strlcat: Safely combines two strings together. 🍝
4. Non-Standard Functions (For Extra Fun)
ft_putchar_fd: Prints a character to a file. 📂
ft_putstr_fd: Prints a string to a file. 📝
ft_putendl_fd: Prints a string followed by a newline to a file. 🧑‍💻
ft_putnbr_fd: Prints an integer to a file. 🔢💻
ft_itoa: Converts an integer into a string. 🧙‍♂️
ft_substr: Extracts part of a string. Think of it like cutting out a slice of bread. 🍞
ft_strtrim: Removes unwanted characters from the start and end of a string. ✂️
5. Linked List Functions (For Working with Lists)
ft_lstnew: Creates a new list node (like adding a new item to your shopping list). 📝
ft_lstsize: Counts how many items are in a list. 🧑‍🤝‍🧑
ft_lstlast: Finds the last item in the list. 🏁
ft_lstadd_back: Adds an item to the end of the list. 🔙
ft_lstadd_front: Adds an item to the start of the list. 💥
ft_lstdelone: Removes an item from the list. 🗑️
ft_lstclear: Removes multiple items from the list. ✨
ft_lstiter: Applies a function to each item in the list. 🎨
ft_lstmap: Creates a new list by applying a function to each item in the original list. 🚀
