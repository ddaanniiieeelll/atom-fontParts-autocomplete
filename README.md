# fontParts autocomplete for Atom

This package provides an autocomplete for the basic terms used while writing scripts for RoboFont.  
Use [this gist](https://gist.github.com/RafalBuchner/5affdfafc76785c637ea7c5d2a035787) of [RafalBuchner](https://github.com/RafalBuchner) to run python scripts from Atom and execute them inside Robofont.  

Since this is not an official Atom-package you can install it like this:

1. Clone this repo
2. Install apm (in Atom go to Atom -> Install Shell Commands)
3. Open the Terminal, navigate to the repo directory and run `apm link`
4. Back in Atom it should now be installed, you'll find it under Atom -> Preferences... -> Packages -> Community Packages

In the `intermediate.json` you'll find all the terms for autocompletion.
If you find something missing you can add it there.
Reload after you made changes with `ctrl`+`option`+`command`+`L`  

## Acknowledgements

- [RafalBuchner](https://github.com/RafalBuchner) who made it possible to run Robofont Scripts in Atom.
- [connordavenport](https://github.com/connordavenport) who first made an autocomplete package for Sublime Text. This is where I got the idea from.
- [lonekorean](https://github.com/lonekorean) who made an [atom-autocomplete-boilerplate](https://github.com/lonekorean/atom-autocomplete-boilerplate) upon which I  build this thing.
