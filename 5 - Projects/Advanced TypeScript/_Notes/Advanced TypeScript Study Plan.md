# Personalized Study Plan: Achieving TypeScript Wizardry

Based on your performance, you are already an **Advanced** TypeScript developer. This plan focuses on refining specific areas and diving into deeper, more complex topics to reach the "wizard" level.

## Phase 1: Solidify Advanced Fundamentals (Estimate: 1-2 weeks)

### 1. Mastering Mapped Types
*   **Focus:** Conditional modifiers (`?`, `readonly`), key remapping (`as`) combined with conditional types, filtering keys.
*   **Practice:** Revisit Problem 12's solution. Create variations like `MakeReadonly<T, K extends keyof T>` (makes only specified keys `K` readonly) or `FilterByType<T, U>` (keeps only properties of type `U`).
*   **Resource:** [TypeScript Docs - Mapped Types](https://www.typescriptlang.org/docs/handbook/2/mapped-types.html) (Study Key Remapping via `as` and mapping modifiers).

### 2. Deep Dive into Conditional Types & `infer`
*   **Focus:** Complex `infer` scenarios (multiple `infer`s, inferring different positions like parameters/tuples), distributive conditional types, the `never` type's role.
*   **Practice:** Create utility types like `GetFunctionParameters<T>`, `GetFirstArgument<T>`, `Flatten<T[]>` (flattens an array by one level).
*   **Resource:** [TypeScript Docs - Conditional Types](https://www.typescriptlang.org/docs/handbook/2/conditional-types.html) (Review `infer` examples and Distributive Conditional Types).
*   **Resource:** [TypeScript Type Challenges (GitHub Repo)](https://github.com/type-challenges/type-challenges) - Tackle "Medium" level challenges focusing on `infer` and conditional types.

### 3. Enums & Alternatives
*   **Focus:** Solidify string vs. numeric enums. Explore `as const` objects for simple string constants and understand their trade-offs (readability, tree-shaking, no reverse mapping).
*   **Resource:** [TypeScript Docs - Enums](https://www.typescriptlang.org/docs/handbook/enums.html)
*   **Resource:** [Blog Post: Alternatives to Enums](https://www.basedash.com/blog/typescript-enums-are-probably-a-bad-idea) (For alternative perspectives).

### 4. Namespaces Revisited
*   **Focus:** Understand syntax, namespace merging, and primary use cases (global scope organization, legacy UMD modules). Contrast sharply with ES Modules.
*   **Resource:** [TypeScript Docs - Namespaces](https://www.typescriptlang.org/docs/handbook/namespaces.html)

## Phase 2: Advanced Patterns and Tooling (Estimate: 2-4 weeks)

### 1. Advanced Decorators
*   **Focus:** Parameter, property, and accessor decorators. Understand decorator metadata (`emitDecoratorMetadata`, `reflect-metadata`) and its use in frameworks (NestJS, TypeORM).
*   **Practice:** Implement a basic validation decorator (e.g., `@IsPositive`) using metadata.
*   **Resource:** [TypeScript Docs - Decorators](https://www.typescriptlang.org/docs/handbook/decorators.html)
*   **Resource:** [Understanding `reflect-metadata`](https://blog.logrocket.com/understanding-reflect-metadata-typescript/)

### 2. Declaration Files (`.d.ts`) Mastery
*   **Focus:** Declaring globals (`declare global`), module augmentation, handling different module formats (UMD, `export =`), using tools like `dts-gen`.
*   **Practice:** Find a small JS library without types and write a `.d.ts` file for it. Consider contributing to DefinitelyTyped.
*   **Resource:** [TypeScript Docs - Declaration Files](https://www.typescriptlang.org/docs/handbook/declaration-files/introduction.html) (Read Publishing, Consumption, Library Structures).
*   **Resource:** [DefinitelyTyped Contribution Guide](https://definitelytyped.org/guides/contributing.html)

### 3. `tsc` and `tsconfig.json` Deep Dive
*   **Focus:** Master key compiler options (the `strict` family, `target`, `module`, `lib`, `outDir`, `rootDir`, `paths`, `declaration`, `sourceMap`). Understand project references for monorepos.
*   **Resource:** [TypeScript Docs - `tsconfig.json`](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)
*   **Resource:** [TypeScript Docs - Compiler Options Reference](https://www.typescriptlang.org/tsconfig)

### 4. Nominal Typing Simulation
*   **Focus:** Understand structural vs. nominal typing. Implement techniques for nominal simulation (branded types using unique symbols or intersection types) where structure alone is insufficient (e.g., `UserID` vs `ProductID` both as `number`).
*   **Resource:** [Blog Post: Nominal Typing Techniques in TypeScript](https://michalzalecki.com/nominal-typing-in-typescript/)

## Phase 3: Architectural Application and Ecosystem (Ongoing)

### 1. Complex Type System Design
*   **Focus:** Analyze type systems in large libraries (Redux Toolkit, Zod, tRPC, React Query). Design your own complex, type-safe systems (e.g., state machine, API client generator, type-safe event emitter).
*   **Resource:** Explore source code of popular TypeScript libraries on GitHub.
*   **Resource:** [Type Challenges - Hard/Extreme Levels](https://github.com/type-challenges/type-challenges)

### 2. Integration with Frameworks
*   **Focus:** Deepen understanding of TypeScript's role in frameworks like React (Generic Hooks, Context typing, Prop inference), Angular (DI, Decorators), Vue (Composition API typing), NestJS (Decorators, Modules), Express (Middleware typing).

### 3. Build Tools and Linting
*   **Focus:** Configure TypeScript with build tools (Webpack+`ts-loader`, Vite, esbuild) and linters (`eslint` + `@typescript-eslint/parser`). Understand `eslint` rules specific to TypeScript best practices.
*   **Resource:** [@typescript-eslint Documentation](https://typescript-eslint.io/)

### 4. Performance and Advanced Language Concepts
*   **Focus:** Understand potential compiler performance impacts of complex types. Learn about Variance (covariance/contravariance), Assertion Functions (`asserts`), the `satisfies` operator, and `const` type parameters.
*   **Resource:** [TypeScript Docs - Release Notes](https://devblogs.microsoft.com/typescript/) (Track new features and advanced concepts).
*   **Resource:** [TypeScript Docs - Everyday Types](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html) (Revisit sections on Assertion Functions).
*   **Resource:** [TypeScript 4.9 `satisfies` Operator](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-4-9.html#the-satisfies-operator)