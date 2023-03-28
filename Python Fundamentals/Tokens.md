# Tokens

## Definition
Tokens are the smallest individual unit of a language.  <br>
They are the building blocks of a language.  <br>
It is also called the lexical unit.


## Types of Tokens
There are 5 types of tokens in Python:
- Keywords
- Identifiers
- Literals
- Punctuators / Delimiters
- Operators

You may remember these as "KILPO"

### Keywords
- Keywords are reserved words in Python.  <br>
- They cannot be renamed.  <br>
- They have a specific meaning and cannot be used as identifiers.  <br>
- All keywords are in lowercase, except for `True`, `False`, and `None`, which start with a capital letter.  <br>

List of keywords in Python:
<div>
	<table>
		<tr>
			<td>and</td>
			<td>as</td>
			<td>assert</td>
			<td>async</td>
			<td>await</td>
		</tr>
        <tr>
            <td>break</td>
            <td>class</td>
            <td>continue</td>
            <td>def</td>
            <td>del</td>
        </tr>
        <tr>
            <td>elif</td>
            <td>else</td>
            <td>except</td>
            <td>finally</td>
            <td>for</td>
        </tr>
        <tr>
            <td>from</td>
            <td>global</td>
            <td>if</td>
            <td>import</td>
            <td>in</td>
        </tr>
        <tr>
            <td>is</td>
            <td>lambda</td>
            <td>nonlocal</td>
            <td>not</td>
            <td>or</td>
        </tr>
        <tr>
            <td>pass</td>
            <td>raise</td>
            <td>return</td>
            <td>try</td>
            <td>while</td>
        </tr>
        <tr>
            <td>with</td>
            <td>yield</td>
            <td>True</td>
            <td>False</td>
            <td>None</td>
    </table>
</div>



### Identifiers
- An identifier is a ***fundamental*** unit in a programming language.  <br>
- Examples of identifiers are variable names, function names, class names, etc.  <br>

Rules for identifiers:
- An identifier can be a combination of letters in lowercase (a to z) or uppercase (A to Z) or digits (0 to 9) or an underscore (_).  <br>
- Identifiers are case-sensitive, i.e. num1 and NUM1 are different identifiers.  <br>
- An identifier cannot start with a digit.  <br>
- An identifier can start with an underscore.  <br>
- Identifiers cannot be the keywords used in Python.  <br>

Examples of **Valid** Identifiers:
- `myvar`
- `my_var`
- `myVar`
- `_myvar`
- `myvar1`
- `myvar_1`

Examples of **Invalid** Identifiers:
- `1myvar` (starts with a digit)
- `my-var` (hyphen)
- `my var` (space)
- `myvar!` (exclamation mark)
- `for` (keyword)
- `myvar@` (special character)


### Literals
- A literal is a constant value, i.e. these are fixed values.  <br>
- The different types of literals are:
    - Special Literals
    - Boolean Literals
    - Numeric Literals
    - String Literals
    - Float Literals


Examples:
###### Special Literal
- `None` is a special literal.  <br>

###### Boolean Literals
- `True` and `False` are boolean literals.  <br>

###### Numeric Literals
- Any number without a decimal point is a numeric literal.  <br>
- This can also include binary, octal, and hexadecimal literals.  <br>

Examples:
- `1010` (binary)
- `010` (octal)
- `0x123` (hexadecimal)
- `FACE` (hexadecimal)
- `123` (integer)
- `10` (integer)
- `-10` (negative integer)

###### String Literals
- String literals are characters enclosed single or double quotation marks.  <br>
- If the string starts with a single quotation mark, it must end with a single quotation mark. Same goes for double quotation marks.  <br>

Examples:
- `'Hello World'`
- `"Hello World"`
- `'123'` (Even though it seems that it is a number, it is not because it is enclosed in single quotation marks)
- `"test@test.com"`

Invalid Examples:
- `'Hello World"` (starts with a single, ends with a double quotation mark)
- `"Hello World'` (starts with a double, ends with a single quotation mark)


###### Float Literals
- Float literals are numbers with a decimal point.  <br>

Examples:
- `1.0`
- `10.5`
- `0.5`
- `1.` (even though it seems that it is an integer, it is not because it has a decimal point)
- `-0.5`
- `-5.0`


### Punctuators / Delimiters
- Punctuators are special symbols that are used to separate tokens.  <br>
- They are also called delimiters.  <br>

### Operators
- Operators are special symbols that are used to perform operations.  <br>

###### Arithmetic Operators
- `+` (addition)
- `-` (subtraction)
- `*` (multiplication)
- `/` (division)
- `%` (modulus)
Modulus function returns the remainder of the division of two numbers.  <br>
- `**` (exponentiation)
Exponentiation function returns the result of raising the first number to the power of the second number.  <br>
- `//` (floor division)
Floor division function returns the quotient of the division of two numbers. The remainder is discarded.  <br>

Examples:
- `10 + 3` (addition)               Output: `13`
- `10 - 3` (subtraction)            Output: `7`
- `10 * 3` (multiplication)         Output: `30`
- `10 / 3` (division)               Output: `3.3333333333333335`
- `10 % 3` (modulus)                Output: `1`
- `10 ** 3` (exponentiation)        Output: `1000`
- `10 // 3` (floor division)        Output: `3`


