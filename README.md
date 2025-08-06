# Pixi Show and Tell Demo

A demonstration repository showcasing [Pixi](https://pixi.sh/), a modern package management tool that simplifies Python project setup and dependency management.

## What is Pixi?

Pixi is a package management tool for Python that:

- Uses Conda and PyPI packages
- Provides fast, reliable dependency resolution
- Creates isolated environments automatically
- Works cross-platform (Windows, macOS, Linux)
- Uses a single `pixi.toml` configuration file or be integrated with existing `pyproject.toml` files

## Features Demonstrated

This demo repository showcases:

- 🚀 **Fast Setup**: One-command project initialization
- 📦 **Dependency Management**: Easy package installation and updates
- 🔒 **Environment Isolation**: Automatic virtual environment creation
- 🔄 **Reproducible Builds**: Lock files ensure consistent environments
- 🛠️ **Task Runner**: Built-in task execution system
- 🌍 **Cross-Platform**: Works seamlessly across operating systems

## Quick Start

### Prerequisites

- Install Pixi: `curl -fsSL https://pixi.sh/install.sh | bash`
- Restart your terminal or run `source ~/.bashrc` (Linux) / `source ~/.zshrc` (macOS)

### Getting Started

```bash
# Clone this repository
git clone https://github.com/lsetiawan/pixi-demo.git
cd pixi-demo

# Install dependencies and activate environment
pixi install

# Start a shell in the pixi environment
pixi shell
```

## Common Pixi Commands

```bash
# Initialize a new Pixi project
pixi init

# Add a new dependency
pixi add numpy pandas matplotlib

# Add development dependencies
pixi add --feature dev pytest black flake8

# Remove a package
pixi remove package-name

# Update all packages
pixi update

# Run a specific task
pixi run <task-name>

# List all available tasks
pixi task list

# Show project information
pixi info
```

## Benefits Over Traditional Tools

| Feature | Pixi | pip + venv | conda |
|---------|------|------------|-------|
| Setup Speed | ⚡ Fast | 🐌 Slow | 🐌 Slow |
| Dependency Resolution | ✅ Robust | ❌ Limited | ✅ Good |
| Cross-platform | ✅ Yes | ⚠️ Varies | ✅ Yes |
| Lock Files | ✅ Built-in | ❌ Manual | ❌ Manual |
| Task Runner | ✅ Built-in | ❌ No | ❌ No |

## Use Cases

Perfect for:

- 🔬 **Data Science Projects**: Easy access to scientific Python packages
- 🌐 **Web Development**: Quick setup for Django, Flask, FastAPI projects
- 🤖 **Machine Learning**: Simple installation of ML frameworks
- 📊 **Research**: Reproducible computational environments
- 👥 **Team Collaboration**: Consistent environments across team members

## Resources

- 📖 [Pixi Documentation](https://pixi.sh/latest/)
- 🐙 [Pixi GitHub Repository](https://github.com/prefix-dev/pixi)
- 📦 [conda-forge Packages](https://conda-forge.org/)

## License

This project is licensed under the BSD-3 License - see the [LICENSE](LICENSE) file for details.

---

*This demo was created for the SSEC Pixi Show and Tell presentation on August 6, 2025.*
