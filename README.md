# laguangesInOne
A repo to list the differences of different programming laguanges


Arithmatics

| Operator | Java | Erlang | Elixir |
|:---:|:---:|:---:|:---:|
|     Add   | + | + | + |
|   Minus   | - | - | - |
|  Multiply | * | * | * |
|  Divide   | / | / | div a,b |
|  DivideF  | (float)/| / | / |
| Reminder  | % | % | rem a,b|
| Or        | \|\| | | \|\| |
| And       | && | | && |
| Not       | ! | | ! |
| Or_Strict |  | | or |
| And_Strict |  | | and |
| Not_Strict |  | | not |
| compare | ==, !=, <=, >=, <, > |  | ==, !=, <=, >=, <, > |
| compare_Strict |  |  | ===, !== |


Functions

| Feature | Java | Elixir  |
|:---:|:---:|:---:|
| Identify| funName+argTypes | funName/numOfArgs |
| constants| enum | atom |
| Anonymous | Function f = (a, b)->{return a + b;} | f = fn a, b -> a + b end |
| Anonymous call| ~~Required~~ | f.(a,b) |

Strings

| Feature | Java | Elixir  |
| ------- |:----:| ------: |
| line breaks | \\n | \\n |
| constants| enum | :atom |
| Length  | object.length | String.length/1 |
| ToUpperCase | object.toUpperCase | String.upcase/1 |
| concatenation | ++ | <> |


DataStructures
| Names | Java | Elixir  |
|:-------:|:----:|:------:|
| LinkedList | new LinkedList({a,b}) | \[a,b\] |
| Tuples     | Array  | {a,b} |

List
| Names | Java | Elixir  |
| ------- |:----:| ------: |
|concatenated |  ~~Required~~ |++|
|subtracted  |  ~~Required~~  |--|

Tuples
| Names | Java | Elixir  |
| ------- |:----:| ------: |
| Access Element |  object\[integer\] | elem/2 (0-index)|
|  Size |  object.size(array) | tuple_size/1|
| Add Element | object\[integer\] = v | put_elem/3 (t,index,v) |

Files Operations
File.read/1

Boolean
type not boolean and true will be false in java
Providing a non-boolean will raise an exception in Elixir
all values except false and nil will evaluate to true:

Elixir specials
1. Identify Functions
..* is_boolean/1, is_integer/1, is_float/1, is_number/1, is_atom/1, is_binary/1, is_function/1, i/1

2. Aliases constructor
..* Aliases start in upper case and are atoms

3. immutable data structures
..* List operators never modify the existing list. Concatenating to or removing elements from a list returns a new list. We say that Elixir data structures are immutable.

4. charlist
..* When Elixir sees a list of printable ASCII numbers, Elixir will print that as a charlist (literally a list of characters), single-quoted and double-quoted representations are not equivalent in Elixir as they are represented by different types:

5. Compare types
number < atom < reference < function < port < pid < tuple < map < list < bitstring
