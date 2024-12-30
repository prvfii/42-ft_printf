𝑭𝒕_𝒑𝒓𝒊𝒏𝒕𝒇
      
      Reimplementing the famous printf function from the C standard library.

________________________________________________________________________________

Description

The ft_printf project is part of the 42 curriculum and aims to recreate the functionality of the C library function printf. This project helps to deepen your understanding of variadic functions, string formatting, and modular programming while adhering to strict coding standards.

Features

The implementation supports a subset of the standard printf functionality, including the following format specifiers:

			•	%c: Prints a single character.
   
			•	%s: Prints a string.
   
			•	%p: Prints a pointer address.
   
			•	%d / %i: Prints a signed decimal integer.
   
			•	%u: Prints an unsigned decimal integer.
   
			•	%x / %X: Prints a hexadecimal integer (lowercase/uppercase).
   
			•	%%: Prints a percent sign.

Other behaviors of printf are also emulated, including:
	•	Proper memory management.
	•	Handling of variadic arguments.
	•	Output to the standard output.
