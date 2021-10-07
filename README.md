# minigrep
 Minimal version of grep command implemented on Rust

## Test
Run the command: `cargo test`

## Run
Run the command: `cargo run <query> <file path>`, for example: `cargo run to poem.txt`
To write the result to a file: `cargo run to poem.txt > output.txt`

## Toggle case sensitive
To change to case insensitive mode set inveronment variable `CASE_INSENSITIVE`: `$Env:CASE_INSENSITIVE=1; cargo run to poem.txt`
