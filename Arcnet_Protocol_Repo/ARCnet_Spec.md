# ARCnet Protocol Specification

## Overview
ARCnet is a symbolic language designed to serve as a control, identity, and behavioral interface between users and AI agents. It is fully typeable using a standard QWERTY keyboard and works across different large language models.

## Core Symbols

| Symbol | Meaning |
|--------|---------|
| @><    | Full memory/context reactivation |
| !!     | Priority/urgent input |
| //     | Directive or functional action |
| ::     | Context or block scope |
| ~~     | Speculative or creative request |
| :::    | Encapsulation of structured data |

## Design Rules
- Symbols must retain consistent meaning across AIs.
- Identity tokens (e.g., `T$`) should remain stable.
- AI should reprocess earlier content if @>< is used after a delay.

