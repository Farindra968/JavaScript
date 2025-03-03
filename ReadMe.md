
# Variables

Variable is the container containing the data with the specific name. Or a name of the storage location.

    example: 
    
        let name = 'Hari'
        let age = 23
    
    :: "name", "age" is the variable


# DataType
There are 2 types of Datatype.
1. Primitive DataType
2. Non Primitive DataType

- Primitive DataType.
    
    a. Number

        example:
            let age= 20,
            let mark = 60,
        
        :: above code is the example of number datatype. It do not contain any alphabet, symbol, etc. pure number only. 
        Number include;
            a. Positive & Negative (4, -6),
            b. Floating or Decimal Number (4.5, -5.2),
            c. Integers (20, -5)

    b. String

        example: 
            let fullName = 'Jack Paul',
            let address = "New York, 4th street"
        
        :: above code is the example of string datatype. It can contain number, symbol. String datatype can be identified by the quote '', or double quote "".
    
    c. Boolean:

        example:
            let ispass = true;
            let isAdult = false;
        
        :: above is the boolean datattype. It only give the answer or result in true (1) or false (0)

    d. Bignit:

        example:
            let turnOver = 21025586689689;

        :: above code is the Bignit datatype. Bignit datatype is also similar to number type but, Bignit datatype contain large number. Bignit datatype is mainly used in stockMarket, etc

    e. Undeined:

        example: 
            let name= ;
        
        :: Undefined is the type of datatype, where variable is defined but its data is not defined
    
    f. Null

    g. Symbol.

# Operation in JS
- Addition Operation (+):
        
        example: 
            let a = 5,
            let b= 6,
            console.log(a+b)
        
        Output= 5+6 = 11

- Subtraction Operation (-):

        example: 
            let a= 5,
            let b= 3,
            console.log(a-5);
        
        Output =  5-3 = 2

- Multiplication Operation (*):

        example: 
             let a= 3,
             let b = 4,
             console.log(a*b);
        
        Output = 3*4 = 12

- Division Operation (/):

        example: 
            let a = 6,
            let b = 2,
            console.log(a/b);

        Output = 6/2 = 3  

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

    example: 
        console.log(0/0) // NaN
        console.log(undefined+1) // NaN
        console.log(Math.floor("Hello")) // NaN
        console.log(parseInt("Hi")) // NaN

        console.log(typeof NaN) // Number type




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
        
            example:
                a= 5, //write but not good ways to declare.
                let a= 5,
                let name= "Jack"

- Const

    const (Block-scoped & Immutable)
    - Block-scoped, like let.
    - Cannot be re-assigned variable (but objects/arrays inside can change).
    - Must be initialized at declaration.

            example:
                let age = 20,
                 age=30 // wrong cannot reassigned 

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

        example:
            let age = 10,
            age = age + 1 value 
            age +=1  
if we want to increase the value by 1 then simply we can use increment operator:
        
        example:
            let age= 10;
            age++, // 10+1
            age++, //11+1
Similarly if we want to decrease the value by 1 then simply we can use decrement operator:

        example:
            let mark = 50,
            mark --, // 50-1 =49
            mark --, // 49-1 =48
