# Angular_Concepts
In This Page we can see Important commands ,configuration about Angular and problems and its solutions


Problem1:
import { Customer2 } from "./Customer2";

^^^^^^



SyntaxError: Cannot use import statement outside a module

    at Object.compileFunction (node:vm:352:18)

    at wrapSafe (node:internal/modules/cjs/loader:1026:15)

    at Module._compile (node:internal/modules/cjs/loader:1061:27)

    at Object.Module._extensions..js (node:internal/modules/cjs/loader:1149:10)

    at Module.load (node:internal/modules/cjs/loader:975:32)

    at Function.Module._load (node:internal/modules/cjs/loader:822:12)

    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:81:12)

    at node:internal/main/run_main_module:17:47



Node.js v17.3.0

**Solution:**
          We Can install node 16...version to resolve this issue:
          https://nodejs.org/download/release/latest-gallium/
          For windows 64 bit download this file: node-v16.13.2-x64.msi 
