# Welcome to KeyKata

## Index
1. [Overview](#overview)
2. [Materials](#materials)
3. [Setup](#Setup)
  - [Terminal](#terminal)
  - [Shell](#Shell)
  - [Code editor](#code-editor)
  - [Browser](#browser)
  - [Keyboard](#keyboard)
4. [Symbols](#symbols)
5. [Where to start?](#where-to-start)

## Script

### Overview

Welcome to the first in hopefully a long series of KeyKata videos.

The idea of KeyKata is to promote intelligent use of the keyboard to
- boost productivity and
- reduce the risk of repetitive stress injury.

Along the way, you can learn important skills like
- computer programming and
- git version control

I also hope that the materials provided here will help you improve your touch
typing ability.
In particular, the benefits of practicing touch typing are
- increased speed and
- decreased error rate

That being said, don't worry too much about your speed or error rate. Being
able to fix errors quickly is just as important, if not more important, than
avoiding errors in the first place. We're all human and we all make mistakes.

Instead of focusing on speed and error rate, I recommend putting the emphasis
on building good habits. A term that I like to keep in mind is Kaizen,
a Japanese word that means "continuous improvement". Concentrating on working
towards positive change will make learning and practicing with KeyKata more
enjoyable.

The name KeyKata comes from another Japanese word, kata, which means "form" and
is used to refer to a series of movements used to practice Karate, a Japanese
Martial Art.

Don't worry, I'm not planning to go overboard with the use of Japanese terms
and I'm not going to refer to myself as your Sensei :)

[Back to index](#index)

### Materials

The first thing you'll want to do is to learn to navigate the KeyKata
materials. All of the lesson materials, including the script for this video,
are available at https://github.com/keykata/keykata

The materials in the KeyKata GitHub organization are divided up into two
repositories:
- setup and
- dojo

Repositories, or repos, are version controlled directories and dojo is
a Japanese word that means "training hall".

You can get a local copy of the materials by
- cloning one of the KeyKata repositories or
- downloading a zip file through the GitHub interface

If want to clone a repository, but don't know how,
take a look at the [Git
setup](https://github.com/keykata/setup/blob/main/git-setup.md)
materials.

Depending on the operating system you are using, some setup may be required. At
the beginning of each kata, I will reference recommended and required setup
materials.

[Back to index](#index)

### Setup

To maximize the benefit of KeyKata, you should follow along while watching the
video, so you can practice and build up your muscle memory.

To follow along with most videos, I recommend that you use either a:
- a UNIX terminal or
- a code editor, like RStudio

#### Terminal

If you want to follow along in a UNIX terminal, you can use the terminal
included with MacOS or any Linux distribution. If you are using ChromeOS, you
need to enable Linux (Beta) under Settings. For Windows users, I recommend
installing [GitBash](https://gitforwindows.org/) or [Windows Subsystem for
Linux (WSL)](https://docs.microsoft.com/en-us/windows/wsl/install-win10).

If you prefer not to use a terminal, you can install RStudio.
RStudio is available for MacOS, Linux, and Windows. I'll demo the
RStudio Emacs mode at the end of most videos. For information on RStudio
installation, check out the [RStudio setup
materials](https://github.com/keykata/setup/blob/main/rstudio-setup.md).

Simiarly, you also don't need to use the exact software that I'm using. Any
UNIX terminal or code editor should work! Instead of the MacOS terminal, I use
iTerm, a 3rd party terminal emulator for MacOS. When I say something is 3rd
party, I mean that it is not a builtin MacOS application created by Apple. More
importantly, iTerm is free open source software (FOSS).

Before I record videos, I switch to a white terminal background because the
contrast is better, but otherwise my terminal background is dark as night. My
terminal font is FiraCode, though I chose Inconsolata for the KeyKata logo.
I think terminal customization is not that important, but if you want to set up
your terminal like mine, you may be interested in the [iTerm setup
materials](https://github.com/keykata/setup/blob/main/iterm-setup.md).

[Back to index](#index)

#### Shell

Inside my terminal, I use Z shell (zsh). Zsh is the default MacOS shell since
Catalina, but you can also use Bash, the default Linux shell. My zsh is heavily
customized and I don't recommend going down that rabbit hole right away. That
being said, I do have materials related to [zsh
setup](https://github.com/keykata/setup/blob/main/zsh-setup.md), including the
prompt, shell aliases, and keybindings.

#### Code editor

In contrast to zsh setup, my RStudio setup is pretty minimal and is covered in
the [RStudio setup
materials](https://github.com/keykata/setup/blob/main/rstudio-setup.md).
I chose RStudio as the first code editor to cover, because it is very easy to
install and requires no additional setup beyond switching the editing mode to
Emacs or Vim. Later, I plan to introduce a Jetbrains code editor such as
PyCharm and Visual Studio Code.

#### Browser

There are also kata that focus on web browser keybindings. For those kata, you
should use Firefox or a Chromium-based browser like Chrome or Edge, instead of
a terminal or code editor. In order to follow along, you'll need to install the
[Vimium](https://github.com/philc/vimium#vimium---the-hackers-browser) and
[Surfingkeys](https://github.com/brookhong/Surfingkeys#surfingkeys---expand-your-browser-with-javascript-and-keyboard)
browser extensions. The first browser kata shows how to install these browser
extensions for Firefox and Chrome.

[Back to index](#index)

### Keyboard

##### Layout
To follow along you don't need to have the exact same keyboard layout that
I have. In other words, if you your keyboard looks different than mine, that's
ok! The layout will probably be fairly similar and I don't expect you'll have
any problems following along.

##### Hardware
Also, don't feel pressure to get an expensive keyboard. Fancy keyboards are
nice, but if you are happy with a keyboard you already have, you certainly
don't need to get a new keyboard to use the KeyKata materials. If you do
want/need to buy a keyboard, I would suggest trying to find a cheaper version
of an Apple magic keyboard, a bluetooth keyboard without a number pad. ![apple
magic
keyboard](https://raw.githubusercontent.com/sharlagelfand/ggkeyboard/main/man/figures/README-mac-1.png)

##### Customization

While keyboard customization is not required, I highly recommend setting up
Caps Lock and Enter to act as Control when pressed with other keys. On MacOS,
this can be achieved by installing Karabiner and importing the two rules shown
here. For more, check out my [Karabiner setup
materials](https://github.com/keykata/setup/blob/main/karabiner-setup.md).

[Back to index](#index)

### Symbols

In all of the videos, I will show my keystrokes as I'm typing with the built-in
MacOS accessibility keyboard and/or Keycastr, a 3rd party MacOS Application. It
will be helpful to learn the symbols used to represent keys like
- Command (or Cmd) ⌘
- Shift ⇧
- Option (or Alt) ⌥
- Control (or Ctrl) ⌃
- Escape ⎋
- Tab ⇥
- Return ↩
- Space ␣
- Left ←
- Down ↓
- Up ↑
- Right →

I customize my keyboard to use Caps Lock ⇪ as Control ⌃ when pressed with other
keys and Escape ⎋ when pressed alone, so you will never see the Caps Lock key
highlighted on the MacOS accessibility keyboard or shown in Keycastr display.
Also, you may notice that Control ⌃ is briefly highlighted before Escape ⎋,
because I always press Caps Lock instead of the actual Escape ⎋ key.

[Back to index](#index)

### Where to start?

For your first kata, I recommend trying these three kata in a UNIX shell or
RStudio:
1. [Move to start and end of current line with ctrl a and ctrl
   e](kata/01_ctrl-a-and-ctrl-e_move-to-line-start-and-end.md)
2. [Move left and right with ctrl b and ctrl
   f](kata/02_ctrl-b-and-ctrl-f_move-left-and-right.md)
3. [Delete left and right with ctrl h and ctrl
   d](kata/03_ctrl-h-and-ctrl-d_delete-left-and-right.md)

After that, you can continue through the remaining Control shortcuts and then
the Alt shortcuts. The browser kata are also a great place to start. After you
feel comfortable with the Bash / Emacs shortcuts and you think you might ready
to learn about modal editing, give the Vim kata a try.

Please don't hesitate to let me know what you think about KeyKata and feel free
to submit an issue or start a discussion if you like!

Happy typing!

[Back to index](#index)
