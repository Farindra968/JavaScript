
# Variables

Variable is the container containing the data with a specific name, or a name of the storage location.

```javascript
let name = 'Hari';
let age = 23;
```

- `name`, `age` are variables.

## DataType
There are 2 types of Datatype:
1. Primitive DataType
2. Non-Primitive DataType

### Primitive DataType

#### a. Number

```javascript
let age = 20;
let mark = 60;
```

- The above code is an example of the number datatype. It does not contain any alphabet, symbol, etc. It includes:
  - Positive & Negative Numbers (4, -6)
  - Floating or Decimal Numbers (4.5, -5.2)
  - Integers (20, -5)

#### b. String

```javascript
let fullName = 'Jack Paul';
let address = "New York, 4th street";
```

- The above code is an example of the string datatype. It can contain numbers, symbols, and can be identified by single (`''`) or double (`""`) quotes.

#### c. Boolean

```javascript
let isPass = true;
let isAdult = false;
```

- Boolean datatype only returns `true (1)` or `false (0)`.

#### d. BigInt

```javascript
let turnOver = 21025586689689n;
```

- The above code is a BigInt datatype. It is similar to number type but is used to store very large numbers, mainly used in stock markets, etc.

#### e. Undefined

```javascript
let name;
```

- Undefined is a type of datatype where a variable is declared but its value is not assigned.

#### f. Null

```javascript
let value = null;
```

- Null is an empty or unknown value.

#### g. Symbol

```javascript
let symbol1 = Symbol("id");
let symbol2 = Symbol("id");
```

- Symbols are unique and immutable.

## Operations in JavaScript

### Addition Operation (`+`):

```javascript
let a = 5;
let b = 6;
console.log(a + b);
```

**Output:** `5 + 6 = 11`

### Subtraction Operation (`-`):

```javascript
let a = 5;
let b = 3;
console.log(a - b);
```

**Output:** `5 - 3 = 2`

### Multiplication Operation (`*`):

```javascript
let a = 3;
let b = 4;
console.log(a * b);
```

**Output:** `3 * 4 = 12`

### Division Operation (`/`):

```javascript
let a = 6;
let b = 2;
console.log(a / b);
```

**Output:** `6 / 2 = 3`


<table >
    <tr>
        <th>Category</th>
        <th>Operator</th>
        <th>Description</th>
        <th>Example</th>
    </tr>
    <tr>
        <td rowspan="6">Arithmetic</td>
        <td>+</td>
        <td>Addition</td>
        <td>5 + 2 // 7</td>
    </tr>
    <tr>
        <td>-</td>
        <td>Subtraction</td>
        <td>5 - 2 // 3</td>
    </tr>
    <tr>
        <td>*</td>
        <td>Multiplication</td>
        <td>5 * 2 // 10</td>
    </tr>
    <tr>
        <td>/</td>
        <td>Division</td>
        <td>5 / 2 // 2.5</td>
    </tr>
    <tr>
        <td>%</td>
        <td>Modulus (Remainder)</td>
        <td>5 % 2 // 1</td>
    </tr>
    <tr>
        <td>**</td>
        <td>Exponentiation (Power)</td>
        <td>5 ** 2 // 25</td>
    </tr>
    <tr>
        <td rowspan="7">Assignment</td>
        <td>=</td>
        <td>Assign value</td>
        <td>x = 5</td>
    </tr>
    <tr>
        <td>+=</td>
        <td>Add & assign</td>
        <td>x += 2</td>
    </tr>
    <tr>
        <td>-=</td>
        <td>Subtract & assign</td>
        <td>x -= 2</td>
    </tr>
    <tr>
        <td>*=</td>
        <td>Multiply & assign</td>
        <td>x *= 2</td>
    </tr>
    <tr>
        <td>/=</td>
        <td>Divide & assign</td>
        <td>x /= 2</td>
    </tr>
    <tr>
        <td>%=</td>
        <td>Modulus & assign</td>
        <td>x %= 2</td>
    </tr>
    <tr>
        <td>**=</td>
        <td>Exponentiation & assign</td>
        <td>x **= 2</td>
    </tr>
    <tr>
        <td rowspan="8">Comparison</td>
        <td>==</td>
        <td>Equal (loose comparison)</td>
        <td>5 == "5" // true</td>
    </tr>
    <tr>
        <td>===</td>
        <td>Strict equal</td>
        <td>5 === "5" // false</td>
    </tr>
    <tr>
        <td>!=</td>
        <td>Not equal</td>
        <td>5 != 3 // true</td>
    </tr>
    <tr>
        <td>!==</td>
        <td>Strict not equal</td>
        <td>5 !== "5" // true</td>
    </tr>
    <tr>
        <td>></td>
        <td>Greater than</td>
        <td>5 > 2 // true</td>
    </tr>
    <tr>
        <td><</td>
        <td>Less than</td>
        <td>5 < 2 // false</td>
    </tr>
    <tr>
        <td>>=</td>
        <td>Greater than or equal to</td>
        <td>5 >= 5 // true</td>
    </tr>
    <tr>
        <td><=</td>
        <td>Less than or equal to</td>
        <td>5 <= 2 // false</td>
    </tr>
    <tr>
        <td rowspan="3">Logical</td>
        <td>&&</td>
        <td>Logical AND</td>
        <td>(true && false) // false</td>
    </tr>
    <tr>
        <td>||</td>
        <td>Logical OR</td>
        <td>(true || false) // true</td>
    </tr>
    <tr>
        <td>!</td>
        <td>Logical NOT</td>
        <td>!true // false</td>
    </tr>
