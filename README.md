# Terminal Form Builder

A C++ terminal application for creating, editing, saving, and running simple text-based forms.

## Features

- Create labels, textboxes, and buttons
- Position and render components in the console
- Save, load, edit, and remove forms
- Enter and save form data

## Requirements

- Windows
- CMake 3.21 or newer
- A C++14 compiler (for example, Visual Studio Build Tools)

The application uses Windows-specific console headers and is not currently portable to Linux or macOS.

## Build

Run these commands from a Windows Developer PowerShell or a terminal configured with a C++ compiler:

```powershell
cmake -S . -B build
cmake --build build --config Release
```

## Project Structure

```text
terminal-form-builder/
├── src/
│   └── main.cpp
├── CMakeLists.txt
├── README.md
└── LICENSE
```

## Scope

This is an educational project for practicing C++, basic data structures, console input, and form rendering. It is not intended for handling sensitive data or production use.