###### Relational Operators
The output returned by using relational operators is always a boolean value, i.e. `True` or `False`.  <br>

- `>` (greater than)
- `<` (less than)
- `>=` (greater than or equal to)
- `<=` (less than or equal to)
- `==` (equal to)
- `!=` (not equal to)

Examples:
- `10 > 3` (greater than)               Output: `True`
- `10 < 3` (less than)                  Output: `False`
- `10 >= 3` (greater than or equal to)  Output: `True`
- `10 <= 3` (less than or equal to)     Output: `False`
- `10 == 3` (equal to)                  Output: `False`
- `10 != 3` (not equal to)              Output: `True`
- `10 == 10` (equal to)                 Output: `True`
- `10 == '10'` (not equal to)           Output: `False` (because the data types are different)


###### Assignment Operators
- `=` (assigns the value on the right to the variable on the left)
- `+=` (adds the value on the right to the variable on the left and assigns the result to the variable on the left)
- `-=` (subtracts the value on the right from the variable on the left and assigns the result to the variable on the left)
- `*=` (multiplies the value on the right to the variable on the left and assigns the result to the variable on the left)
- `/=` (divides the value on the right from the variable on the left and assigns the result to the variable on the left)
- `%=` (modulus the value on the right from the variable on the left and assigns the result to the variable on the left)
- `**=` (exponentiates the value on the right to the variable on the left and assigns the result to the variable on the left)
- `//=` (floor divides the value on the right from the variable on the left and assigns the result to the variable on the left)

Examples:
Note: The value of x used in all operations is 10. In reality, the value will change after the operations <br>

- `x = 10` (assigns the value 10 to the variable x)                             Value of 'x': `10`
- `x += 3` (adds 3 to the variable x and assigns the result to x)               Value of 'x': `13`
- `x -= 3` (subtracts 3 from the variable x and assigns the result to x)        Value of 'x': `7`
- `x *= 3` (multiplies 3 to the variable x and assigns the result to x)         Value of 'x': `30`
- `x /= 3` (divides 3 from the variable x and assigns the result to x)          Value of 'x': `3.3333333333333335`
- `x %= 3` (modulus 3 from the variable x and assigns the result to x)          Value of 'x': `1`
- `x **= 3` (exponentiates 3 to the variable x and assigns the result to x)     Value of 'x': `1000`
- `x //= 3` (floor divides 3 from the variable x and assigns the result to x)   Value of 'x': `3`

###### Logical Operators
- `and` (returns `True` if **both** statements are `True`)
- `or` (returns `True` if **either** statement is `True`)
- `not` (returns `False` if the statement is `True`, i.e. it reverses the boolean value)

Examples:
- `True and True` (returns `True` because both statements are `True`)       Output: `True`
- `True and False` (returns `False` because one statement is `False`)       Output: `False`
- `False and True` (returns `False` because one statement is `False`)       Output: `False`
- `False and False` (returns `False` because both statements are `False`)   Output: `False`

- `True or True` (returns `True` because both statements are `True`)        Output: `True`
- `True or False` (returns `True` because one statement is `True`)          Output: `True`
- `False or True` (returns `True` because one statement is `True`)          Output: `True`
- `False or False` (returns `False` because both statements are `False`)    Output: `False`

- `not True` (returns `False` because the statement is `True`)              Output: `False`
- `not False` (returns `True` because the statement is `False`)             Output: `True`

###### Membership Operators
- `in` (returns `True` if a specified value is present in the object)
- `not in` (returns `True` if a specified value is not present in the object)

Examples:
- `10 in [1, 2, 3, 4, 5]` (returns `False` because 10 is not present in the list)       Output: `False`
- `10 in [1, 2, 3, 4, 5, 10]` (returns `True` because 10 is present in the list)        Output: `True`
- `'p' in 'python'` (returns `True` because 'p' is present in the string)               Output: `True`
- `'p' in 'java'` (returns `False` because 'p' is not present in the string)            Output: `False`

- `10 not in [1, 2, 3, 4, 5]` (returns `True` because 10 is not present in the list)    Output: `True`
- `10 not in [1, 2, 3, 4, 5, 10]` (returns `False` because 10 is present in the list)   Output: `False`
- `'p' not in 'python'` (returns `False` because 'p' is present in the string)          Output: `False`
- `'p' not in 'java'` (returns `True` because 'p' is not present in the string)         Output: `True`


###### Identity Operators
- `is` (returns `True` if both variables are the same object)
- `is not` (returns `True` if both variables are not the same object)

Examples:
- `x = 10` (assigns the value 10 to the variable x)
- `y = 10` (assigns the value 10 to the variable y)
- `z = '10'` (assigns the value '10' [as a string] to the variable z)

- `x is y` (returns `True` because both variables are the same object)          Output: `True`
- `x is z` (returns `False` because both variables are not the same object)     Output: `False`


- `x is not y` (returns `False` because both variables are the same object)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;Output: `False`
- `x is not z` (returns `True` because both variables are not the same object)&nbsp;|&nbsp;Output: `True`