</table>


# NAN in JS
In JavaScript, NaN stands for "Not-a-Number". It is a special value that represents an invalid or undefined numerical result. NaN type is also Number but provide Invalid or undefined numerical output.
```javascript        
console.log(0/0) // NaN
console.log(undefined+1) // NaN
console.log(Math.floor("Hello")) // NaN
console.log(parseInt("Hi")) // NaN
console.log(typeof NaN) // Number type
```



# Var, Let, Const in JS
- Var

    var (Old & Function-scoped)
    - Function-scoped (not block-scoped).
    - Can be re-declared and updated.
    - Hoisted but initialized as undefined.
    -Not recommended in modern JavaScript.

- Let

    let (Block-scoped & Mutable)
    - Block-scoped (exists only inside {} blocks).
    - Can be updated, but not re-declared in the same scope.
    - Hoisted but not initialized.
        
```javascript
a= 5, //write but not good ways to declare.
let a= 5,
let name= "Jack"
```
- Const

    const (Block-scoped & Immutable)
    - Block-scoped, like let.
    - Cannot be re-assigned variable (but objects/arrays inside can change).
    - Must be initialized at declaration.

```javascript
let age = 20,
age=30 // wrong cannot reassigned 
```
# Assignment operator
Assignment operator is used to assign values to variables. The most common assignment operator is =;
    
