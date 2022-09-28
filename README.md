# Hypertext system based on YAML Xanadoc documents

This repository implements a minimal hypertext system following conventions laid out at <https://jakobib.github.io/hypertext2019/> and <https://doi.org/10.1145/3342220.3344922>.

## Installation

Source code is available from <https://github.com/nichtich/xanadoc-demo>.

    git clone https://github.com/nichtich/xanadoc-demo.git
    cd xanadoc-demo

The system is implemented in Perl. Run

    cpanm --installdeps .

to install required Perl modules.

## Usage

Execute `./xanadoc` with a Xanadoc file as first argument, e.g.

    ./xanadoc example.yml

The default output is plain text with transcluded document selections
marked by `[[` and `]]`. More sophisticated output formats with support
of links are yet to be implemented.

Xanadoc file format is based on YAML (see `example.yml`).

## License

Use as you like but proper citation is welcome!
