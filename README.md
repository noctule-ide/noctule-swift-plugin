## Cross-Platform Swift Development with your JetBrains IDE

**Noctule brings cross-platform Swift language support to your JetBrains IDE and Android Studio.**

> [!IMPORTANT]
> This plugin is a freemium plugin. For now, all features are still free to use. Support the development by purchasing a license for USD 1 per month.
> At this time, all features are free to use until the plugin is more stable.
> Noctule will be offered as a freemium or paid plugin in the future.>Please note that the final price will be higher when the product is stable.

<a target="_blank" href="https://lists.j-a.dev/subscription?f=fUWUAxYS1O09VBQtL0S0YJrJHotnoE7f35nm892D9KiINm3fsOPw9MTMtRSzN2PDzK">
Join the Noctule newsletter</a> to receive updates about the plugin and its development.
<br>
<br>

**[Please join the discussions](https://github.com/noctule-ide/noctule-swift-plugin/discussions) to shape the future of this plugin.**
<br>
<br>

**Available features**:

- Support for the language specification of Swift 6.2
- Native code formatter
- Code completion
- Find usages, go to declaration, rename refactoring
- Code error highlighting with quick fixes
- Inlay hints for types and parameters
- Structure view
- Type hierarchy (supertypes, subtypes, or both in a single hierarchy)
- Call hierarchy (callees (outgoing calls), callers (incoming calls))
- Support for "Go to class" and "Go to symbol"
- Quick documentation with colored rendering of embedded code blocks
- Code folding with custom settings for default code folding
- Language injection support for string and multiline string literals
- File templates for common Swift declarations
- Syntax highlighting, including semantic token highlighting
- Color schema settings
- ToDo item highlighting
- Navigation bar support
- Brace matching for `()`, `{}`, `[]`
- Comment support

Most of the features rely on Apple's `sourcekit-lsp` and need an installed Swift toolchain.
The implementation was tested with the current stable version of Swift.

<br>
<br>

**Known limitations** of the already available features:
- Renaming a function declared in a `protocol` does not yet rename all implementations of this function.
