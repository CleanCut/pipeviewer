# Hands On Systems Programming with Rust

Hands-On Systems Programming with Rust, Published by Packt

## Pipeviewer

This repository contains the code for the pipeviewer project that accompanies the
"Hands-on Systems Programming with Rust" online course I created for and published
through Packt.

This project replicates _some_ of the functionality of [pv], but the main focus of this
project is to walk students through a hands-on project to teach and demonstrate Rust
programming language features.  Each Git tag in this repository is for a commit that
corresponds to one of the training videos in the course, so you can walk through the
code tag-by-tag if you like along with the course.

I hope you find this repository and the companion course useful.  If you do, I
encourage you to check out [other courses, training, and projects that I do](https://agileperception.com). :wink:

I can be contacted via contact details on my website [agileperception.com].

[pv]: http://www.ivarch.com/programs/pv.shtml
[agileperception.com]: https://agileperception.com

## Update: 2022-06-17

- Tag the update as `update-2022-06-17`†
- Update from 2018 to 2021 edition of Rust†
- Update all deep dependencies with `cargo update`†
- Update `crossbeam` to version `0.8.1`†
- Update `crossterm` to version `0.23.2`. Required bringing `crossterm::style::Stylize` into scope in `stats.rs`, and changing `cursor::MoveToColumn(0)` to `cursor::MoveToColumn(1)`.

† No changes to the code were required for this step
