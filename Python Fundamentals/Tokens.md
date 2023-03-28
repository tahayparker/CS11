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

Examples of Valid Identifiers:
- `myvar`
- `my_var`
- `myVar`
- `_myvar`
- `myvar1`
- `myvar_1`

Examples of Invalid Identifiers:
- `1myvar` (starts with a digit)
- `my-var` (hyphen)
- `my var` (space)
- `myvar!` (exclamation mark)
- `for` (keyword)
- `myvar@` (special character)