# Responsive-SCSS-Mixins
A set of mixins to help with creating responsive designs in SCSS. It's a cheat sheet or boilerplate that I use when developing themes.

## Usage
The mixins are defined for different screen sizes:
- `small-screen`: for screens equal to or larger than 576px
- `medium-screen`: for screens equal to or larger than 768px
- `large-screen`: for screens equal to or larger than 992px
- `extra-large-screen`: for screens equal to or larger than 1200px

You can use these mixins in your stylesheet by adding them to the selectors that you want to apply the media queries to.
```scss
.selector {
    /* styles for small screens */
    @include small-screen {
        /* additional styles for small screens and up */
    }
    @include medium-screen {
        /* additional styles for medium screens and up */
    }
    @include large-screen {
        /* additional styles for large screens and up */
    }
    @include extra-large-screen {
        /* additional styles for extra large screens */
    }
}
```
You can adjust the breakpoints in the `media-queries.scss` file, in the variables section.

## Installation

1. Download or clone the repository.
2. Import the `media-queries.scss` file into your main SCSS file.

## Note

This is a simple example and you can modify it accordingly to your needs.
