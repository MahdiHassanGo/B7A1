
---

## `blog-2.md`

```md
# How Generics Build Reusable and Strictly Typed TypeScript Code

## Introduction

Generics are one of the most powerful features of TypeScript. They allow developers to create reusable functions, classes, and interfaces while still keeping strong type safety. Instead of writing the same logic for different types, generics let us write flexible code that works with many data structures.

## The Problem Without Generics

Suppose we want a function that returns the first item from an array. Without generics, we might write separate functions for different types.

```ts
function getFirstNumber(items: number[]): number {
  return items[0];
}

function getFirstString(items: string[]): string {
  return items[0];
}