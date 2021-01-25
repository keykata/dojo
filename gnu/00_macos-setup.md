# MacOS Setup

## Script

### Overview

Welcome to the first in hopefully a long series of KeyKata videos.

The idea of KeyKata is for you to practice while watching the video.

All of the lesson materials, including the script for this video, are available
at https://github.com/keykata/dojo

### MacOS Apps

Before we take a look at the materials, I'm going to install some awesome MacOS
Apps that will make everything we do easier and (dare I say?) more fun. Windows
and Linux users won't be able to follow along with this video, but I will
mention non-MacOS alternatives throughout this video. Please feel
free to contribute your own content, for example Windows and Linux setup
instructions, via pull request at https://github.com/keykata/dojo.

#### Vimari

The first App I will install is called
[Vimari](https://github.com/televator-apps/vimari/#vimari). Vimari provides
enhanced scrolling and a hint mode that removes the need to use the mouse in
the browser. Later on, I will switch from Safari to Firefox and Chromium-based
browsers, so Windows and Linux users can follow along. First, I'll open up the
App Store using the MacOS Spotlight Search. The Spotlight Search shortcut is
`Command Space`. The Windows equivalent of Spotlight Search would be to press
the Windows key. Next, I will press `Command f` to go to the search input
field. After I type in vimari, I press enter and then click install. Now I can
open up Safari, again with Spotlight Search, to install Vimac, another awesome
MacOS App. After I press `command l` to edit the url, I'll type in
vimacapp.com. Thanks to Vimari, I can scroll down with `j` and scroll up with
`k`. Vimac is going to allow us to scroll like this outside of the browser. The
other feature that is shared by both Vimari and Vimac is the Hint Mode. To use
the Vimari equivalent of Hint Mode, I press `f`. Then I can press the key shown
to open the link underneath. On the next page, I press `f` again to start the
download. Then I have to click the pop-up to allow the download.

#### Vimac

[Vimac](https://github.com/dexterleng/vimac#vimac) provides a keyboard centric
interface to MacOS called Hint Mode. Windows users can get the same
functionality from [hunt-and-peck](https://github.com/zsims/hunt-and-peck). To
install Vimac, I'll copy some download the latest release from the
`vimacapp.com`. First, I'll open up Safari using the MacOS Spotlight Search.
The Spotlight Search shortcut is `Command Space`. The Windows equivalent of
Spotlight Search would be to press the Windows key. Since I wiped this computer
before recording this video, the only browser I have is Safari. Safari is only
available on MacOS, but any browser will do. and Karabiner Elements. and
Karabiner is a keyboard customization application

and Keyboard Manager,
which comes with Windows PowerToys. To install these Vimac and Karabiner, I
will use a command-line installer and package manager called Homebrew. In Safari, I type the url `brew.sh`. I'll click the
clipboard button below "Install Homebrew". Next, I'll paste this url into the
MacOS terminal. To open up the MacOS terminal, I will use Spotlight Search
again. After Homebrew is installed, I can `brew install --cask vimac
karabiner-elements firefox`. I'm also installing Firefox because it has two
browser extensions that I think are really useful. After installation, I use
Spotlight Search yet again to open up Vimac. I am prompted to grant some
permissions for Vimac in System Preferences. After the permissions are granted,
I will change the default Vimac keyboard shortcuts. For Scroll Mode, I will use
`Command Shift J` and for Hint Mode I will use `Command Shift ;`. Once the
setup is complete, I can use Vimac to setup Karabiner Elements. First, I open
Karabiner Elements using Spotlight Search and grant permissions as before. Now
I will use Karabiner Elements to add two super useful complex modifications.
This takes me to a browser where Vimac Hint Mode is useless. Vimac is actually
inspired by the browser extension I will install next. The first modification
is called "Change caps_lock to Control if pressed with other keys, to escape if
pressed alone." from the "Change caps_lock key (rev 4)" section. The second
modification is called "Change return to Control if pressed with other keys, to
return if pressed alone", which is under "Change return to Control".


and load in two
keyboard modifications. 
Now that I have my keyboard set up, let's take a look at the materials
together. To switch back to Safari, I will `Command Tab`. The Windows
equivalent is `Alt Tab`. Next, I select the url with `Command l`. The Windows
shortcut to select a url is `Control l`. Now that I have the url selected, I
can type the url that leads to the materials. Before pressing enter, I will
press `Command a` and `Command c` to select and copy the url. The Windows
shorcuts to select all are `Control a` and `Control c`. These shortcuts
conflict with the shortcuts covered in the KeyKata materials. Windows users can
use the Windows Keyboard Manager to try to reconcile the differences. I
recommend using the `Windows` instead of `Control` to select all, select urls,
cut, copy, and paste. This will free up Control for all of the awesome
shortcuts will learn to use in the shell and in text editors.

Now that I have the url copied, I can take a look at the page and then switch
back to MacOS terminal. Next, I'm going to paste the url I copied into the
MacOS terminal. On Windows, I would install the Windows Subsystem for Linux
(WSL) and the Windows Terminal. After pasting in the url, I press `Control a`
to go to the beginning of the line in the terminal. At the beginning of the
line, I type git clone. By default, git clone would copy the materials to a
directory called dojo. Instead, I am going to go to the end of the line with
`Control e` and specify a different target directory. Now, I can press Control
m, Control j, or enter to clone the materials to the directory I specified. To
go to the cloned repository, I'll use the cd command, which stands for change
directory. Instead of typing out the target directory again, I press `alt .` to
reuse the last argument. This shortcut is super handy! Now that I am in the
right place, I can open up some files. To look at the available files, I will
run the ls command. Let's open up the welcome to keykata file using the open
command. The open command only works on MacOS, but Linux and WSL users should
be able to open files with the xdg-open command. Instead of typing out the
entire filename I can press tab after the prefix to have my shell fill in the
rest of the filename. This called tab completion. Now I press enter and I see
the default file contents in the default text editor, which for MacOS is
TextEdit. In TextEdit, I can practice pressing `Control a` and `Control e`, but
this will not work for Windows and Linux users. Let's go back to the terminal
and install a better text editor. 

If I want to go to the beginning of the url I can
press `Control a`. Instead of reaching To go back to the end of the url, I press `Control e`.
`Control a` and `Control e` are default shortcuts in MacOS. On Windows, I would
have to press the home and end keys. 
