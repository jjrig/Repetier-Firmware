Remember to load/reset EEPROM correctly or your configuration.h modifications may be ignored.

**IMPORTANT!**

In order to compile this solution, you must follow these instructions or you will have unresolved dependencies.

See https://github.com/teemuatlut/TMC2130Stepper

1. Use the Arduino IDE library manager (Sketch -> Include library -> Manage libraries...)
2. Search for TMC2130Stepper and then install.

**Requires the following Workspace Settings:**

`{
    "C_Cpp.intelliSenseEngine": "Tag Parser"
}`

Configuration

- Most configuration is done in Configuration.h
- If you want to use Marlin-style TMC2130 controls, uncomment this line in Printer.cpp
`#define USE_MARLIN_CONFIG`
