# Katzen Webseite

## Pinterest auf Homepage anpassen:

In `params.toml` musst du den Teil anpassen:

```toml
[home.pinterest]
enable = true
user = "ilona_brandt"
board = "katzen"
```

## Neue Katze:

1. In `content/posts` gehen
2. Einen bestehenden Artikel kopieren
3. Oben die Infos zur neuen Katze und Kontaktdaten anpassen
4. Text auf der Seite ändern
5. In `static/` einen neuen Ornder mit Namen der Katze anlegen (siehe Justus)
6. 3 Bilder im Format `NAME.jpg`, `NAME_2.jpg`, `NAME_3.jpg` hochladen

## Ändern der Farben:

`themes/FixIt/assets/css/_variables.scss`

#### Menüleiste:

```scss
// ========== Header ========== //
// Height of the header
$header-height: 3.5rem !default;

// Color of the header background
$header-background-color: #f8f8f8 !default;
$header-background-color-dark: #252627 !default;

// Font style of the header title
$header-title-font-family: $global-font-family !default;
$header-title-font-size: 1.5rem !default;

// Color of the active menu item
$menu-active-color: #161209 !default;
$menu-active-color-dark: #fff !default;

// Color of the search background
$search-background-color: #e9e9e9 !default;
$search-background-color-dark: #363636 !default;
// ========== Header ========== //
```

#### Hintergrund:

```scss
// ========== Global ========== //
// Prefix for :root CSS variables.
$prefix: fi- !default;

// Font and Line Height
$global-font-family: system-ui, -apple-system, BlinkMacSystemFont, PingFang SC,
  Microsoft YaHei UI, Segoe UI, Roboto, Oxygen, Ubuntu, Cantarell, Fira Sans, Droid
    Sans, Helvetica Neue, Helvetica, Arial, sans-serif !default;
$global-font-size: 16px !default;
$global-font-weight: 400 !default;
$global-line-height: 1.5rem !default;

// scroll-margin-top of content anchor
$global-scroll-margin-top: 0.5rem;

// Radius of the border
$global-border-radius: 5px !default;

// Color of the background
$global-background-color: #ffffff !default;
$global-background-color-dark: #292a2e !default;

// Color of the text
$global-font-color: #161209 !default;
$global-font-color-dark: #b1b1ba !default;

// Color of the secondary text
$global-font-secondary-color: #b1b1ba !default;
$global-font-secondary-color-dark: #909092 !default;

// Color of the link
$global-link-color: #161209 !default;
$global-link-color-dark: #b1b1ba !default;

// Color of the hover link
$global-link-hover-color: #2983bb !default;
$global-link-hover-color-dark: #fff !default;

// Color of the border
$global-border-color: #f0f0f0 !default;
$global-border-color-dark: #363636 !default;
// ========== Global ========== //
```
