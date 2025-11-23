# Justin Napolitano Personal Website

This repository hosts the source code and content for my personal website, built primarily with Python and Sphinx documentation tools. It serves as a portfolio and project showcase platform.

## Features

- Static website generation using Sphinx
- Documentation and blog content management
- Integration with modern static site tools

## Tech Stack

- Python
- Sphinx documentation generator
- Makefile and batch scripts for build automation
- Docker (assumed for some project components based on content)

## Getting Started

### Prerequisites

- Python 3.x
- Sphinx (`pip install sphinx`)
- Make (or use `make.bat` on Windows)

### Installation and Build

Clone the repository:

```bash
git clone https://github.com/justin-napolitano/justin-napolitano.github.io.git
cd justin-napolitano.github.io
```

Build the documentation:

```bash
make html
```

On Windows, use:

```bat
make.bat html
```

The built site will be available in the `docs` directory.

## Project Structure

```
justin-napolitano.github.io/
├── content/          # Content files such as blog posts
├── docs/             # Built documentation output
├── source/           # Sphinx source files and configuration
├── Makefile          # Makefile for building the site
├── make.bat          # Windows batch file for build automation
├── README.md         # This file
```

## Future Work / Roadmap

- Expand content with more blog posts and projects
- Improve site styling and responsiveness
- Automate deployment to GitHub Pages
- Add more interactivity or dynamic content if needed

---

This site is a work in progress and serves as a personal portfolio and documentation hub.