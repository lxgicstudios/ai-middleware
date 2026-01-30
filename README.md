# ai-middleware

[![npm version](https://img.shields.io/npm/v/ai-middleware.svg)](https://www.npmjs.com/package/ai-middleware)
[![npm downloads](https://img.shields.io/npm/dm/ai-middleware.svg)](https://www.npmjs.com/package/ai-middleware)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-middleware)](https://github.com/lxgic-studios/ai-middleware/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Generate Express middleware from plain English descriptions. Rate limiting, auth, logging, whatever you need.

## Install

```bash
npm install -g ai-middleware
```

## Usage

```bash
npx ai-middleware "rate limit 100 req/min per IP"
npx ai-middleware "JWT auth with role-based access" -t
npx ai-middleware "request logging with response time" -o logger.ts -t
```

## Options

- `-t, --typescript` - Generate TypeScript
- `-o, --output <file>` - Write to file

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT
