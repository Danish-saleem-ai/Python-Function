###String Modification Methods###
#capitalize(): Converts the first character of the string to uppercase.#
#casefold(): Converts all characters to lowercase, aggressively.
#center(width, fillchar=' '): Centers the string within a field of #specified width, using a specified fill character (default is a space).
#join(iterable): Concatenates elements of an iterable (e.g., a list or tuple), separated by the string itself.
#ljust(width, fillchar=' '): Left-justifies the string within a field of specified width, using a specified fill character.
lower(): Converts all characters to lowercase.
#lstrip(chars=None): Removes leading characters from the string based on a specified set of characters (default is whitespace).
#replace(old, new, count=None): Replaces occurrences of the old substring with the new substring, optionally specifying the maximum number of replacements.
#rstrip(chars=None): Removes trailing characters from the string based on a specified set of characters (default is whitespace).
#strip(chars=None): Removes both leading and trailing characters from the string based on a specified set of characters (default is whitespace).
#swapcase(): Swaps the case of all characters in the string.
#title(): Converts the first character of each word to uppercase and the rest to lowercase.
#upper(): Converts all characters to uppercase.
#zfill(width): Fills the string with zeros from the left until it reaches the specified width.
#String Information Methods
#count(sub, start=0, end=None): Counts the number of occurrences of a substring within the string, optionally specifying the start and end indices.
#endswith(suffix, start=0, end=None): Checks if the string ends with a specified suffix.
#find(sub, start=0, end=None): Returns the lowest index of the substring within the string, or -1 if not found.
#index(sub, start=0, end=None): Similar to find, but raises a ValueError if the substring is not found.
#isalnum(): Checks if the string consists of alphanumeric characters only.
#isalpha(): Checks if the string consists of alphabetic characters only.
#isascii(): Checks if all characters in the string are ASCII characters.
#isdigit(): Checks if the string consists of digits only.
#isidentifier(): Checks if the string is a valid Python identifier.
#islower(): Checks if all characters in the string are lowercase.
#isnumeric(): Checks if the string consists of numeric characters only.
#isprintable(): Checks if all characters in the string are printable.
#isspace(): Checks if the string consists of whitespace characters only.
#istitle(): Checks if the string is in title case.
#isupper(): Checks if all characters in the string are uppercase.
#startswith(prefix, start=0, end=None): Checks if the string starts with a specified prefix.
String Formatting Methods
#**format(*args, kwargs): Formats the string using placeholders and positional or keyword arguments.
#format_map(mapping): Formats the string using a dictionary-like mapping.