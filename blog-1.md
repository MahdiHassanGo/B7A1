# Why `any` Is a Type Safety Hole and `unknown` Is the Safer Choice

## Introduction

TypeScript helps developers write safer JavaScript by checking types before code runs. However, using `any` can break this safety. The `any` type tells TypeScript to stop checking a value, which can lead to runtime errors. A safer alternative is `unknown`, because it forces developers to check the type before using the value.

### Why `any` Is Dangerous

When a variable is typed as `any`, TypeScript allows any operation on it. This means you can call methods, access properties, or assign it to other types without any warning.

```ts
let value: any = "Hello";

value.toUpperCase();
value.toFixed();