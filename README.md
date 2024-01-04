# Solidity-Course-Lesson-001-DataType
**- Solidity is a statically typed language**

**- It has various data types to handle different kinds of data.**

**- Solidity data types define the kind of data that can be stored in variables**
![Solidity Data Type](https://github.com/Cyfrin/foundry-full-course-f23/assets/35864731/57923f7e-62da-41df-9ffc-39b38b697317)

# ValueType

# 1-boolean

**- The possible value are constant (true or false)**

**- Defualt value for booleans false**

**- Name use in code bool**

**- Example value true or false**

**- IT is essential for expressing conditional logic in smart contracts **


![1_OS8dxK91Nl37tqbMbAwaZQ](https://github.com/Cyfrin/foundry-full-course-f23/assets/35864731/f7c8cff5-0cdd-43e1-9059-326b615e48d2)

### **Examples**

```solidity
contract BoolExample {
    // Defualt boolean Value False
    // boolean variable return true or false
    bool isApproved;   
    bool isMarried; 
    bool isActive = true;
    bool study = false;
}
```

# 2- Integers
- Integers are used to represent whole numbers
- Sign and unsign integers of various sizes
- Name use in code (int-uint)
- int these are signed integers that hold both negative and positive values
- uint these are unsigned integers that can hold 0 and positive values only
- Integers sign various size(int8-int16-int32-int64-int128-int256)
- Integers unsign various size(uint8-uint16-uint32-uint64-uint128- uint256)
- Integers are restricted to a certain range For example uint8 take value from zero up to 2**8 -1 (0–255)
- uint16 (0–65535)
- uint by defualt equals uint256
- Signed integers can represent negative values
- unsigned integers can only represent positive values.
- Fixed point numbers are not fully supported by Solidity yet.

  ![1_2hpBBUWZVyOhrsiA11L-TA](https://github.com/Cyfrin/foundry-full-course-f23/assets/35864731/67b37d6b-db26-47c3-86c4-9319d7551d88)

  ### **Examples**

```solidity
contract integerExample{
    int wheather= -2;
    int airPodes;
    uint iphonePrice;
    uint8 macPrice=255; // only number(0-255)
    uint16 ipadPrice= 65535; // only number(0-65535_
}
```

# 3-String




  













