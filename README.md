# SQLite for Delphi and FreePascal / Lazarus

SQLite is a software library that implements a self-contained,
serverless, zero-configuration, transactional SQL database engine.
The source code for SQLite is in the public domain and is thus free
for use for any purpose, commercial or private.
SQLite is the most widely deployed SQL database engine in the world.

This package contains a complete SQLite API translation for Delphi and FreePascal / Lazarus,
as well as a simple Unicode-enabled object wrapper to simplify working with the database engine.

## Compatibility

- Delphi 7 and later
- FreePascal / Lazarus

## Installation

1. Unzip the package to a directory of your choice.
2. Add the **Source** directory to your IDE or project settings:
   - **Delphi**: 
     - **Global**: Add the path to *Library path* in the environment options.
     - **Project-specific**: Add the path to *Search path* in *Project Options*.
   - **Lazarus**: 
     - **Global**: Add the path to *Additional source search path for all projects* in the IDE options.
     - **Project-specific**: Add the path to *Other unit files* in *Project Options > Compiler Options*.

## Usage

To use the SQLite API directly, add the `SQLite3` unit to your `uses` clause.
If you prefer working with the object wrapper, use the `SQLite3Wrap` unit.

Make sure to distribute the appropriate shared library
(**sqlite3.dll** for Windows, **sqlite3.so** for Linux, etc.)
along with your executable.

## Credits

- [Yuri Plashenkov](https://github.com/plashenkov) — developer
- [Marek Mauder](https://github.com/galfar) — contributor
- [Alexander Kotliarskyi](https://github.com/frantic) — contributor

## License

This package is licensed under the [MIT License](LICENSE.md).
