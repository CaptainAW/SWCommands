# SWCommands


Compact framework for building application on Unity. The basic idea is to use a command structure to support the MVC approach.
The controller layer is implemented through a command structure consisting of entities of several types, such as:
 - Command: simple (synchronous) command
 - AsyncCommand: command, that takes some time to complete.
 - MacroCommand: a command can consist of a set of other commands of any type, including synchronous, asynchronous and macro.

Based on the <a href="https://github.com/modesttree/Zenject">Zenject</a> DI framework.
