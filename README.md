# eunoia
Eunoia planned to be an assistant and productivity tool that aims to centralize todos, scheduling, journaling, study aids, progress tracking, and task planning into a coherent, TUI-driven interface.

Eunoia will ideally be able to integrate tools such as email, notes, flashcards, and scheduling into a unified system that can run offline and respects user privacy. It is extensible and scriptable, allowing users to define their own workflows, commands, and automations.

Hopefully an easy-to-use API for eventual GUI interface if someone wants to make that. (I don't know how to write GUIs it always confuses me.)

## Planned Features

- TUI-based interface for productivity and assistant tasks
- Daily, weekly, and "eventually" scheduling with ease-of-use in mind
- Priority and focus task selection (e.g. "Pick 3 Things")
- Project tracking with percent-done and progress prediction
- Integration with emails, local notes (e.g. Google Keep export, markdown files, etc.)
- AI-assisted task sorting and generation (pluggable assistant)
- Diary / journaling support
- Flashcards and study planning system
- Mental health links and unstuck tools
- Flowchart-based decision helpers (what to do now?)
- Extensible architecture: add your own commands and automations

## Why?

Many productivity tools either cost money, or aren't very customisable and I've yet to find one that works very well with my workflow. Some have ads, many require too much manual effort to run. So, my solution was to make my own, for me, and for the sake of being helpful, let others see it.


## Installation
Will be using a makefile, and 

### Dependencies
See dependencies.txt

### Quick Install

```sh
git clone https://github.com/yourusername/eunoia.git
cd eunoia
make install
````

## Usage

```sh
eunoia
```

By default, the app launches a TUI. All configuration is stored under `~/.config/eunoia`.

## Contributing

All contributions are welcome. See the `CONTRIBUTING.md` for more details.

## License

MIT
