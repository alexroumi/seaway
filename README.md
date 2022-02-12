markdown: kramdown

<link rel="stylesheet" href="seaway.css">

# Seaway CSS v0.1.0

Custom CSS framework made for https://www.marinabookings.gr/

## Installation

1. Download the `Seaway` [css](./seaway.css) file
1. Add the following to your html <head>

```html
<link rel="stylesheet" href="seaway.css" />
```

## CSS Class Reference

#### Banners

| Parameters           | Type        |
| :------------------- | :---------- |
| `banner danger`      | danger      |
| `banner information` | information |

Sample

```html
<div class="banner danger">
  <div class="banner_title">Title</div>
  <div class="banner_content">main content</div>
</div>
```

Output

<div class="banner danger" style=" border-radius: var(--main_radius);
    padding: var(--padding_banner);
    margin: 10px 5px;">
    <div class="banner_title" style="font-size: var(--banner_title_size);">Title</div>
    <div class="banner_content" style="font-weight: normal;">main content</div>
</div>

#### Pills

| Parameters          | Type        |
| :------------------ | :---------- |
| `badge danger`      | danger      |
| `badge information` | information |
| `badge warning`     | warning     |

Sample

```html
<div class="badge danger">danger</div>
<div class="badge information">info</div>
<div class="badge warning">warning</div>
```

Output

<div class="badge danger">danger</div>
<div class="badge information">info</div>
<div class="badge warning">warning</div>
