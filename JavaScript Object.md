# Operations on Object  (not an Instance)

When a Constructor is called a new Object is created, that object represents a type

Objects can be mutable or Immutable 

Objects are made up of **Key & Value** pair eg. { name: "Israel" }, each key has characteristics (enumerable, writable, configuration) which affects how the keys are accessible

1. Creating, Coping & Checking Objects
2. Making Object Immutability & and checking Immutability  (seal, freeze, extensible)
3. Getting Object Keys and Values
4. Converting Object Keys and Values to an Array and back to an Object
5. Getting and Setting Object Key(s) Characteristics (Enumerable, Writable, Configurable)
6. Getting Prototype

## Creating, Coping & Comparing

Object.create 
Object.assign
Object.is

## Immutability & Checking Immutability

Object.seal
Object.freeze
Object.preventExtensions
Object.isExtensible
Object.isFrozen
Object.isSealed

## Getting keys and values 

Object.values
Object.keys

Object.getOwnPropertyNames
Object.getOwnPropertySymbols

## Converting to an Array, Converting from Array to Object

Object.entries
Object.fromEntries

## Creating Property(s) & Getting Property(s) characteristics

Object.defineProperty
Object.defineProperties
Object.getOwnPropertyDescriptor
Object.getOwnPropertyDescriptors

## Getting Prototype


Object.getPrototypeOf

# Operations when Objects are Instantiated 

The methods below are available when a constructor is called with the "new" keyword, that means all object types (Arrays, Strings, RegExp, Date, etc) all have these methods, cause of Inheritance 

## Checking Properties

Object.prototype.propertyIsEnumerable
Object.prototype.hasOwnProperty

## Checking Prototype

Object.prototype.isPrototypeOf

## Converting to a String representation

Object.prototype.toString