Spythonic Is A Shitty Parser That Translate Sentences To Working Python Code

Keywords:
These Are Special Words That Should Always Be First When Starting A New Line/Sentence
Such As make,call,use,change,assign,exit,include

Make:
You Can Make Objects Using The 'Make Keyword'
The Grammar For Making A Object Is Simple
[keyword] [count_specifier] [object] [property_specifier] [identifier] [extender] [keyword] [identifier/value/string]

Making A Variable:
[make] [a] [variable] [called] [str] [and] [assign] ["Hello World"]

Making a Function:
[make] [a] [function] [called] [main] [with] (if your function has no arguements)
[make] [a] [function] [called] [main] [with] argc argv (if your function has arguements)

Making A Array:
[make] [a] [array] [called] [arr] [and] [assign] [1] [2] [3] 


Call:
You Can Call Functions Using 'Call Keyword'
The Grammar For Calling Functions Is
[keyword] [count_specifier] [object] [property_specifier] [identifier] [referencer] [identifier/value/string]

Calling A Function:
[call] [a] [function] [called] [print] [with] ["Hello World"]

Use:
You Can Assign Function Return Value Using 'Use Keyword'
The Grammar For Using Functions Is
[keyword] [identifier] [extender] [keyword] [identifier] [referencer] [identifier/value/string]

Using Functions:
[use] [input] [and] [assign] [str] [with] ["Input String"]

Is/Or:
These Keywords Are Conditional Keywords Like If/Else 
The Grammar For Using Is/Or Are:
[keyword] [identifier/value/string] [less than/equal to/greater than/not equal/both/either/different] [identifier/value/string]

Otherwise:
This Keyword Is The Equivalent Of 'Else'

Using Is/Or/Otherwise:
[is] [x] [equal] [to] [y] 
[or] [x] [equal] [to] [z]
[or] [x] [equal] [to] [j]
[otherwise]
[call] [a] [function] [called] [print] [with] ["X Is Not Equal To Anything"]

While: 
This Keyword Is A 'While Loop':
And Has The Same Grammar As 'Is'
[keyword] [identifier/value/string] [less than/equal to/greater than/not equal/both/either/different] [identifier/value/string]

Using While To Make A Infinite Loop:
[while] [1] (see its that simple)


Reset:
This Keyword Resets The Indent Back To 0
This Is Typically Used With The 'Call Keyword'

Calling A Function With Reset:
[reset]
[call] [a] [function] [called] [main] [with] [0]

Exit:
This Keyword Exits A Object
This Is Used With 'loop' 'conditional'

Exiting A Loop/Conditional:
[is] [1] [equal to] [2]
[exit] [conditional]

[while] [1]
[exit] [loop] 

Change:
This Keyword Is Mostly Used For Changing The DataType Of A Variable
The Grammar For Using Change Is
[keyword] [referencer] ["datatype"] ["of"] [identifier] ["to"] [integer/float/character/string] 

Converting Input To Integer Using Change:
[make] [a] [variable] [called] [input_] [assign] [input]
[change] [the] [datatype] [of] [input_] [to] [integer]

Include:
This Keyword Is Basically 'import' In Python And Allows You To Include Modules

Importing Random Library:
[include] [random]

Calculate:
This Keyword Is Used For Arithematic Purposes
[keyword] ["how"] ["much"] ["is"] [identifier/value/string] [added by/subracted by/multiplied by/raised to/divided by/modulus by] [identifier/value/string]

Adding X Y And Z:
[calculate] [how] [much] [is] [x] [added by] [y] [added by] [z]

Examples:

Random Number Maker:
include random 
use random.randint and assign random_number with 1 50 
call a function called print with "The Number Generated Is:" random_number

