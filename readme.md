# Data Pack Template

A basic data pack template for creating minecraft data pack functions.

## Installation
Click the ```Code``` button at the top of the page and click ```Download ZIP``` option. After the download extract the first folder and place it in a minecraft save's datapacks folder.

## Getting Started
1. **Replace the following files' contents from ```template``` to ```YOUR DATA PACK NAME```;**

- ./data/minecraft/tags/functions/load.json
- ./data/minecraft/tags/functions/tick.json

e.g: Suppose you package name is my-awesome-package
```json
{
    "values": ["template:load"]
}
```
```json
{
    "values": ["my-awesome-package:load"]
}
```
2. **Replace the following folder names to ```YOUR DATA PACK NAME```;**

- ./data/template

e.g: Suppose you package name is my-awesome-package

./data/my-awesome-package

3. **Write your data pack**

## Documentation

For sytax documentation, see [official wiki](https://minecraft.fandom.com/wiki/Function_(Java_Edition))

## License

Copyright 2021 Muhammed Ali CAN

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.