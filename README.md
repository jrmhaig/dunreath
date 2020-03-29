## Page body

The main page body text is added in the `*.md` file below the header section
as paragraphs separated by one or more empty lines. A title is added as

```
{:.title}
# Main title

{:.subtitle}
## A subtitle
```

## Navigation bar

The navigation bar is configures in `_config.yml` as:

```yml
navbar:
  - text: This is a single item
    link: page-for-single-item
  - text: This has a submenu
    submenu:
      - text: This is the first submenu item
        link: first-submenu-item
      - text: This is the second submenu item
        link: second-submenu-item
  - text: This is an external link
    link: https://www.google.co.uk
```
