# github2orgmode
Download a list of issues from Github and write them to an org-mode formatted
file

## What is this?

github2orgmode downloads a project's entire list of issues, and writes them to
a single plain-text file in [Org mode](http://orgmode.org) format.

The result, in a [suitable viewer](http://www.orgzly.com), might look something
like this:

![Orgzly Screenshot 1](https://github.com/Matrixcoffee/github2orgmode/raw/master/OrgzlyScreen1.jpeg)

## Why would one want this?

The goal is to keep a local copy of all issues on my phone, for quick and
efficient search and review. This program's output can be used with the
[Orgzly](http://www.orgzly.com)
[app](https://f-droid.org/repository/browse/?fdid=com.orgzly) (see screenshot).

## Status

This software is pre-alpha, and not useful yet, not even to the author (me).

## How do I use this?

Please see **Status**. This software is not ready for use. That said, for the
stubborn:

1. Download or check it out anywhere.
2. Run it:
```
python3 github2orgmode.py owner/repo > output.org
```
3. Be amazed at all the ways in which it doesn't work yet.

## Compatibility

This software should run on any stable python 3 interpreter, in a unixy
environment. If not, please file an
[issue](https://github.com/Matrixcoffee/github2orgmode/issues/new). Running in
a non-unixy environment might be considered if the needed adjustments are
minor, in the author's opinion.

This software is written to be compatible with
[Tails](https://tails.boum.org/), but it is not be required.

## Contributing

There will soon be a
[CONTRIBUTING.md](https://github.com/Matrixcoffee/github2orgmode/blob/master/CONTRIBUTING.md)
(#2)

Please note that the latest code lives on the `develop` branch. Stable releases
will appear on `master`.

## Acknowledgements

This repository contains an embedded copy of
[PySocks](https://github.com/Anorov/PySocks) (formerly SocksiPy), taken from
https://raw.githubusercontent.com/Anorov/PySocks/d0eb45b80145bec982bfb551910312b886967be3/socks.py.
See [socks.py] for details.

## Author

[Matrixcoffee](https://github.com/Matrixcoffee)

## Contact

This project has a dedicated matrix room at
[#github2orgmode:matrix.org](https://matrix.to/#/#github2orgmode:matrix.org)
where you can discuss the project and ask questions.

The author can be privately contacted via matrix:
[@Coffee:matrix.org](https://matrix.to/#/@coffee:matrix.org).

## License

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.

The full text of this license can be found in the file called
[LICENSE](https://github.com/Matrixcoffee/github2orgmode/raw/master/LICENSE).
