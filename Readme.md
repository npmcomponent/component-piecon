*This repository is a mirror of the [component](http://component.io) module [component/piecon](http://github.com/component/piecon). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-piecon`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# piecon

  Pie charts for [component/favicon](https://github.com/component/favicon)
  inspired by the original [piecon](https://github.com/lipka/piecon). Styled
  with CSS!

  ![js pie favicons](http://f.cl.ly/items/3T2g1b2w1j2t3e3A1Y3r/Screen%20Shot%202012-09-20%20at%2012.55.50%20PM.png)

## Installation

    $ component install component/piecon

## Styling

  Piecon utilizes [component/style](https://github.com/component/style)
  to enable CSS styling for Canvas rasters. For example the default
  style is:

```css
.pie {
  color: #EC4E89;
  background: #bbb;
  border: 2px solid white;
}
```

## API

### new Piecon([selector])

  Initialize a new `Piecon` with optional CSS `selector` used
  for styling, this defaults to ".pie".

### Piecon#update(n)

  Update the percentage to `n`, this will automatically
  draw the pie and replace the favicon.

### Piecon#size(n)

  Set the diameter to `n`.

### Piecon#reset()

  Reset favicon.

# License

  MIT

