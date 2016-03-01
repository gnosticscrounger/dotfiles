# dotfiles - Modal and Keyboard Driven

## Introduction

Since getting into vim and the keyboard-driven way of doing things, I've dreamt of setting up a system where every element is geared towards achieving friction-less movement and control with the keyboard. The modular and completely editable nature of Linux - Particularly Arch Linux gives me the opportunity to achieve this. After screwing up my installation a couple of times - including my current one to be perfectly honest - and reading [this gentleman's repository](https://github.com/noctuid/dotfiles), I now have some idea of where to go with all of this.

## What I have accomplished so far

* Keymap alterations
  * Swapped escape and capslock positions
  
  ###### This is absolutely mandatory in my opinion to make vim/evil and by extension pentadactyl usable.
  
  * Swapped positions of lctrl and lalt and assigned the meta key to ralt.

  ###### This is the only keybinding in which emacs's modifier-happy design makes sense in and is closer to the [keyboard RMS himself probably used](https://en.wikipedia.org/wiki/Space-cadet_keyboard). My alteration to the scheme is to make the right alt the meta key so the vast majority of modifier key usage is done with the thumbs.

## Keymap Thoughts and Plans

While I have covered most of my bases here, there are still a few niggling issues with keys. The real elephant in the room is the shift key which requires an ugly pinky stretch to use. I'm thinking of possibly creating a second state for the capslock key where if held down, acts like a shift key. A quick tap will still make it behave as the escape key. I can't think of any use case off the top of my head which requires the holding down of the escape key so this sounds like a good plan atm.

In the long term, I plan on persuing stenography with the use of [Plover](https://github.com/openstenoproject/plover) once I get my hands on a decent nkro keyboard. However, I certainly got plenty of headroom to improve on my qwerty typing speed first before trying this. However, the promise of greater than 2 times speed gain while reducing RSI risk is very enticing - even if the idea of finding a laptop with a nkro keyboard built-in to it is less so.

More "conventional" alternative keyboard schemes like dvorak and colemark don't interest me because they don't offer a large enough speed up or indeed comfort gain to justify putting in the time to learn them and they are reported to actively interfere with your qwerty abilities so that rules out 99% of public computers and many of my friends'. By comparison, stenography is so fundumentally different in action and style to traditional typing that my qwerty typing should not be altered significently beyond perhaps a little rust from lack of usage which I can live with.

Stenography will definitely require a radically different approach to keyboard control though beyond just insertion of text. While the prospect of executing multi-syllabic commands with single keystrokes is enticing, the idea of coming up with an interface for this still largely virgin territory is intimidating. 
