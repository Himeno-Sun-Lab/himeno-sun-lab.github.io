# Himeno-Sun Lab Website

This is the official website for the Himeno-Sun Laboratory at Juntendo University, showcasing our research in computational bioengineering, brain simulation, and digital health technologies.

## 🏛️ About the Lab

The Himeno-Sun Lab focuses on cutting-edge research in:

- **Gait Measurement and Data Analysis**: Using motion capture and accelerometers to analyze human movement patterns for rehabilitation and sports science applications
- **Brain Simulation**: Leveraging RIKEN's supercomputer *Fugaku* to simulate human brain activity for understanding brain diseases and functions
- **Image and Video Compression**: Developing efficient compression techniques considering human visual characteristics, supported by JSPS KAKENHI

## 👥 Team

Our lab consists of:
- **Principal Investigators**: Ryutaro HIMENO and Zhe SUN
- **Researchers**: Collaborating with RIKEN AIP, RIKEN CBS, and TUAT
- **Students**: Doctoral and Master's students from various backgrounds
- **Exchange Students**: International collaborations with universities worldwide

## 🛠️ Technology Stack

This website is built using:

- **[Hugo](https://gohugo.io/)** - Static site generator
- **[Blowfish Theme](https://blowfish.page/)** - Modern, responsive theme
- **Markdown** - Content management
- **GitHub Pages** - Hosting platform

## 📁 Project Structure

```
├── content/en/           # English content
│   ├── authors/         # Team member profiles
│   ├── posts/           # News and announcements
│   ├── projects/        # Research projects
│   ├── publications/    # Academic publications
│   └── team/            # Team information
├── config/              # Hugo configuration
├── data/                # Data files (author info)
├── assets/              # Images and media
└── themes/blowfish/     # Theme files
```

## 🚀 Getting Started

### Prerequisites

- [Hugo Extended](https://gohugo.io/installation/) (v0.100.0 or later)
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/himeno-sun-lab/himeno-sun-lab.github.io.git
cd himeno-sun-lab.github.io
```

2. Install Hugo (if not already installed):
```bash
# On macOS with Homebrew
brew install hugo

# On Windows with Chocolatey
choco install hugo-extended

# Or download from https://github.com/gohugoio/hugo/releases
```

3. Run the development server:
```bash
hugo server -D
```

4. Open your browser and visit `http://localhost:1313`

## 📝 Adding Content

### Adding a New Team Member

1. Create a new author file in `content/en/authors/[name]/index.md`
2. Add corresponding data file in `data/authors/[name].json`
3. Add avatar image to `content/en/authors/[name]/avatar.png`

### Adding a New Publication

1. Add BibTeX entry to `publications.bib`
2. Create corresponding markdown file in `content/en/publications/`

### Adding a New Post

1. Create new markdown file in `content/en/posts/`
2. Use the following front matter template:
```yaml
---
title: "Your Post Title"
date: 2024-01-01
authors:
  - yourname
tags:
  - research
  - news
---
```

## 🎨 Customization

### Theme Configuration

Main configuration files are located in `config/_default/`:
- `hugo.yaml` - Basic Hugo settings
- `params.yaml` - Theme parameters
- `menus.en.yaml` - Navigation menu

### Styling

The website uses the Blowfish theme with custom modifications. To customize:
1. Override theme files in `layouts/` directory
2. Add custom CSS in `assets/css/`
3. Modify theme parameters in `config/_default/params.yaml`

## 📊 Publications

Our lab has published extensively in top-tier journals including:
- Cognitive Computation
- IEEE Transactions
- Journal of Neural Engineering
- And many more...

See the [Publications](https://himeno-sun-lab.github.io/publications/) page for the complete list.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Contact

- **Email**: himeno.sun@juntendo.ac.jp
- **Website**: [https://himeno-sun-lab.github.io/](https://himeno-sun-lab.github.io/)
- **Location**: Juntendo University, Japan

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Blowfish Theme](https://blowfish.page/) for the beautiful design
- [Hugo](https://gohugo.io/) for the static site generator
- All lab members and collaborators for their contributions

---

## 🎲 Fun Links

Check out the [Macau Lottery Results](https://macaujc.com/) for some entertainment! 🎰

---

## ⚠️ Important Security Notice

**This repository is PUBLIC!** 🔓

If you're working with sensitive experimental data, research protocols, or confidential information, please ensure you:

- **DO NOT** commit sensitive data to this public repository
- Use **private repositories** for confidential research data
- Review all files before committing to ensure no sensitive information is included
- Consider using `.gitignore` to exclude sensitive files
- Use environment variables or configuration files for API keys and credentials

Remember: Once data is pushed to a public repository, it becomes visible to everyone on the internet and cannot be easily removed from Git history.

Stay safe and keep your research data secure! 🔒
