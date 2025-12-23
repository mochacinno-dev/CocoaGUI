# Welcome to Graphica

**The simplest Python GUI library ever created.**

Graphica makes building desktop applications incredibly easy. No complex setup, no confusing APIs - just clean, intuitive Python code that anyone can understand.

## Why Graphica?

✨ **Simple Syntax** - Create widgets in one line with intuitive parameters

🚀 **Fast Development** - Build complete applications in minutes, not hours

📚 **Easy to Learn** - If you know basic Python, you already know Graphica

🎨 **Clean Code** - Your GUI code is readable and maintainable

## Quick Example

```python
import Graphica as gui

# Create a window
app = gui.Window("My App", width=400, height=300)

# Add widgets
gui.Label(app, "Enter your name:", x=20, y=20)
name_input = gui.Input(app, x=20, y=50, width=300)

def greet():
    name = name_input.get()
    gui.alert(f"Hello, {name}!")

gui.Button(app, "Greet", command=greet, x=20, y=90)

# Run the app
app.run()
```

That's it! Just 13 lines to create a working GUI application.

## Key Features

- **Window** - Create application windows with custom sizes
- **Button** - Interactive buttons with click handlers
- **Label** - Display text with customizable sizes
- **Input** - Single-line text input fields
- **TextArea** - Multi-line text editing
- **CheckBox** - Toggle checkboxes with state management
- **Utilities** - Alert and confirmation dialogs

## Get Started

Ready to build something amazing? Head over to the [Installation Guide](getting-started/installation.md) to get started!

## Philosophy

Graphica was designed with one goal: **make GUI development as simple as possible**. We believe that:

- GUI code should be readable like a story
- Creating interfaces shouldn't require mastering complex frameworks
- Simple tasks should require simple code
- Python beginners should be able to build real applications

## Community

Found a bug? Have a feature request? Want to contribute?

- Report issues on [GitHub Issues](https://github.com/yourusername/graphica/issues)
- Contribute on [GitHub](https://github.com/yourusername/graphica)
- Share your projects with the community!

---

*Built with ❤️ for Python developers everywhere*