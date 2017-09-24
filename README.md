# Coder keyboard layout

On a standard keyboard layout the pinkies are exposed to heavy workloads, despite being the weakest and slowest fingers. Apart from their designated letters and numbers, they are responsible for the Enter, Backspace, Escape, Shift, Delete, Control, Tab and the Arrow buttons. The main goal of this layout is to reduce the load on the little fingers. 

The thumbs on the other hand have only one task - to press on the space bar (and occasionaly press on the Command/Window/Alt buttons). The thumbs are durable and strong, we should give them a higher workload. In this layout the four buttons adjacent to the spacebar are remapped as modifier keys. These are the layers it gives us:

1. **Standard layer**, based on the optimized keyboard layout QFMLWY from  [carpalx](https://www.google.com). Some symbols are swapped such as ".", "-" and the "," button because of their frequent use in code.

2. **Standard layer captial letters**, also have room for interational letters.

3. **Symbol layer**, Their positions are laid out depending on n-gram frequency, inward rolls are prefered.

4. **Navigation layer**, Move and delete words and sentences.

5. **System layer**, Micellanelous system commands

6. **Selection layer**, Select words and sentences 

7. **Window layer**, Move windows on the screen using  [Spectacle](https://www.spectacleapp.com/)

Of the number buttons only 2,3, and 8,9 are suitable for use as you can see in the keymap below. This is because they are pressed by the ring and long fingers, only these fingers are long enough to reach up to the number row. 

The remap is implemented as a [Karabiner](https://pqrs.org/osx/karabiner/) configuration file, `karabiner-keybindings.xml` pull requests are welcome for other platforms. 

Suggestions for new remappings are also welcome if they can be justified by reasonable arguments.

![Layout](https://github.com/3h4/coder/raw/master/keymap.png)