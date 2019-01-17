# react-ipuz

This is a demo for **react-ipuz**, a collaborative crossword puzzle player. The frontend was built with React/Redux and the backend is a Ruby on Rails API with Action Cable support to allow real-time collaboration.

Requires [react-ipuz](https://github.com/ihollander/react-ipuz) frontend and [react-ipuz-api](https://github.com/ihollander/react-ipuz-api) backend.

## Features
1. [Convert .puz files to playable crosswords](#file-conversion)
2. Interactive puzzle grid
3. Puzzle tools and timer
4. Save puzzle progress
5. Real-time collaboration

### File Conversion
Puzzle conversion is made possible thanks to a custom Javascript .puz file parser, written for this project based off this [spec] (https://code.google.com/archive/p/puz/wikis/FileFormat.wiki). Users can upload puzzle files from a number of major crossword puzzle publishers, including the New York Times and Wall Street Journal. Puzzles are parsed client-side into a JSON object which is used to generate the puzzle grid.

**ADD GIF**

The parser also allows for advanced puzzle features such as rebuses (multiple letters in a square), as well as circled grid squares.

**ADD IMAGE**

### Interactive Puzzle Grid
The puzzle grid is generated as a SVG object to allow for responsive scaling and clean presentation. Users can interact with the grid via mouse and keyboard, as well as navigate to any answer square by clicking the associated clue.

**ADD GIF**

### 

## Resources
* Documentation on the [ipuz](http://www.ipuz.org/) puzzle format 
* Reference to .puz file format spec: [docs](https://code.google.com/archive/p/puz/wikis/FileFormat.wiki)
