# Project information

site_name: Regelgeving
site_author: 'Leiden Roleplay'
site_url: 'https://itzlucqzzzz.github.io/'
use_directory_urls: false

# Copyright
copyright: Copyright &copy; 2025. Leiden Roleplay

# Configuration
theme:
  name: material
  features:
    # - Navigation.tabs
  palette:
    - scheme: default
      toggle:
        icon: material/toggle-switch-off-outline
        name: Switch to dark mode
    - scheme: slate
      toggle:
        icon: material/toggle-switch
        name: Switch to light mode
  language: nl
plugins:
  - search:
      lang: nl
markdown_extensions:
  - admonition
  - attr_list
  - pymdownx.highlight
  - pymdownx.superfences
extra_javascript:
  - https://cdnjs.cloudflare.com/ajax/libs/tablesort/5.2.1/tablesort.min.js
  - javascripts/tables.js
nav:
  - Hoofdpagina: index.md
  - Informatie: informatie.md
  - Regels: algemeen.md
  - Straffen: straffen.md
