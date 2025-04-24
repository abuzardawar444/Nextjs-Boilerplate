# Types Directory

The `types` directory is used to store TypeScript type definitions and interfaces. It helps in maintaining a clean and organized codebase by centralizing type definitions, making them reusable and easier to manage.

## Purpose

- Define shared types and interfaces used across the project.
- Improve code readability and maintainability.
- Ensure type safety in the application.

## Example

```typescript
// types/user.ts
export interface User {
  id: string;
  name: string;
  email: string;
}
```

## Usage

Import the types wherever needed in your project:

```typescript
import { User } from "../types/user";

const getUser = (user: User) => {
  console.log(user.name);
};
```
