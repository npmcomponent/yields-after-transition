
# after-transition

  Invoke a function after transition or immediately.

## Installation

  Install with [component(1)](http://component.io):

    $ component install yields/after-transition

## API

### after(el, fn)
Invoke the given `fn` after transitions

It will be invoked only if the browser
supports transitions __and__
the element has transitions
set in `.style` or css.

### after.once(el, fn)

Same as `after()` only the function is invoked once.

## Notes

  - for this to work the element style must be computed.
  - it uses `.getComputedStyle()`.

## License

  MIT
