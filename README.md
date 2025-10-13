#  **typelint**

a minimal static analyzer for Lua 5.4

---

### quickstart

```bash
typelint check src/
```

catches type errors during development. LSP compatible.

### highlights

* type inference
* inline annotations `---@type string`
* config file `.typelintrc`
* zero dependencies

```lua
---@type number
local x = "oops" -- error
```

MIT • [typelint.io](https://typelint.io)
