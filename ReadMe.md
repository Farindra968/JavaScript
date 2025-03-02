
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