# Project: JavaScript Application Log

## Summary

Implement a client-side application log with a revealable user interface. The implementation should be modular so that it can be used in several web applications.

Use index.html to demonstrate the logging solution. 


## User Story

* 


## Acceptance Criteria

* 


## Programming Interface

An instance of the Log object should provide a method for each of four log entry severity levels: debug, info, warning, error.

* `debug(moduleName, message)`

* `info(moduleName, message)`

* `warning(moduleName, message)`

* `error(moduleName, message)`


`moduleName` is a string indicating the section of the application that generated the log entry. This will often be the name of a module.

`message` is the string of text to be logged.

Assuming that `log` contains an instance of the Log object, the following statement should add a log entry that represents an error in MyModule.

	log.error('MyModule', 'Something bad happened.');


## User Interface 
