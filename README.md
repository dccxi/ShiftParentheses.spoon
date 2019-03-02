# ShiftParentheses.spoon

Supercharge your <kbd>shift</kbd> key. Tap it for parentheses. Hold it for <kbd>shift</kbd>.

### A more useful shift key

As Steve Losh points out in his [Modern Space Cadet](http://stevelosh.com/blog/2012/10/a-modern-space-cadet/#control-escape) post, there are "keys you hold down to change how other keys behave, but that (usually) don’t do anything if you use them on their own" (e.g., <kbd>shift</kbd>), and there are "keys that you press and release but don’t want to 'repeat' as you hold them" (e.g., parentheses). "There are two [distinctly] different ways to use [these keys] and they’re each only useful in one of those ways. This means that we can *combine* them onto a single key without losing any useful functionality!"

With that in mind, we can teach the <kbd>shift</kbd> key to pull double duty:

- If <kbd>shift</kbd> is pressed and released in isolation, we can generate a pair of parentheses and locate the cursor between them
- If <kbd>shift</kbd> is held down and used in combination with another key, then we can let it provide the normal <kbd>shift</kbd> key behavior

## Dependencies

This functionality is developed and tested with the following dependencies:

- macOS Sierra 10.12
- [Hammerspoon 0.9.54][hammerspoon]

## Installation

#### Just the basics

```sh
mkdir -p ~/.hammerspoon/Spoons

git clone https://github.com/dccxi/ShiftParentheses.spoon.git ~/.hammerspoon/Spoons/ShiftParentheses.spoon

cd ~/.hammerspoon/Spoons/ShiftParentheses.spoon

script/setup
```

Now you're ready to rock. 🤘

## Where can I get this code as a Spoon?

If you prefer to roll your own Hammerspoon config, this code is also available as a [Spoon](https://github.com/Hammerspoon/hammerspoon/blob/0.9.54/SPOONS.md#how-do-i-install-a-spoon). Just look for `ShiftParentheses.spoon.zip` included with the [latest release](https://github.com/dccxi/ShiftParentheses.spoon/releases/latest).

## Shout-outs

Shout-out to [@arbelt](https://github.com/arbelt) and [@jasoncodes](https://github.com/jasoncodes) for the original implementation of this functionality. ⚡️🍻🌟

This code is an adaptation of their work:

- https://gist.github.com/arbelt/b91e1f38a0880afb316dd5b5732759f1
- https://github.com/jasoncodes/dotfiles/blob/ac9f3ac/hammerspoon/control_escape.lua

## You might also like...

Still reading? Dude, you're pretty serious about your keyboard. :neckbeard:

Lucky for you, there's more where this came from. Check out [jasonrudolph/keyboard](https://github.com/jasonrudolph/keyboard#features) for even more fun. ⌨🤓

[hammerspoon]: http://www.hammerspoon.org
