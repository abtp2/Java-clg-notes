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





