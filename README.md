[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025, 2026  Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (------------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the GNU Affero)
[comment]: <> (General Public License as published by the Free)
[comment]: <> (Software Foundation, either version 3 of the License.)

[comment]: <> (This program is distributed in the hope that it will be)
[comment]: <> (useful, but WITHOUT ANY WARRANTY; without even the)
[comment]: <> (implied warranty of MERCHANTABILITY or FITNESS FOR)
[comment]: <> (A PARTICULAR PURPOSE. See the)
[comment]: <> (See the GNU Affero General Public License for)
[comment]: <> (more details.)

[comment]: <> (You should have received a copy of the GNU Affero)
[comment]: <> (General Public License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# Distributed Encoder (`distributed-encoder`)

Linearly scalable video encoder which distributes workload
across an array of devices.

The program is written in GNU Bash using the
[Crash Bash](
  https://github.com/themartiancompany/crash-bash)
library.

Videos to encode are split using the `mediaclip` program from the
[Media Tools](
  https://github.com/themartiancompany/media-tools) library
and sent to devices through SSH using
[DynSSH](
  https://github.com/themartiancompany/dynssh).

## Installation

The encoder
can be installed from source using GNU Make.

```bash
make \
  install
```

The encoder has been officially published
on the the uncensorable
[Ur](
  https://github.com/themartiancompany/ur).

A censorable
[Gur](
  https://github.com/themartiancompany/gur)
mirror is available at
[`distributed-encoder-ur](
  https://github.com/themartiancompany/distributed-encoder-ur).


## License

Distributed encoder is released by Pellegrino Prevete
under the terms of the GNU Affero General Public License
version 3.

