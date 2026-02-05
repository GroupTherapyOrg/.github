# Group Therapy

**Native Julia. WasmGC. No glue code.**

We are building the infrastructure to run Julia natively in the browser without a heavy runtime. This is an active R&D ecosystem targeting the WebAssembly Garbage Collection (WasmGC) proposal.

### The Stack

* **[WasmTarget.jl](https://github.com/GroupTherapyOrg/WasmTarget.jl)**
    * *The Compiler.* Compiles Julia functions directly to WebAssembly binaries using WasmGC.

* **[Therapy.jl](https://github.com/GroupTherapyOrg/Therapy.jl)**
    * *The Framework.* A fine-grained reactive web framework inspired by Leptos and SolidJS.

* **[Sessions.jl](https://github.com/GroupTherapyOrg/Sessions.jl)**
    * *The IDE (Planned).* A Pluto-inspired, Wasm-capable hybrid notebook and environment built entirely in Therapy.jl.
 
* **[Suite.jl](https://github.com/GroupTherapyOrg/Suite.jl) [TODO]**
    * *The Components.* A composable UI component library for Therapy.jl — unstyled primitives and styled defaults, inspired by Radix and shadcn/ui. Use programmatically or extract into your project.

---

> [!NOTE]
> **Status: Experimental.**
> These repositories are currently in pre-alpha development.
