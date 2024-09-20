# GitSetGo

## Function
1. `pregit` either clones or links a remote repository and branch to your current directory.
2. `postgit` pulls, commits, and force-pushes to the remote repository, stashing changes if needed.

## Support
GitSetGo supports POSIX-compliant OSes (cf. https://en.wikipedia.org/wiki/POSIX#POSIX-oriented_operating_systems).

## Setup
1. Optionally, add `pregit` and `postgit` to your PATH.
2. Ensure `pregit` and `postgit` are executable.
3. Ensure `git` is installed.

## Usage
1. Ensure the remote repository exists.
2. Ensure the remote repository includes a `.gitignore` file specifying potentially problematic hidden files (e.g. `.DS_Store` on MacOS).
3. Before work, run `pregit`.
4. After work, run `postgit`.
