# Developer Productivity Scripts

Based on [Frontend Masters - Developer Productivity v2](https://frontendmasters.com/courses/developer-productivity-v2)

## Goal

A simple bash script runner for automating development workflows and tasks.

## How to Run

Execute all scripts in the `runs/` directory:
```bash
./run
```

Filter specific scripts:
```bash
./run neovim
```

Dry run to preview what will execute:
```bash
./run --dry
```

## Adding Scripts

Add executable bash scripts to the `runs/` directory. They will be automatically executed by the `run` command.
