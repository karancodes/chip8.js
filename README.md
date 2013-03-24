# Chip8.js

Chip8.js aims to bring CHIP8 emulation to the browser and node.js.

## Demo

Currently, the demo doesn't support Internet Explorer.

http://reu.github.com/chip8.js

## Running the tests

The emulator is almost completely covered with automated tests. You can run the CPU tests using node, with the `test` task:

    $ make test

To run the Keyboard and emulator tests, you must run the suite in the browser.

    $ make test-browser

And then accessing http://localhost:3000/test/tests.html URL.

You can also run the tests online by following http://reu.github.com/chip8.js/test/tests.html

## Documentation

The documentation is located in the `doc` folder, and can be found online at http://reu.github.com/chip8.js/doc

It is generated by YUIDoc, so if you need to update it, make sure you have it installed:

    $ npm install yuidocjs

Then, to generate the documentation, just run:

    $ make documentation

# License

MIT License. Copyright 2013 Rodrigo Navarro. http://rnavarro.com.br
