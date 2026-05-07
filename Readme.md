# TypeScript Assignment Project

## Project Summary

This repository contains TypeScript problem-solving solutions and technical blog posts based on important TypeScript concepts. The project demonstrates how TypeScript helps developers write safer, cleaner, and more maintainable code.

The coding part focuses on functions, arrays, union types, type guards, generics, interfaces, classes, inheritance, and data structure manipulation. The blog posts explain important TypeScript concepts with simple explanations and code examples.

## Files Overview

### `solutions.ts`

This file contains TypeScript solutions for seven programming problems. Each solution is written using clean and meaningful code.

The included functions and classes are:

- `filterEvenNumbers`: Accepts an array of numbers and returns only the even numbers.
- `reverseString`: Takes a string and returns the reversed version of that string.
- `checkType`: Uses a union type and type guards to check whether the input is a string or a number.
- `getProperty`: A generic function that safely retrieves a property value from an object using `keyof`.
- `toggleReadStatus`: Accepts a `Book` object and returns a new object with an added `isRead` property.
- `Person` and `Student` classes: Demonstrate class inheritance, where `Student` extends `Person` and adds a `grade` property with a `getDetails` method.
- `getIntersection`: Takes two arrays of numbers and returns the common elements between them.

### `blog-1.md`

This file contains a blog post titled **"Why `any` Is a Type Safety Hole and `unknown` Is the Safer Choice"**.

The blog explains why using `any` can be risky in TypeScript because it disables type checking. It also explains why `unknown` is safer when working with unpredictable data.

The post covers:

- Why `any` can create runtime errors
- How `unknown` improves type safety
- The concept of type narrowing
- Using `typeof` checks to safely work with unknown values

### `blog-2.md`

This file contains a blog post titled **"How Generics Build Reusable and Strictly Typed TypeScript Code"**.

The blog explains how generics help developers create reusable functions, interfaces, and code structures while keeping strong type safety.

The post covers:

- The problem of writing duplicate functions without generics
- How generic functions work
- How generics keep input and output types connected
- Generic constraints using `keyof`
- Using generics with interfaces

## Key TypeScript Concepts Used

This project demonstrates the following TypeScript concepts:

- Strong typing
- Function return types
- Array methods
- String manipulation
- Union types
- Type guards
- Interfaces
- Generics
- Generic constraints
- `keyof`
- Classes
- Inheritance
- Object spreading
- Set data structure

## Project Structure

```txt
├── solutions.ts
├── blog-1.md
├── blog-2.md
└── README.md
```

## Purpose of the Project

The purpose of this project is to practice TypeScript fundamentals through coding problems and technical writing. It helps explain how TypeScript improves JavaScript by adding type safety, better structure, and reusable coding patterns.

## Conclusion

This repository provides simple and practical examples of TypeScript problem-solving. The blog posts and coding solutions together show how TypeScript can make code safer, cleaner, and easier to maintain.
