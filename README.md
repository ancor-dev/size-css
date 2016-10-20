# Size-CSS
Helpful classes for make margin, padding, font-size and some other styles

## Installation:
TODO:

## Documentationj:

### Sizes

**Default sizes:**

    xs: 10px // extra small
    sm: 15px // small
      : 20px // default
    md: 25px // middle
    lg: 30px // large
    el: 40px // extra large

**Vertical offsets:**

- .offset-xs
- .offset-sm
- .offset
- .offset-md
- .offset-lg
- .offset-el

**Horizontal offsets:**

- .offset-xs-h
- .offset-sm-h
- .offset-h
- .offset-md-h
- .offset-lg-h
- .offset-el-h

**Offset for one side:**

- .offset-xs-(top|bottom|left|right)
- .offset-sm-(top|bottom|left|right)
- .offset-(top|bottom|left|right)
- .offset-md-(top|bottom|left|right)
- .offset-lg-(top|bottom|left|right)
- .offset-el-(top|bottom|left|right)

**If you want to remove offset specify prefix `no-`:**

- .no-offset
- .no-offset-h
- .no-offset-(top|bottom|left|right)

**Useing padding**

For use `padding` instead of `margin` just write `inset` instead of `offset`.  
Examples:

- .inset-sm
- .inset
- .inset-h
- .inset-md-h
- .inset-xs-top
- .no-inset-h
- .no-inset-top

### Font-sizes
Default sizes: fromm 8px to 40px with 2px step

- .fz-8
- .fz-10
- .fz-12
- .fz-...
- .fz-40

## Make a build

Requirements:

- Nodejs v6.0+ with npm

Do the steps:

1. Clone the repository `git clone https://github.com/ancor-dev/size-css.git`
2. Go to repository directory `cd size-css`
3. Install node-js dependencies `npm install`
4. Make a build `npm run css`
