# TypeScript Project

A simple TypeScript learning project demonstrating basic TypeScript syntax and features.

## Project Structure

```
├── src/
│   ├── index.ts          # Main entry point with greet function
│   ├── index.js          # Compiled JavaScript
│   └── index.d.ts        # TypeScript declaration file
├── hello.ts              # Additional TypeScript file with greet function
├── hello.js              # Compiled JavaScript
├── hello.d.ts            # TypeScript declaration file
├── package.json          # Project dependencies and metadata
├── tsconfig.json         # TypeScript compiler configuration
└── README.md             # This file
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (comes with Node.js)

### Installation

```bash
# Clone the repository
git clone https://github.com/satyapal49/Typescript.git

# Navigate to the project directory
cd Typescript

# Install dependencies
npm install
```

### Compiling TypeScript

```bash
# Compile TypeScript files
npx tsc
```

This will compile all `.ts` files to `.js` files according to the settings in `tsconfig.json`.

### Running the Code

```bash
# Run the main file
node src/index.js

# Run the hello file
node hello.js
```

## Features

- **Type Safety**: Examples of TypeScript type annotations
- **String Interpolation**: Using template literals with typed variables
- **Function Types**: Functions with parameter and return type declarations

## Code Examples

### src/index.ts
```typescript
function greet(name: string): string {
    return `Hello, ${name}!`;
}
```

### hello.ts
```typescript
function greet(person: string): string {
    return `Hello, ${person}, Lets learn TypeScript!`;
}
```

## Development

Edit the `.ts` files and run `npx tsc` to compile them to JavaScript.

## Repository

- Repository: [satyapal49/Typescript](https://github.com/satyapal49/Typescript)
- Issues: [GitHub Issues](https://github.com/satyapal49/Typescript/issues)

## License

ISC

## Author

Satyapal
