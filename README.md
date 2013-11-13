SASSFace
========

SASSFace is an easy, breezy SASS (SCSS, actually) mixin and variable library to
help you make your Facebook app look like -- you guessed it -- Facebook.

## Philosophy

Keep it simple. Facebook is inconsistent in their usage of their own styles.
Colors, type sizes, and whitespace appear in infinite combinations. SASSFace
doesn't try to match Facebook example. Instead, it goes for simple and good
enough.

SASSFace doesn't pollute your namespace when you `include` it -- everything is
prefixed with `fb`.

## Usage

Just `@import "sassface";`, and start using SASSFace's mixins and variables,
like such:

```
body{
  @include fb-text;
}

a{
  @include fb-link;
}

.panel{
  @include fb-panel;
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Make your changes
4. Commit your changes (`git commit -am 'Added some feature'`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create new Pull Request

## TODO

1. ~~Buttons~~
2. Lists
3. Headers
4. Forms
