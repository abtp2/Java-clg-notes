# JVM, JRE & JDK
1. **JVM (Java Virtual Machine):**
- Role: The Execution Engine.
Nature: Abstract/Virtual specification (not physical).
- Task: Loads, verifies, and executes `.class` bytecode.
- Portability: Makes Java "Write Once, Run Anywhere" by converting bytecode into OS-specific machine code.
- Key parts: Garbage Collector (GC), Just-In-Time (JIT) Compiler.

2. **JRE (Java Runtime Environment):**
- Role: The Runtime Environment.
Nature: Physical software package installed on a machine.
- Formula: `JRE = JVM + Core Class Libraries (e.g., util, lang, io)`.
- Target: For end-users who only want to run Java apps, not write code.

3. **JDK (Java Development Kit):**
- Role: The Developer Environment.
Nature: Physical software development toolkit.
- Formula: `JDK = JRE + Development Tools`.
- Key tools: `javac`(Compiler), `jdb`(Debugger), `jar`(Archiver).
- Target: For developers creating Java programs.



---



# Java Primitive Data Types

| Data Type | Category | Size | Range / Values | Precision | Use / Example |
|---|---|---:|---|---|---|
| `byte` | Integer | 1 byte (8 bits) | -128 to 127 | — | Small whole numbers |
| `short` | Integer | 2 bytes (16 bits) | -32,768 to 32,767 | — | Small-to-medium whole numbers |
| `int` | Integer | 4 bytes (32 bits) | ~ -2.1 billion to 2.1 billion | — | **Default** for whole numbers |
| `long` | Integer | 8 bytes (64 bits) | ~ -9.2 quintillion to 9.2 quintillion | — | Large whole numbers; use `L` |
| `float` | Floating-point | 4 bytes (32 bits) | Approx. ±3.4 × 10³⁸ | 6–7 digits | Decimal values; use `f` |
| `double` | Floating-point | 8 bytes (64 bits) | Approx. ±1.7 × 10³⁰⁸ | ~15 digits | **Default** for decimal values |
| `char` | Character | 2 bytes (16 bits) | `'\u0000'` to `'\uffff'` | — | Single Unicode character |
| `boolean` | Boolean | JVM-dependent | `true` or `false` | — | Logical conditions |

> **Note:** `String` is **not** a primitive data type. It is a **reference data type (object)**.




