# Obvia

Obvia is an MIT-licensed open source Javascript framework created to make the development of single page applications as easy and obvious as possible. It is designed with the objective of being easy to work with, separating code from data, separating structural components (layout) from functional components and allowing embedded state and history management. Obvia consists of UI components, application and applets, general use libraries, and code generation utilities.

## Browser Compatibility

Obvia supports all browsers that are ES5-compliant (IE8 and below are not supported).

## Issues

Before reporting an issue, please read the [Issue Reporting Guidelines]. Issues that do not follow the guidelines may get closed.

## Want to Help?

If you would like to contribute some code or improve the documentation, please read our [Contribution Guidelines] then check out the current issues. Your work is always appreciated!

## Libraries

This is a list of all the open source libraries used in the Obvia framework.
[yaml.js]\
[tokenize.js]\
[micro-requirejs]\
[Deep Clone]\
[Get Font Awesome Icon from MIME]\
[Debounce decorator]\
[CSS hasStyleRule]\
[Coroutine]\
[MD5 (Message-Digest Algorithm)]

## Roadmap

This is a basic roadmap with some instructions to keep in mind when working with Obvia.

- The implementation class is to be named according to the applet anchor
- Implement the dependency injection
- Create a dependency info-structure
- Create a base-dependent type to return dependencies-related information (array of dependencies info-structure)
- Implementations will be dependent types
- Create a Factory Implementation to support the autowiring of dependencies
- Create the info structure for the types which the Factory will create/return instances of
- An Applet will not create the implementation instance directly but will ask the Factory for it
- The Applet (& App) should handle URL hash changes via an external dependency (the existing logic is to be wrapped in a default provider)
- The security is to be provided by external dependencies
