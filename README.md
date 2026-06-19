<p align="center">
  <img src="https://github.com/kotarimorm/kotarimorm/blob/main/assets/GW_bunner.png" width="100%">
</p>

<h1 align="center">GRAY_WHALE_CO</h1>

<p align="center">
  <b>Systems programming · OSDev · compilers · low-level tooling</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OSDev-000000?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Compilers-111111?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/NASM-000000?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Python-111111?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Systems-000000?style=for-the-badge"/>
</p>

---

```txt
I build tools close to the machine.

No fake magic.
No unnecessary abstraction.
No comfort layer hiding the hardware.

If something breaks, I want to know why.
```

---

## Active Work

<p align="center">
  <a href="https://github.com/kotarimorm/SENTINEL_LANG">
    <img src="https://github.com/kotarimorm/kotarimorm/blob/main/assets/cards/sentinel.svg" width="49%">
  </a>
  <a href="https://github.com/kotarimorm/tech_teach_OS-BETA-">
    <img src="https://github.com/kotarimorm/kotarimorm/blob/main/assets/cards/tech_teach_os.svg" width="49%">
  </a>
</p>

| Project | Status | Focus |
|---|---|---|
| [`SENTINEL_LANG`](https://github.com/kotarimorm/SENTINEL_LANG) | `v0.2-alpha` | experimental low-level language compiling to NASM |
| [`tech_teach_OS`](https://github.com/kotarimorm/tech_teach_OS-BETA-) | `BETA` | OSDev reference stand for low-level kernel work |
| `GRAY_WHALE_CO` | active | systems tooling, research, experiments |

---

## Operating Area

| Area | Focus |
|---|---|
| **OSDev** | GDT, IDT, PIC, ISR, paging, VGA, PS/2, ATA, PCI |
| **Compilers** | lexer, parser, AST, codegen, NASM output |
| **Assembly** | x86 / x64 low-level experiments |
| **Low-Level Tools** | debugging helpers, reference snippets, hardware experiments |
| **Systems Research** | kernels, drivers, memory, interrupts, execution flow |
| **Graphics / Rendering** | visual systems, rendering experiments, tooling |

---

## SENTINEL_LANG

Experimental systems language focused on OSDev and low-level code generation.

```text
.sl source
    │
    ▼
Lexer / Parser / AST
    │
    ▼
NASM Assembly
    │
    ▼
Flat Binary
```

Current focus:

- x64 compiler pipeline
- NASM code generation
- function system
- arrays and indexing
- low-code byte emission
- future OSDev standard libraries

---

## tech_teach_OS

Reference stand for low-level operating system development.

```text
GDT / IDT / PIC / ISR / PIT / Paging
VGA / PS/2 / ATA / PCI / PMM / Panic / Debug
```

Purpose:

> When your kernel explodes at 3 AM, open the reference and find the missing piece.

---

## Engineering Style

```text
Read the failure.
Trace the state.
Find the broken assumption.
Fix the root cause.
Document the result.
```

---

## Direction

```text
1. Build low-level references.
2. Build the compiler.
3. Build OSDev libraries.
4. Build a demo kernel.
5. Push toward larger systems.
```

---

## Philosophy

| Principle | Meaning |
|---|---|
| **Control** | understand what the machine is doing |
| **Clarity** | generated output should make sense |
| **Minimalism** | no useless layers |
| **Debuggability** | every failure should teach something |
| **Performance** | low-level work should stay close to hardware |

---

## Signal

```text
BLACK / WHITE
RAW / CONTROLLED
LOW-LEVEL / READABLE
BROKEN / DEBUGGED
```

---

## Status

```text
building systems
breaking compilers
debugging kernels
documenting the machine
```
