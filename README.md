# Project: JavaScript Application Log

## Summary

Implement a client-side application log with a revealable user interface. The implementation should be modular so that it can be used in several web applications.

Use index.html as a mock web application to demonstrate the logging solution.


## User Stories

* As a developer, I want to assign a severity level to the log entries that I generate so that I can indicate the rough importance of each entry. From lowest to highest severity, the levels should be `info`, `warning`, and `error`.

* As a web app user, I want the log panel to be hidden unless I explicitly reveal it.
* As a web app user, I want the log panel to alternately show and hide when I press the `L` key on my keyboard.
* As a web app user, I want the log panel to look nice so that it feels like part of a professional application.
* As a web app user, I want the log panel to appear as an overlay above the rest the web page so that there is plenty of room for the log content without affecting the layout of the web application.

* As a log panel user, I want all log entries to be captured regardless of whether the log panel is visible or hidden.
* As a log panel user, I want the oldest log entries to be shown at the top and the newest at the bottom.
* As a log panel user, I want each log entry to display the time added, severity level, module name, and message text.
* As a log panel user, I want to hide log entries below a severity level that I specify so that I can focus on the most important messages.
* As a log panel user, I want newly generated log entries to display automatically in the log panel so that I don't need to manually refresh anything.


## Acceptance Criteria

* 


## Programming Interface

An instance of the Log object should provide a method for each of three log entry severity levels: `info`, `warning`, and `error`.

* `info(moduleName, message)`

* `warning(moduleName, message)`

* `error(moduleName, message)`


The `moduleName` parameter is a string indicating the section of the application that generated the log entry. This will often be the name of a module.

The `message` parameter is the string of text to be logged.

Assuming that `log` contains an instance of the Log object, the following statement should add a log entry that represents an error in MyModule.

`log.error('MyModule', 'Something bad happened.');`


## User Interface 
