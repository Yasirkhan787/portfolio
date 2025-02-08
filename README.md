# Java Access Modifiers

Access modifiers in Java define the scope and accessibility of classes, methods, and variables. There are four types of access modifiers:

- **Private**
- **Default (Package-Private)**
- **Protected**
- **Public**

## Access Control Table

| Modifier      | Same Class  | Same Package (Subclass) | Same Package (Non-Subclass) | Different Package (Subclass)  | Different Package (Non-Subclass) |
|---------------|-------------|-------------------------|---------------------------- |-------------------------------|----------------------------------|
| **Private**   | ✅ Yes     | ❌ No                   | ❌ No                      | ❌ No                         | ❌ No                            |
| **Default**   | ✅ Yes     | ✅ Yes                  | ✅ Yes                     | ❌ No                         | ❌ No                            |
| **Protected** | ✅ Yes     | ✅ Yes                  | ✅ Yes                     | ✅ Yes                        | ❌ No                            |
| **Public**    | ✅ Yes     | ✅ Yes                  | ✅ Yes                     | ✅ Yes                        | ✅ Yes                           |

## Explanation of Access Modifiers

### 1. Private
- Accessible only within the same class.
- Not accessible from subclasses or other classes.

### 2. Default (Package-Private)
- Accessible within the same package.
- Cannot be accessed outside the package, even by subclasses.
  
### 3. Protected
- Accessible within the same package.
- Also accessible in subclasses, even if they are in different packages.

### 4. Public
- Accessible from anywhere in the program.

## Summary
- Use **private** for strict encapsulation.
- Use **default** when you want access within the same package.
- Use **protected** when subclass access is needed even outside the package.
- Use **public** for unrestricted access.

### ⭐ Hope this helps you understand Java Access Modifiers! Happy Coding! 😊

