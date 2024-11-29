# Jacob's House Sober Living Program

Welcome to the Jacob's House repository. This project is dedicated to supporting individuals in recovery by providing a structured, supportive environment that fosters personal growth and community reintegration.

## Table of Contents

- [Jacob's House Sober Living Program](#jacobs-house-sober-living-program)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
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
   git clone https://github.com/dev3l/jacobs-house.git
   cd jacobs-house
   ```

2. **Install Hatch**:
   Ensure you have Hatch installed. You can install it via pip if it's not already installed:

   ```bash
   pip install hatch
   ```

3. **Create and activate the virtual environment**:

   ```bash
   hatch env create
   hatch shell
   ```

## Usage

To preview the site locally, use the following command:

```bash
mkdocs serve
```

Access the site at `http://127.0.0.1:8000`.

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
