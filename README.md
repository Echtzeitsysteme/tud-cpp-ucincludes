# tud-cpp-ucincludes

## Flashing without setting the mode selection switch S1 to PROG
Set UART_SCANNING in **start.asm** to ON to avoid setting the mode switch to PROG before flashing the board.
Instead, flashing is also possible when the mode selection switch is set to RUN.
