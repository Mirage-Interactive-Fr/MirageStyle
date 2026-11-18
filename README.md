# MirageStyle

Mirage is Mirage Interactive's Julia formatting style for Étendue 3D projects.

Projects ship [JuliaFormat.toml](JuliaFormat.toml) at their root. Open the project in VS Code with the official Julia extension and run **Format Document**. The extension loads the configuration automatically.

Mirage builds on JuliaFormatter's Blue preset. The `style = "blue"` setting selects that preset, and `[options]` applies the Mirage rules. [Julia extension formatting guide](https://www.julia-vscode.org/docs/stable/userguide/formatter/)

## Acknowledgments

Thanks to the JuliaDiff contributors who wrote the Blue style guide and to the JuliaFormatter.jl contributors who implemented its `BlueStyle` preset. The Mirage formatting rules build on their work. [Blue style guide](https://github.com/JuliaDiff/BlueStyle) · [JuliaFormatter.jl](https://github.com/JuliaEditorSupport/JuliaFormatter.jl)
