- Missing driver for Arduino IDE

- Currently missing math.h - I think it was a dependency that Arduino automatically resolved?

**IMPORTANT!**

In order to compile this solution, you must follow these instructions or you will have unresolved dependencies.

See https://github.com/teemuatlut/TMC2130Stepper

1. Use the Arduino IDE library manager (Sketch -> Include library -> Manage libraries...)
2. Search for TMC2130Stepper and then install.

**Requires the following Workspace Settings:**

`{
    "C_Cpp.intelliSenseEngine": "Tag Parser"
}`