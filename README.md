# Coder keyboard layout

On a standard keyboard layout the pinkies are exposed to heavy workloads, despite being the weakest and slowest fingers. Apart from their designated letters and numbers, they are responsible for the Enter, Backspace, Escape, Shift, Delete, Control, Tab and perhaps some of the the Arrow buttons. The main goal of this layout is to reduce the load on the little fingers. 

The thumbs on the other hand have only one task - to press on the space bar (and occasionally press on the Command/Window/Alt buttons). The thumbs are durable and strong, we should give them a higher workload. In this layout the four buttons adjacent to the spacebar are remapped as modifier keys. These are the layers it gives us:

1. **Standard layer**, based on the optimized keyboard layout QFMLWY from  [carpalx](http://mkweb.bcgsc.ca/carpalx/?full_optimization). Some symbols are swapped such as ".", "-" and the "," button because of their frequent use in code.

2. **Capital letters layer**, this layer also have room for international letters.

4. **Navigation layer**, Move the caret and delete words and sentences.

3. **Symbols and Debug layer**, The positions of the symbols are laid out depending on n-gram frequency, inward rolls are preferred.

5. **System and Numbers layer**, Miscellaneous system commands as well as a number pad.

6. **Selection layer**, Select words and sentences.

7. **Window layer**, Move windows on the screen using [Spectacle](https://www.spectacleapp.com/) for Mac. Room for more uncommon commands.

Of the number buttons only 2,3, and 8,9 are suitable for use as you can see in the keymap below. This is because they are pressed by the ring and long fingers, only these fingers are long and strong enough to reach up to the number row. 

You may notice that some commands are possible to access with only one hand on the keyboard. The idea is that the other hand should control the trackpad/mouse while performing some common tasks such as:

- *Left hand*: Change desktop/app/tab, show desktop/miniature windows, scroll vertically, copy/cut/past text or files. *Right hand*: Use the mouse for selection.
- *Left hand*: Inspect web elements, increase/decrease CSS. *Right hand*: Use the mouse for selection of elements and CSS rules. ([Chrome devtools custom hotkeys](https://bugs.chromium.org/p/chromium/issues/detail?id=174309) have to be implemented before this will fully work).
- *Left hand*: Comment code, tab in, tab out, delete, add line (return). *Right hand*: Use the mouse for selection and moving the caret.
- *Right hand*: Run/debug, step in, step out, step over, clear the console. *Left hand*: Use the mouse for expanding data structures setting breakpoints etc.
- *Right hand*: Go backwards, forwards. *Left hand*: Use the mouse to click on hyperlinks and browse the web.

The left and right hand should alternate using the mouse for ergonomy as you can see above. Apart from this, here are some additional requirements:
- Capital letters should be in the same layer (often used together).
- Navigate the caret then select text should be smooth (pressing one additional modifier button). 
- Undo should be in the same layer as the deleting buttons.
- Number should be in the same layer (often used together).
- Symbols should be in the same layer (often used together).

The remap is implemented as a [Karabiner](https://pqrs.org/osx/karabiner/) configuration file, `karabiner-keybindings.xml` pull requests are welcome for other platforms. 

Suggestions for new remappings are also welcome if they can be justified by reasonable arguments.

![Layout](https://github.com/3h4/coder/raw/master/keymap.png)
