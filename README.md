# Setup

For the fullscreen button to work, you have to go into this file:
`Milkdown_next\static\chunks\pages\playground-921c97ac027c59a1.js`
and replace the two instances of `file:///index.html` with the actual path to `index.html` on your machine.

Leave the `?expand=true` argument in the first instance.

For example, it could look something like this after you perform this step on a Windows machine:
`...u.push("file:///C:/Users/yummy/Downloads/Milkdown/index.html?expand=true"):u.push("file:///C:/Users/yummy/Downloads/Milkdown/index.html")...`

# Other important stuff

* Pressing the fullscreen button will lose all progress, as it just refreshes and adds a fullscreen argument in the URL.
  To avoid this, please press the share button, which encodes the markdown into the URL, before pressing the fullscreen button.
  Then, you can create a bookmark (after pressing the share button) to save your text.
* This does pull some assets from servers, including vectors and fonts. The dark\_mode, chevron\_left (fullscreen button), and share buttons are some examples of of this. However, the buttons are still usable. For this reason, I didn't bother trying to make these buttons load from the archive. The font will be slightly different (as they will be your browser's default fonts), but again, it is still usable.
* I made this readme file with this archive of Milkdown + Crepe 🤣
