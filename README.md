# Design Patterns in TypeScript #

Here are the implementations of the following design patterns in TypeScript:

### Creational ###

* [Singleton](https://github.com/torokmark/design_patterns_in_typescript/tree/master/singleton)
* [Abstract Factory](https://github.com/torokmark/design_patterns_in_typescript/tree/master/abstract_factory)
* [Factory Method](https://github.com/torokmark/design_patterns_in_typescript/tree/master/factory_method)
* [Builder](https://github.com/torokmark/design_patterns_in_typescript/tree/master/builder)
* [Prototype](https://github.com/torokmark/design_patterns_in_typescript/tree/master/prototype)


### Structural Patterns ###

* [Adapter](https://github.com/torokmark/design_patterns_in_typescript/tree/master/adapter)
* [Bridge](https://github.com/torokmark/design_patterns_in_typescript/tree/master/bridge)
* [Composite](https://github.com/torokmark/design_patterns_in_typescript/tree/master/composite)
* [Decorator](https://github.com/torokmark/design_patterns_in_typescript/tree/master/decorator)
* [Facade](https://github.com/torokmark/design_patterns_in_typescript/tree/master/facade)
* [Flyweight](https://github.com/torokmark/design_patterns_in_typescript/tree/master/flyweight)
* [Proxy](https://github.com/torokmark/design_patterns_in_typescript/tree/master/proxy)


### Behavioral Patterns ###

* [Chain of Responsibility](https://github.com/torokmark/design_patterns_in_typescript/tree/master/chain_of_responsibility)
* [Command](https://github.com/torokmark/design_patterns_in_typescript/tree/master/command)
* [Interpreter](https://github.com/torokmark/design_patterns_in_typescript/tree/master/interpreter)
* [Iterator](https://github.com/torokmark/design_patterns_in_typescript/tree/master/iterator)
* [Mediator](https://github.com/torokmark/design_patterns_in_typescript/tree/master/mediator)
* [Memento](https://github.com/torokmark/design_patterns_in_typescript/tree/master/memento)
* [Observer](https://github.com/torokmark/design_patterns_in_typescript/tree/master/observer)
* [State](https://github.com/torokmark/design_patterns_in_typescript/tree/master/state)
* [Strategy](https://github.com/torokmark/design_patterns_in_typescript/tree/master/strategy)
* [Template Method](https://github.com/torokmark/design_patterns_in_typescript/tree/master/template_method)
* [Visitor](https://github.com/torokmark/design_patterns_in_typescript/tree/master/visitor)

## Compile the project

```
$ git clone https://github.com/torokmark/design_patterns_in_typescript.git
$ cd design_patterns_in_typescript
$ tsc
```

There is a new `tsconfig.json` file in the root direcotry which is responsible for the compiler options.
As it is set the default target is Ecmascript5 now.
Any additional options come here.

To compile only one pattern, use the following command.

```
$ cd design_patterns_in_typescript/visitor
$ tsc --target ES5 visitor.ts
```
>> Here if there is no `--outFile` option then the compiler generates the js counterpart into the current directory.
