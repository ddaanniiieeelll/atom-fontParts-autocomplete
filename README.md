# fontParts autocomplete for Atom

Use [this gist](https://gist.github.com/RafalBuchner/5affdfafc76785c637ea7c5d2a035787) of @RafalBuchner to run python scripts from Atom execute them inside Robofont

Based on @connordavenport's [Sublime-Completions](https://github.com/connordavenport/Sublime-Completions-) I made an autocomplete provider for Atom.

Since this is not an official Atom-package you can install it like this:

1. Clone this repo
2. Install apm (in Atom go to Atom -> Install Shell Commands)
3. Open the Terminal, navigate to the repo directory and run `apm link`
4. Back in Atom it should now be installed, you'll find it under Atom -> Preferences... -> Packages -> Community Packages

In the `intermediate.json` you'll find all the terms for autocompletion.
If you find something missing you can add it there.
Reload after you made changes with `ctrl`+`option`+`command`+`L`  
If you find something basic is missing and you add it please share it here as well so everybody can benefit from it.
