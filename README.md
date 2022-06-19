# Open Papyrus Compiler

> This project is still **WORK IN PROGRESS**. If you have any feature requests, head over to the [Issues](https://github.com/erri120/papyrus-compiler) tab and describe your needs. The [Compiler Explorer](https://papyrus-compiler-explorer.herokuapp.com/) website is also live however still very barebones.

The "official" Papyrus compiler that comes with the Creation Kit has some issues:

1) each game has a different language version (eg: F04 supports structs while Skyrim doesn't, F04 has `DebugOnly` and `BetaOnly` function flags and release modes but Skyrim has none of that)
2) the compiler does the minimum amount of work required to produce an output 

The CK compiler provides no meaningful errors, has no code analysis, does not optimize the output and requires the CK to be installed. The Open Papyrus Compiler will have a strong focus on analysis and optimization to produce high performance scripts.

## Documentation

The entire documentation is available [here](https://erri120.github.io/papyrus-compiler/).

## Contributing

See [CONTRIBUTING](CONTRIBUTING.md) for more information.

## Credits and Resources

- [Orvid/Caprica](https://github.com/Orvid/Caprica): Existing Papyrus compiler for F04, written in C++
- [cadpnq/papyrith](https://github.com/cadpnq/papyrith): Existing Papyrus compiler, written in Common Lisp
- [cadpnq/papyrithjs](https://github.com/cadpnq/papyrithjs): Pex decompiler and optimizer, written in Common Lisp
- [joelday/papyrus-lang (Wiki)](https://github.com/joelday/papyrus-lang/wiki/Papyrus): Papyrus Wiki
- [Creation Kit](https://www.creationkit.com/index.php?title=Category:Papyrus): Papyrus Wiki
- [joelday/papyrus-lang](https://github.com/joelday/papyrus-lang): VSCode Extension for Papyrus
- [blu3mania/npp-papyrus](https://github.com/blu3mania/npp-papyrus): Notepad++ Plugins for Papyrus
- [Mutagen.Bethesda.Core.Pex](https://github.com/Mutagen-Modding/Mutagen/tree/dev/Mutagen.Bethesda.Core/Pex): Pex parser, written in C#
- [UESP](https://en.uesp.net/wiki/Skyrim_Mod:Compiled_Script_File_Format): Wiki page on the Pex format for Skyrim
- [Orvid/Champollion](https://github.com/Orvid/Champollion): Pex decompiler for F04, written in C++
- [MrOctopus/nl_mcm sources](https://github.com/MrOctopus/nl_mcm/tree/main/main/source): Example scripts
- [schlangster/skyui sources](https://github.com/schlangster/skyui/tree/master/dist/Data/Scripts/Source): Example scripts
- [Sairion350/OStim sources](https://github.com/Sairion350/OStim/tree/main/Scripts/Source): Example scripts

## License

MIT, see [LICENSE](LICENSE) for more information.
