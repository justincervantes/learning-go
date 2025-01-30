# Literals

Untyped in Go

# Integer Literal

- Base 10 default
- Prefixes allowed: 0b - binary, 0o - octal, 0x - hex
- Go allows you to use underscores in integer literals, and is useful for long numbers like 1_132_118 to help you read numbers faster (no underscores at start or end allowed)
- Typically, always use base 10, octal ius used for POSIX permission flags, hex and binary are used for filters or networking and infrastructure applications

# Floating Point Literal

- Has a decimal to indicate fractional portion of a value
- Allows exponent specifications with e and a positive or negative number, for example 5.02e10, or 5.02e-10

# Rune Literals

- Characters surrounded by single quotes
- In go, single quotes and double quotes are NOT interchangable
- Rune literals can be single:
  - unicode chars - 'a'
  - 8 bit octal numbers - '\141'
  - 8 bit hex numbers - '\x61'
  - 16 bit hex numbers - '\U0061'
  - 32 bit unitcode numbers - '\U00000061'

# Interpreterd String Literals

- Contain zero or more rune literals, ie "Greetings and Salutations"
- To add rune literals, they must be escaped "Greetings and \n\"Salutations\""

# Raw String Literals

- Similar to template literals in JavaScript, you might take `hello
world`
