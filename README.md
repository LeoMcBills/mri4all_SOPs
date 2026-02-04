# mri4all Standard Operating Procedures

Professional documentation for operating the low-field MRI system at MRI-Uganda.

## 🚀 Quick Start

### Prerequisites

Install MkDocs and required plugins:

```bash
pip install mkdocs-material
pip install mkdocs-git-revision-date-localized-plugin
```

### Preview Locally

Run the development server:

```bash
mkdocs serve
```

Then open your browser to `http://127.0.0.1:8000`

### Build for Production

Generate static site files:

```bash
mkdocs build
```

The site will be created in the `site/` directory.

## 📚 Features

- ✨ **Modern Material Design** - Clean, professional look
- 🎨 **Light/Dark Mode** - Automatic theme switching
- 🔍 **Smart Search** - Fast, fuzzy search with suggestions
- 📱 **Fully Responsive** - Works perfectly on all devices
- 🎯 **Code Copy Buttons** - Easy code snippet copying
- 🖼️ **Image Zoom** - Click to enlarge images
- ⌨️ **Keyboard Shortcuts** - Quick navigation
- 📊 **Progress Indicator** - Track reading progress
- 🏷️ **Rich Admonitions** - Info boxes, warnings, tips

## 🎨 Customization

Edit the following files to customize:

- `mkdocs.yml` - Site configuration, theme, colors
- `docs/stylesheets/extra.css` - Custom styling
- `docs/javascripts/extra.js` - Custom interactions
- `docs/index.md` - Main content

## 📖 Documentation Structure

```
docs/
├── index.md              # Main SOP guide
├── stylesheets/
│   └── extra.css        # Custom styles
├── javascripts/
│   └── extra.js         # Custom scripts
└── images/              # Screenshots and diagrams
```

## 🛠️ Development

### Adding New Pages

1. Create a new `.md` file in the `docs/` directory
2. Add it to the `nav` section in `mkdocs.yml`

### Updating Content

Edit the markdown files in the `docs/` directory. Changes will auto-reload in dev mode.

## 📝 License

See [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions welcome! Please open an issue or submit a pull request.

## 📧 Contact

For questions or support, contact the MRI-Uganda team.

---

**Made with ❤️ by the MRI-Uganda Team**
