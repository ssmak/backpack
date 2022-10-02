# Typescript

### Primitive types
```typescript
string
number
boolean
bigint // const oneHundred: bigint = BigInt(100);
null
undefined
any
Symbol("name") // const firstName = Symbol("name")
```

### typeof type guards
```typescript
"string"
"number"
"bigint"
"boolean"
"symbol"
"undefined"
"object"
"function"
```

### Object
```typescript
// Iterate an object
for (const key of Person) { ... }

// Check if key in object
if("birth" in Person) { ... }

```

### function
```typescript
function firstElement<Type>(arr: Type[]): Type | undefined {
  return arr[0];
}
```