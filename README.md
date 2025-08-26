# CCUX — AI-Powered Website Generator

Generate professional landing pages and complete websites from your terminal using Claude AI.

## What CCUX Does

CCUX transforms your product description into conversion-optimized websites through professional UX design methodology. Simply describe your product, and get production-ready HTML or React components in minutes.

## Installation

```bash
pip install ccux
```

**Prerequisites:** Claude CLI and Python 3.9+. Get Claude CLI from [claude.ai/code](https://claude.ai/code).

## Getting Started

### Interactive Mode (Recommended)

```bash
ccux init
```

The interactive terminal app provides:
- Guided website creation wizard
- Visual project management 
- Live section editing and theme switching
- Multi-page website generation
- Form management and customization
- Press ESC anytime to exit

### Command Line Usage

```bash
# Generate single landing page
ccux gen --desc "AI project management tool" --theme minimal

# Generate complete multi-page website
ccux multipage --desc "SaaS platform for remote teams"

# Regenerate specific sections
ccux regen --section hero,pricing

# Load description from file
ccux gen --desc-file product.pdf --theme brutalist
```

## Commands

| Command | Description |
|---------|-------------|
| `ccux init` | **Interactive app** - Guided website creation |
| `ccux gen` | Generate single landing page |
| `ccux multipage` | Generate complete multi-page website |
| `ccux regen` | Update specific sections of existing pages |
| `ccux projects` | List existing projects |
| `ccux cost` | Show token usage and costs |
| `ccux help` | Get detailed help for any topic |

## What You Get

**Professional Quality Output:**
- Production-ready HTML or React components
- Mobile-responsive design with TailwindCSS
- SEO optimization and accessibility features
- Clean, semantic code structure

**AI Design Process:**
- Automatic competitor analysis and research
- Professional UX methodology (12-phase process)
- User personas and conversion optimization
- Strategic copywriting and visual design

**13 Design Themes:**
From minimal and corporate to brutalist, animated, and illustrated styles.

## Examples

**Single Page:**
```bash
ccux gen --desc "AI-powered project management tool for remote teams"
```

**Multi-Page Website:**
```bash
ccux multipage --desc "SaaS platform with features, pricing, and about pages"
```

**Edit Existing:**
```bash
ccux regen --section hero,pricing
```

## View Your Pages

```bash
cd output/
python -m http.server 3000
# Open http://localhost:3000
```

## Links

- **PyPI:** [pypi.org/project/ccux](https://pypi.org/project/ccux/)
- **Claude CLI:** [claude.ai/code](https://claude.ai/code)
- **Help:** Run `ccux help` for detailed documentation