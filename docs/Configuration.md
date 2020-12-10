### mkdocs.yml

This is a default mkdocs.yml:

```

site_name: My Docs

```

You can get a list of your pages

```

cd repo.wiki.git
ls > pages.txt

```

Final result:

```
# Project information
site_name: 'MkDocs Material'
site_description: 'Documentation using MkDocs with the Material theme'
site_author: 'Anthony Blackham'
site_url: 'https://anthonyblackham.com/mkdocs-material'

# Repository
repo_name: 'mkdocs-material'
repo_url: 'https://github.com/anthonyblackham/mkdocs-material'
edit_uri: edit/main/docs/

# Copyright
copyright: 'Copyright &copy; 2020 Anthony Blackham'

# Configuration
theme:
  name: 'material'
  language: 'en'
  logo: 'icons/logo.svg'

# Customisation
extra:
  social:
    - icon: fontawesome/brands/github-alt
      link: 'https://github.com/anthonyblackham/mkdocs-material'

# Pages
nav:
- Home: index.md
- Installation: Installation.md
- Getting Started: Getting-Started.md
- Style Guide: Style-Guide.md
- Configuration: Configuration.md
- Deploy: Deploy.md
```
