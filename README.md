# Wimp text rendering library

This repository holds a rendering library for use inside the RISC OS WindowManager.
It is intended for use with the RISC OS 64 project (which aims to bring RISC OS
towards a 64-bit system).

The text rendering library implements the internal and external calls for the
WindowManager, specifically the `Wimp_TextOp` interface. This will allow other components
to render text to the display in the same way as RISC OS Classic.

The library uses a further library, [GContext](https://github.com/gerph/riscos-gcontext)
which provides the graphics operations that actually render text.

The library implements the components described within the RISC OS 64 project. See
[WindowManager (Text rendering)](https://github.com/gerph/riscos64-status/wiki/Module_WindowManager_TextRender) for more details.
