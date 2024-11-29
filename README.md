# Jacob's House Sober Living Program

Welcome to the Jacob's House repository. This project is dedicated to supporting individuals in recovery by providing a structured, supportive environment that fosters personal growth and community reintegration.

## Table of Contents

- [Jacob's House Sober Living Program](#jacobs-house-sober-living-program)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Directory Structure](#directory-structure)
  - [Customization](#customization)
  - [Deployment](#deployment)
  - [Contributing](#contributing)
  - [License](#license)

## Project Overview

Jacob's House is a structured sober living program that provides a safe, supportive, and accountable environment for individuals overcoming addiction. Our tiered housing model and community-focused initiatives empower residents to rebuild their lives and successfully reintegrate into society.

## Features

- **Three-Tier Housing Model**: Transition Housing, Sober Living, and Advanced Living options to support various stages of recovery.
- **Employment Opportunities**: Partnerships with local businesses to provide job training and employment.
- **Community Engagement**: Active participation in local events and collaborations with community organizations.
- **Structured Support**: Clear rules and accountability measures to maintain a safe and supportive environment.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/jacobs-house.git
   cd jacobs-house
   ```

2. **Install dependencies**:
   Ensure you have Python 3.13.0+ installed, then run:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

To preview the site locally, use the following command:

```bash
mkdocs serve
```

Access the site at `http://127.0.0.1:8000`.

## Directory Structure

The project is organized as follows:

```
jacobs-house/
├── docs/
│   ├── index.md
│   ├── about.md
│   ├── programs/
│   │   ├── transition-housing.md
│   │   ├── sober-living.md
│   │   └── advanced-living.md
│   ├── impact/
│   │   ├── success-stories.md
│   │   └── community-benefits.md
│   ├── challenges.md
│   ├── expansion.md
│   └── contact.md
├── images/
│   ├── logo.png
│   ├── favicon.ico
│   └── banner.jpg
├── stylesheets/
│   └── extra.css
└── mkdocs.yml
```

## Customization

- **Theme Configuration**: Modify `mkdocs.yml` to change the theme settings, including colors and fonts.
- **CSS Styling**: Add custom styles in `stylesheets/extra.css` to enhance the site's appearance.

## Deployment

To deploy the site to GitHub Pages, run:

```bash
mkdocs gh-deploy
```

Ensure your repository is linked to a GitHub account and has GitHub Pages enabled.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
