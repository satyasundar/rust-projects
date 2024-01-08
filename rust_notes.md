# Chapter 1

## Installation

    rustc --version
    rustup update
    rustup self uininstall (for uninstalling)

    rustup doc

## Hello World

    rustc --version

    mkdir hello_world
    cd hello_world

    rustc main.rs
    ./main

## Cargo

    cargo --version

    cargo new hello_cargo
    cargo new --vcs=git hello_cargo (if already a git repo)
    cargo new --help

    cargo build
    cargo run
    cargo check

    cargo build --release

# Chapter 2

## Guessing Game project

    cargo new guessing_game