<table>
        <tr>
            <th>Operator</th>
            <th>Example</th>
            <th>Equivalent To</th>
            <th>Description</th>
        </tr>
        <tr><td>=</td><td>x = y</td><td>x = y</td><td>Assigns the value of y to x</td></tr>
        <tr><td>+=</td><td>x += y</td><td>x = x + y</td><td>Adds y to x and assigns the result to x</td></tr>
        <tr><td>-=</td><td>x -= y</td><td>x = x - y</td><td>Subtracts y from x and assigns the result to x</td></tr>
        <tr><td>*=</td><td>x *= y</td><td>x = x * y</td><td>Multiplies x by y and assigns the result to x</td></tr>
        <tr><td>/=</td><td>x /= y</td><td>x = x / y</td><td>Divides x by y and assigns the result to x</td></tr>
        <tr><td>%=</td><td>x %= y</td><td>x = x % y</td><td>Assigns the remainder of x / y to x</td></tr>
        <tr><td>**=</td><td>x **= y</td><td>x = x ** y</td><td>Raises x to the power of y and assigns the result to x</td></tr>
        <tr><td><<=</td><td>x <<= y</td><td>x = x << y</td><td>Left shifts x by y bits and assigns the result to x</td></tr>
        <tr><td>>>=</td><td>x >>>= y</td><td>x = x >>> y</td><td>Zero-fill right shift x by y bits and assigns the result to x</td></tr>
        <tr><td>&=</td><td>x &= y</td><td>x = x & y</td><td>Performs bitwise AND between x and y and assigns the result to x</td></tr>
        <tr><td>|=</td><td>x |= y</td><td>x = x | y</td><td>Performs bitwise OR between x and y and assigns the result to x</td></tr>
        <tr><td>^=</td><td>x ^= y</td><td>x = x ^ y</td><td>Performs bitwise XOR between x and y and assigns the result to x</td></tr>
    </table>

# Uninary Operator
Uninary Operator is a simple and shortcut method to do  Operation in Javascript.

```javascript
            let age = 10,
            age = age + 1 value 
            age +=1  
```
if we want to increase the value by 1 then simply we can use increment operator:
        
```javascript
            let age= 10;
            age++, // 10+1
            age++, //11+1
```
Similarly if we want to decrease the value by 1 then simply we can use decrement operator:

```javascript
let mark = 50,
mark --, // 50-1 =49
mark --, // 49-1 =48
```

# JavaScript String Methods

JavaScript provides several built-in string methods to manipulate and work with strings. Here are some commonly used string methods:

## 1. Basic String Methods

### **String Length**

```js
let str = "Hello, World!";
console.log(str.length); // 13
```

### **toUpperCase() & toLowerCase()**

```js
console.log(str.toUpperCase()); // "HELLO, WORLD!"
console.log(str.toLowerCase()); // "hello, world!"
```

### **charAt(index)**

```js
console.log(str.charAt(0)); // "H"
```

### **indexOf() & lastIndexOf()**

```js
console.log(str.indexOf("o")); // 4 (first occurrence)
console.log(str.lastIndexOf("o")); // 8 (last occurrence)
```

### **includes()**

```js
console.log(str.includes("World")); // true
console.log(str.includes("world")); // false (case-sensitive)
```

## 2. Extracting Substrings

### **slice(start, end)**

```js
console.log(str.slice(7, 12)); // "World"
```

### **substring(start, end)**

```js
console.log(str.substring(7, 12)); // "World"
```

### **substr(start, length)**

```js
console.log(str.substr(7, 5)); // "World"
```

## 3. Modifying Strings

### **replace()**

```js
console.log(str.replace("World", "JavaScript")); // "Hello, JavaScript!"
```

### **replaceAll()** (ES2021+)

```js
console.log("Hello Hello".replaceAll("Hello", "Hi")); // "Hi Hi"
```

### **trim(), trimStart(), trimEnd()**

```js
let text = "   Hello, World!   ";
console.log(text.trim()); // "Hello, World!"
console.log(text.trimStart()); // "Hello, World!   "
console.log(text.trimEnd()); // "   Hello, World!"
```

## 4. Splitting and Joining

### **split()**

```js
let words = str.split(", ");
console.log(words); // ["Hello", "World!"]
```

### **concat()**

```js
let str1 = "Hello";
let str2 = "World";
console.log(str1.concat(", ", str2)); // "Hello, World"
```

## 5. Repeating and Padding

### **repeat()**

```js
console.log("Ha".repeat(3)); // "HaHaHa"
```

### **padStart() & padEnd()**

```js
let num = "5";
console.log(num.padStart(3, "0")); // "005"
console.log(num.padEnd(3, "0")); // "500"
```

## 6. String to Array

### **Array.from()**

```js
console.log(Array.from("Hello")); // ['H', 'e', 'l', 'l', 'o']
```

