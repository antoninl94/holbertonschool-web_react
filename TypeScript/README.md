# TypeScript Fundamentals

This project serves as a hands-on guide to mastering key features of TypeScript. It is designed for developers who want to strengthen their understanding of TypeScript's static typing, object-oriented patterns, and integration with JavaScript tools and the DOM.

## Topics Covered

### 1. **Basic Types in TypeScript**
- Understand TypeScript's type system: `string`, `number`, `boolean`, `null`, `undefined`, `void`, `any`, `unknown`, `never`, and `enum`.
- Type inference and type annotations.
- Arrays and tuples.
- Literal and union types.

### 2. **Interfaces, Classes, and Functions**
- Define object shapes using `interface` and `type`.
- Create reusable class-based code with constructors, access modifiers, inheritance, and method overriding.
- Typing for regular and arrow functions.
- Optional, default, and rest parameters.

### 3. **Working with the DOM and TypeScript**
- Safely select and manipulate DOM elements using TypeScript.
- Handle events with proper type annotations (e.g., `MouseEvent`, `KeyboardEvent`).
- Use type guards and assertions to ensure safe DOM interactions.

### 4. **Generic Types**
- Create flexible and reusable components with generics.
- Generic constraints using `extends`.
- Use generics with functions, interfaces, and classes.

### 5. **Namespaces**
- Encapsulate and organize code using the `namespace` keyword.
- Group related logic and avoid global scope pollution.

### 6. **Declaration Merging**
- Understand how TypeScript merges multiple declarations (e.g., interfaces, namespaces).
- Extend third-party types safely through merging.

### 7. **Ambient Namespaces and External Libraries**
- Use `declare namespace` to describe the shape of external libraries (e.g., jQuery).
- Provide type definitions for non-TypeScript libraries.
- Understand how `DefinitelyTyped` and `.d.ts` files work.

### 8. **Basic Nominal Typing**
- Simulate nominal typing (distinct types with the same structure) using `branding` or `unique symbol`.
- Prevent type mismatches between logically distinct types with structural similarities
