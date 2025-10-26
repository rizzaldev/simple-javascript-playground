# JavaScript Playground

A lightweight, browser-based JavaScript code editor and execution environment that allows you to write and run JavaScript code in real-time.

## Features

- 💻 Clean, modern code editor interface
- ⚡ Instant code execution
- 🔒 Sandboxed code execution environment
- 📝 Console output simulation (log, error, warn, info)
- 💾 In-memory code persistence
- ⌨️ Keyboard shortcuts support
- 📱 Responsive design for all devices

## Usage

1. Open `index.html` in your web browser
2. Write your JavaScript code in the editor
3. Click "Run Code" or press `Ctrl/Cmd + Enter` to execute
4. View the output in the bottom panel

## Keyboard Shortcuts

- `Ctrl/Cmd + Enter`: Run code
- `Tab`: Insert 2 spaces for indentation

## Output Types

The playground supports different types of console outputs:

- Regular logs (`console.log`)
- Errors (`console.error`)
- Warnings (`console.warn`)
- Info messages (`console.info`)
- Success messages (on successful code execution)

## Security

Code execution is sandboxed within an iframe to prevent access to the parent window context and ensure safe execution of user-provided code.

## Browser Compatibility

Compatible with modern browsers including:

- Chrome
- Firefox
- Safari
- Edge

## Local Development

Simply clone the repository and open `index.html` in your browser - no build process or dependencies required!

```bash
git clone <repository-url>
cd javascript-playground
```

## License

MIT License
