# 📘 Golang Data Types

Go is a statically-typed language. Every variable has a specific type known at compile time. Understanding Go's data types is essential for writing correct and efficient programs.

---

## 📂 1. Categories of Data Types

1. **Basic Types**:
   - Numeric Types (Integers, Floats, Complex)
   - Boolean
   - String

2. **Composite Types**:
   - Array
   - Slice
   - Map
   - Struct
   - Pointer

3. **Function Type**

4. **Interface Type**

5. **Channel Type**

6. **Custom Types & Type Aliases**

---

## 🔢 2. Numeric Types

### Integers

| Type     | Size (bits) | Signed Range                 |
|----------|-------------|------------------------------|
| `int`    | 32/64        | Platform-dependent           |
| `int8`   | 8            | -128 to 127                  |
| `int16`  | 16           | -32,768 to 32,767            |
| `int32`  | 32           | -2.1B to 2.1B                |
| `int64`  | 64           | ±9 quintillion               |

### Unsigned Integers

| Type      | Size | Range         |
|-----------|------|---------------|
| `uint`    | 32/64| 0 to max      |
| `uint8`   | 8    | 0 to 255      |
| `uint16`  | 16   | 0 to 65,535   |
| `uint32`  | 32   | 0 to 4B       |
| `uint64`  | 64   | 0 to ~18 quintillion |

**Aliases**:
- `byte` = `uint8`
- `rune` = `int32` (used for Unicode)

### Floating Point

```go
var pi float64 = 3.14159
