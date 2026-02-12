CHANGELOG:

1.3

- can remap UP,DOWN,LEFT,RIGHT keys in keymap.json file (will update the web keymap editor later). they are the last 4 keys in the keymapnormal array.
- Bookmarks Mode has been given a facelift, looks clean now
- fixed umlauts not working in deadkeys
- added escape character for markdown "\" meaning you can type an asterisks * by typing \* (for example)
- cleaned up some markdown and fountain formatting
- increased the time window for inputting passcode locks (will look at this furhter down the line, this is just a quick solution)

1.28

- fixed editor often adding " " extra spaces to sentences in existing files when opening them

- Added Markdown and Fountain modes, supporting stuff like bold, italics, etc  - these are meant as demonstration for the kinds of extensions we can build. These renderers are enabled via the menu, and will act as interpreters for your file underneath.

	- Note that your active line is always rendered as plain text

	- Note that Markdown and Fountain operate at 80% width to minimize lines running off the screen

	- Markdown is a plaintext file format that is popular for people writing for web or rich-text. Markdown on Zerowriter Ink supports: *italics* **bolds** or _italics_ __bolds__

	- Fountain is a plaintext file format that is for screenwriters / scriptwriters. Fountain on Zerowriter Ink supports most Fountain syntax. Also supports: *italics* **bolds** _underlines_ Learn more here: https://fountain.io/syntax/

- Added an option to "Reset Persistent Settings" - this should fix issues if your settings are not saving. You can toggle this on in settings.

- Added an option to turn on a Lock Code sequence to unlock your Zerowriter after sleep. This is not meant for security, but for preventing accidental input. If turned on, whenever your Zerowriter is put to sleep (CTRL+L, or timer), it will prompt for an unlock sequence of keys.

- Added a "Are you sure?" confirmation dialog throughout: when deleting files, deleting or resetting settings, etc.

- Fixed some editor bugs like adding extra " " spaces at the start of lines



====


To install a firmware bin from SD card:

find the "firmware.bin" you want
place on SD card in root directory
insert SD card to Zerowriter Ink
Turn on (or reboot) Zerowriter Ink
Automatically will install

If your update fails, or it keeps rebooting, it means you need to proceed with a manual restore/update first. 
This will enable you to do SD card updates in the future.

To do the manual restore/update, visit this page:

https://zerowriter.ink/pages/firmware-updates
