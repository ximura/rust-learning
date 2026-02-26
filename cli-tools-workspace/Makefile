# Default target
all: build

build:
	cargo build

release:
	cargo build --release

run-rwc:
	cargo run -p rwc -- sample.txt

run-rgrep:
	cargo run -p rgrep -- sample.txt

test:
	cargo test

clippy:
	cargo clippy --all-targets --all-features -- -D warnings

fmt:
	cargo fmt

clean:
	cargo clean