# GHIP

Hacking tools suite. The idea is to code individual tools that could be used in this suite and then integrate them.

## Folders

It might look too much organization for that but as the team will grow, and more people will be working at the same time. This is going to save us a lot of time and brain power on the long run.

`/tools/` is the folder containing each tool individually. `/tools/blue/` represents the defensive tools, `/tools/red/` all the offensive tools, and `/tools/dev/` the tools to make development easier. Each tools is developed as a standalone then implemented into the main suite.

`/dev/` is the folder where we develop the main tool. These files are destined to be compiled into one.

`/dist` is the folder where the compiled version of the script is contained and all the files necessary to make it work properly such as text files, data files, etc... This is the stable version of the script.

## Blue Tools

#### zBounce

Server management tool. Run commands on your proxy servers.

## Red Tools

#### athena

Scans the whole internet for all existing exploits to compile them into a readable database.

#### hermes

Currently in nightly. Automatically hacks all WiFi and compile a report.

#### exploitZ

Automatic exploit of a target.

## Dev Tools

#### zCompile

Compiles files into one before compiling. Helps organize the code and reuse it in other projects.

**Usage:** ```zCompile dir_path main.src```

- `dir_path` is the folder where all the source files are located.
- `main.src` is the main file where the `#import` tags are located.

#### zLib

A library of general purpose scripts such as parsers or display to import in all small projects to make them easy to integrate to the suite.
