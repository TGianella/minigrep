# Minigrep

A rust-implemented copy of grep, done following the Rust guidebook. It searches a file for a given string and returns all lines which matches the string.

## Installation

`git clone` the repo.

## Executing

`cargo run -- searchstring file_path_to_search`
Set environment variable IGNORE_CASE to 1 to perform case insensitive search (`IGNORE_CASE=1 cargo run -- ...`)
