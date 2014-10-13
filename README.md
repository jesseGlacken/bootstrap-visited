# Bootstrap-visited

Overrides `less/mixins/buttons.less` in [Bootstrap 3](https://github.com/twbs/bootstrap) to protect :visited state on buttons.

`<soapbox>`

[@mdo](https://github.com/mdo) has [stated on](https://github.com/twbs/bootstrap/issues/2144) [multiple](https://github.com/twbs/bootstrap/issues/2789) [occasions](https://github.com/twbs/bootstrap/issues/6656) that Bootstrap will not include :visited states for links (button-styled or otherwise), and I'm cool with that.

For myself, I'd rather have one fewer thing to consider as I'm writing my code. 
I also can't think of a case where I'd want my content's :visited state to flow through to a UI element that corresponds to a repeatable task, when I don't care if I've performed that task before.

Hence: this repository.

`</soapbox>`

## How to use

Include `buttons.less` after Bootstrap in your LESS files, either manually or via your build system of choice. That's it.