# Steps to reproduce

- Note `$size-2: 100px` definition in `input.sass`
- Compile SASS (`sass input.sass output.css`)
- Open `index.html`
- Both `is-2` and `is-size-2` elements render at default size instead of `100px`
