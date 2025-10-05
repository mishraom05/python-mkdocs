# Project Documentation

This repository uses [MkDocs](https://www.mkdocs.org/) with the Material theme for managing project documentation.

## Getting Started

### 1. Clone the Repository

```sh
git clone https://github.com/your-username/python-mkdocs.git
cd python-mkdocs/project-doc
```

### 2. Install Dependencies

Make sure you have Python installed. Then, install the required packages:

```sh
pip install -r requirements.txt
```

### 3. Serve Documentation Locally

Start the MkDocs development server:

```sh
mkdocs serve
```

Open [http://localhost:8000](http://localhost:8000) in your browser to view the documentation.

## Project Structure

- `docs/` — Markdown files for documentation
- `docs/img/favicon.ico` — Favicon for the site
- `mkdocs.yml` — MkDocs configuration file
- `requirements.txt` — Python dependencies

## Customization

- Navigation and theme are configured in `mkdocs.yml`.
- Favicon is set via `extra: favicon: img/favicon.ico`.

### mkdocs.yml Configuration Details

```yaml
site_name: Project Documentation
nav:
  - Home: index.md
  - About: about.md
theme: material
extra:
  favicon: img/favicon.ico
```

- **site_name**: Sets the site title.
- **nav**: Defines navigation structure (Home and About pages).
- **theme**: Uses the Material theme for MkDocs.
- **extra > favicon**: Specifies the favicon location
