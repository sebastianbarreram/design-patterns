# Design Patterns in TypeScript

This repository contains implementations of various design patterns in TypeScript with practical examples.

## Description

A collection of design pattern implementations to understand and practice software design principles using TypeScript.

## Prerequisites

Make sure you have Node.js installed and install the required dependencies:

```bash
# Install ts-node globally (recommended)
npm install -g ts-node typescript

# Or install project dependencies if package.json exists
npm install
```

## Running Design Patterns

### Option 1: Using ts-node (Recommended)

You can run any TypeScript pattern file directly using ts-node:

```bash
# Run a specific pattern
npx ts-node 01-Creationals/01-builder.ts
npx ts-node 01-Creationals/02-factory.ts
npx ts-node 02-Structurals/01-adapter.ts
npx ts-node 03-Behaviorals/01-observer.ts

# Or if ts-node is installed globally
ts-node 01-Creationals/01-builder.ts
```

### Alternative Options

```bash
# Option 2: Compile then run
npx tsc 01-Creationals/01-builder.ts
node 01-Creationals/01-builder.js

# Option 3: Using tsx (modern alternative)
npx tsx 01-Creationals/01-builder.ts
```

## Pattern Categories

### 🏗️ Creational Patterns
```bash
# Builder Pattern
npx ts-node 01-Creationals/01-builder.ts

# Factory Pattern
npx ts-node 01-Creationals/02-factory.ts

# Singleton Pattern
npx ts-node 01-Creationals/03-singleton.ts
```

### 🔧 Structural Patterns
```bash
# Adapter Pattern
npx ts-node 02-Structurals/01-adapter.ts

# Decorator Pattern
npx ts-node 02-Structurals/02-decorator.ts

# Facade Pattern
npx ts-node 02-Structurals/03-facade.ts
```

### 🎯 Behavioral Patterns
```bash
# Observer Pattern
npx ts-node 03-Behaviorals/01-observer.ts

# Strategy Pattern
npx ts-node 03-Behaviorals/02-strategy.ts

# Command Pattern
npx ts-node 03-Behaviorals/03-command.ts
```

## Quick Start

1. Clone the repository
2. Navigate to the project directory
3. Install dependencies: `npm install -g ts-node typescript`
4. Run any pattern: `npx ts-node [category]/[pattern-file].ts`

## Example Output

When running the Builder pattern:
```bash
npx ts-node 01-Creationals/01-builder.ts
```

Expected output:
```
Computadora básica:
Configuración de la computadora
  CPU: Intel Core 2 Dúo  
  RAM: 4GB  
  Almacenamiento: 256GB  
  GPU: No tiene GPU  

Computadora gamer
Configuración de la computadora
  CPU: Intel i9  
  RAM: 64GB  
  Almacenamiento: 1TB M2  
  GPU: Nvidia RTX 5090  
```

## Resources

- [Refactoring Guru - Design Patterns](https://refactoring.guru/design-patterns)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)
- [Node.js Documentation](https://nodejs.org/docs/)

## License

This project is MIT licensed.