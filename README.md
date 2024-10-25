# ElectroverseSwiftLintConfig
A repository for [SwiftLint](https://realm.github.io/SwiftLint/) configurations to be shared by Electroverse projects.

## Usage
> [!WARNING]
> Swift Package Manager plugins are not able to make network requests, and so using a remote parent config file does not work with [SwiftLintPlugins](https://github.com/SimplyDanny/SwiftLintPlugins) -  https://github.com/realm/SwiftLint/issues/4787.

Set the `parent_config` in `.swiftlint.yml` like so:

```yml
parent_config: https://raw.githubusercontent.com/octopus-energy/ElectroverseSwiftLintConfig/<version>/.swiftlint.yml
```
