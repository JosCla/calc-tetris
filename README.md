# calc-tetris
Calculator Tetris made with Axe Parser. Made c. April 2017.

## Compatibility
This program is definitely compatible with the following calculators, and will almost definitely not corrupt/damage them:
- TI-84 Plus

This program is likely compatible with other similar TI calculators, particularly those in the TI-83 and TI-84 series, though I have not had the chance to test this. Please notify me if you find that this works on a different calculator that is not listed here!

Additionally, although I have tried my best to ensure that this program will not corrupt/damage your device, there is always the chance, especially if you use this program on a device that isn't listed above, that the program may damage your device.

## Usage
*Note: You should take a backup of your calculator before following any instructions below.*

To use this program, you can either download the compiled binary (TETRIS.8Xp) or you can compile the program from its source (src/AXETETRI.8Xp).

In either case, you will need to send files to your calculator. I would suggest using TI-Connect on Windows/macOS, and TiLP on Linux.

Additionally, I have uploaded a local scoreboard that I made while playing with the program in development. Feel free to download it (TETSB.8Xv) and use it on your own device! If you choose not to use it, an empty scoreboard will be created after your first game, assuming your device has enough memory for it (it almost certainly will).

### From Binary
After transferring the binary to your device:
1. Use [2nd][0] to access the command catalog.
2. Locate the command "Asm(" and press [Enter].
3. Use [PRGM] to access your programs.
4. Locate the program "TETRIS" and press [Enter].
5. Press [Enter] to run the command, starting the game.

### From Source
After transferring the source to your device:
1. Use [Apps] to access your applications.
2. Start the Axe Parser compiler, labeled "Axe". If you don't have Axe, you can find the latest release at https://www.omnimaga.org/the-axe-parser-project/latest-updates-(***do-not-post-here!***)/45/ . After decompressing the file, you can just send the enclosed Axe.8xk to your device, and it will be recognized as a runnable application.
3. Select the Compile option.
4. Use the Ion compile mode (it should be Ion by default).
5. Select the AXETETRI program, and wait for it to compile.
6. At this point, your program should have successfully compiled. Refer to the "From Binary" section above to see how to run the program.

## Controls
- [Left/Right Arrows]: Moves the piece left and right
- [Down Arrow]: Soft Drop
- [Up Arrow]: Hard Drop
- [2nd/Mode]: Rotates the piece clockwise/counterclockwise
- [Alpha]: Hold piece
- [Math]: Pause game ([Enter] to unpause)

## Documentation
Included in doc.txt is a rough documentation of the function of the program. This was one of my earlier programming endeavors, and some of the design decisions that I made were somewhat strange, and difficult to correct. I nevertheless tried to give some sense of what the program is doing at each step using numerous comments along with more appropriate spacing and indentation.
