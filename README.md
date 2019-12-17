# ArduinoJS 
ArduinoJS is a Arduino IDE Library that provides a "JavaScript VM Engine" hosted on top of the Arduino IDE environment. This allows adding JavaScript scripting functionality within an Arduino Sketch.

Unlike other microcontroller JavaScript implementations, ArduinoJS does not try to replace the Arduino development environment with a bare metal JavaScript framework or try to implement a full JavaScript framework with a parser,compiler, or repl ... no modules trying to handle all aspects of the microcontrollers hardware. 

Rather, ArduinoJS takes a simpler approach by only implementing a bare minimal JavaScript VM environment that is built up from and leveraging the Arduino IDE existing libraries and framework. Also, ArduinoJS only has a bytecode interpreter virtual machine engine ... no eval() or REPL ... per say ... but any bytecode can be executed either from ram, rom, or flash ... a full c function interface is provided to map existing Arduino code into the JavaScript environment ... as well as the ability to call Javascript (Bytecode) from Arduino sketches.



**Resources**

https://github.com/svaarala/duktape

https://github.com/jerryscript-project/jerryscript

https://github.com/Moddable-OpenSource/moddable
