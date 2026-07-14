# Larper AntiTamper

Larper AntiTamper is an open-source Lua anti-tamper and runtime integrity library designed to protect Lua applications from runtime modification, hooking, and execution environment manipulation.

## Features

* Runtime environment integrity verification
* Global environment consistency checks
* Function identity validation
* Metatable integrity protection
* Debug library detection
* Tamper response system
* Modular architecture
* Compatible with Lua 5.1+

## Project Structure

```
src/
    AntiTamper.lua
    Integrity.lua
    Environment.lua
    TrapTables.lua
    DebugChecks.lua
```

## Goals

This project provides a lightweight, extensible anti-tamper framework for Lua applications. The implementation is modular, allowing individual protection techniques to be enabled, disabled, modified, or extended to fit different projects and runtime environments.

## License

MIT License

Copyright (c) 2026 Larper

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, subject to the conditions of the MIT License.

See the `LICENSE` file for the full license text.
