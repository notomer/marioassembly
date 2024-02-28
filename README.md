# Mario Game in Assembly for Apple Silicon ARM Processors

This is a simple implementation of the classic game Mario written in assembly language specifically designed for Apple Silicon ARM processors. It utilizes BIOS interrupts for keyboard input and screen manipulation to create a basic game loop where Mario can move left, right, and perform a jump.

## Prerequisites

- Apple Silicon ARM-based Mac
- NASM (The Netwide Assembler)
- QEMU (optional for emulation)

## How to Run

1. Clone or download the repository to your local machine.
2. Navigate to the directory containing the assembly code.
3. Compile the code using NASM:
4. Link the object file to create an executable:
5. Run the executable:

6. Use the following keys to control Mario:
- 'a' - Move left
- 'd' - Move right
- 'w' - Jump

## How to Play

- Mario starts at an initial position and can move left or right using the 'a' and 'd' keys respectively.
- Press 'w' to make Mario jump.
- The game loop continuously updates, allowing Mario to move within the boundaries of the screen.
- Mario's jump height is limited, and he falls back down after reaching the peak of his jump.
- Collision detection prevents Mario from moving beyond the screen boundaries.

## Notes

- This implementation uses BIOS interrupts for keyboard input and screen manipulation, which may not be the most efficient or modern approach but serves as a simple demonstration of game development in assembly language.
- Emulation with QEMU may be necessary if running on a newer Mac with Apple Silicon.

## Credits

This implementation is created by me, Omer.