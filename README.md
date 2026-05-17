# DeepSeek Browser Agent

AI coding agent powered by DeepSeek via browser automation — no API key needed.

## Features

- Batch mode for running multiple stock analysis tasks
- Full agent loop with tool calls support
- Real-time timing logging for troubleshooting
- Support for stock code/name replacement

## Usage

```bash
# Run batch mode with stock analysis
npx deepseek-browser-agent --batch tasks.json --stock 300608思特奇
```

## Batch Mode Format

Create a JSON file with an array of tasks:

```json
{
  "tasks": [
    "请用一句话概括{STOCK_CODE}{STOCK_NAME}这家公司的核心商业模式...",
    "请列出这家公司在行业中的前三大竞争对手..."
  ]
}
```
