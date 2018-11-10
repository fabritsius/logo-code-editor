# Logo Code Editor

_inspired by:_ [Daniel Shiffman](https://github.com/shiffman)

[Logo](https://en.wikipedia.org/wiki/Logo_(programming_language)) was developed in 1967 and is mostly used as an educational programming language. This project is a browser interpreter of the Logo language and uses it's custom version. Full list of supported commands is available in the [documentation](https://fabritsius.github.io/logo-code-editor/docs/).

The code is interpreted live (after any change) and the main idea was to create a powerful and portable Logo Editor which allows to create `400x400` good-looking artworks with limited resources. Another important feature is the ability to share your work with friends via special `.logocode` file which can be easily exported and imported with the editor.

## Features

- uses a version of [Logo programming language](https://en.wikipedia.org/wiki/Logo_(programming_language));
- supports loops and simple methods (more in the [documentation](https://fabritsius.github.io/logo-code-editor/docs/));
- random [example](./examples) is shown each time webpage is reloaded;
- there is an option to save both your code and a generated image;
- you can Drag and Drop `.logocode` file right into the editor;
- works Offline after first load.

[**Open the editor**](https://fabritsius.github.io/logo-code-editor/)

## Logocoding Tips

- by saving your code regularly, you can use your Downloads folder as a simple version control (be safe);
- if you coded a great Art you can go to [./examples](./examples) and request you `.logocode` to be added;
- don't call a method inside of it's definition.


## Usage locally

1. Clone this repo (or obtain in other way);
2. In terminal go to the directory you have files in;
3. Enter `python3 -m http.server`;
4. Visit [localhost:8000](http://localhost:8000) in your browser;

  or just double click on `index.html` after saving and unzipping this repo.

## TODO

- [x] implement the core of Logo language parser
- [x] add `.logocode` shring system 
- [x] add support for simple methods
- [x] add documentation to the editor web page
- [ ] add more options for sharing

## Links

- [Coding Challenge #121: Logo Interpreter](https://www.youtube.com/watch?v=i-k04yzfMpw)
- [Logo (programming language)](https://en.wikipedia.org/wiki/Logo_(programming_language)) on Wikipedia
- [Google Color Picker](https://www.google.ru/search?q=color+picker+tool)