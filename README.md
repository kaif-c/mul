# MUL (**M**agnifying  **U**tility for **L**inux)

## Description

This is a small lightweight magnifying/zooming application for [Linux](https://en.wikipedia.org/wiki/Linux) written in the 
[C programming language](https://en.wikipedia.org/wiki/C_(programming_language)).
This is HEAVILY inspired by [boomer](https://github.com/tsoding/boomer), but is made to be faster, smaller and has no issues with WM animations 

## Dependencies

- X11
- OpenGL

## Build From Source

### Build System Needed:
- make

### 1. Clone the repository
```bash
git clone https://gitlab.com/Agent11196/mul
```

### 2. Use `make` to compile the program
```bash
make release
```

### 2.1. For debug builds
```bash
make
```

### 3. Run
```bash
./build/rel/mul
```

### 3.1. Run debug build
```bash
./build/dbg/mul
```

## Controls
| Control | Action |
|---------|--------|
|Scroll up| Zoom in |
|Scroll down| Zoom out |
|Mouse Click + Drag| Pan the camera |

## Configuration
| Argument | Action |
|----------|--------|
|-h, --help | Shows the list of arguments and the usage |
| -v, --version| show the version of program and exit |
| -z, --zoom-sensitivity <float32=0.2> | scroll sensitivity for zooming|
| -p, --panning-sensitivity <float32=1.0> | mouse cursor sensitivity for panning the camera |
