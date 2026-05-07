# TypeScript Assignment Project

## Project Summary

This repository contains educational content and practical code examples based on important TypeScript programming concepts. It includes problem-solving solutions, blog posts, and examples that demonstrate how TypeScript can be used to write clean, reusable, and type-safe code.

The project focuses on core TypeScript topics such as functions, arrays, union types, generics, interfaces, object manipulation, classes, inheritance, and Object-Oriented Programming principles.

## Files Overview

### `blog-1.md`

This file contains a blog post titled **"Understanding Generics: Building Reusable Yet Strictly Typed Code"**.

The blog explains how generics work in TypeScript and why they are useful for creating reusable code while maintaining strong type safety. It discusses how generic functions, interfaces, and classes can handle different data types without losing type information.

The post also covers generic constraints, multiple type parameters, and real-world examples. It highlights why generics are a better choice than using `any` when flexibility and type safety are both needed.

### `blog-2.md`

This file contains a blog post titled **"Mastering the Four Pillars of OOP in TypeScript: Writing Cleaner and Scalable Code"**.

The blog explains the four main principles of Object-Oriented Programming:

1. Encapsulation
2. Abstraction
3. Inheritance
4. Polymorphism

Each concept is explained with TypeScript code examples. The post also discusses how OOP helps developers organize logic, reduce complexity, and build maintainable applications. A real-world healthcare system example is used to show how these OOP principles can be applied in practical software development.

### `solutions.ts`

This file contains TypeScript solutions for several programming problems. The solutions demonstrate different language features and problem-solving techniques.

The included functions and classes are:

- `filterEvenNumbers`: Filters and returns only the even numbers from an array.
- `reverseString`: Reverses a given string.
- `checkType`: Checks whether a value is a string or a number using union types and type guards.
- `getProperty`: Uses generics and `keyof` to safely retrieve a property value from an object.
- `toggleReadStatus`: Adds an `isRead` property to a `Book` object.
- `Person` and `Student` classes: Demonstrate class inheritance, where `Student` extends `Person` and includes a `getDetails` method.
- `getIntersection`: Finds the common elements between two number arrays using `Set`.

## Key TypeScript Concepts Used

This project demonstrates the following TypeScript concepts:

- Strong typing
- Function return types
- Arrays
- Union types
- Type guards
- Interfaces
- Generics
- Generic constraints
- Classes
- Inheritance
- Object spreading
- Set data structure

## Purpose of the Project

The purpose of this project is to practice TypeScript fundamentals through coding problems and technical writing. It helps build a better understanding of how TypeScript improves JavaScript development by making code more structured, readable, and type-safe.

## Project Structure

```txt
├── solutions.ts
├── blog-1.md
├── blog-2.md
└── README.md