# cosmos

## Reference
[Juno](https://docs.junonetwork.io/juno/readme)
[cosmwasm](https://docs.cosmwasm.com/docs/1.0/)
[cosmos sdk](https://docs.cosmos.network/)

## Run
### Build
```
cargo build --all
```

### Format
Install the nightly version of rustfmt
```
rustup toolchain install nightly
```
To install:
```
rustup component add rustfmt --toolchain nightly
```
To run:
```
cargo +nightly fmt
```

### Lint
Install the nightly version of rustfmt
```
rustup toolchain install nightly
```
To install:
```
rustup component add clippy --toolchain nightly
```
To run:
```
cargo clippy --all --all-targets --release
```

### Test
```
cargo test -all
```

### How to contribute
1. Fork this repository.
2. Clone your forked repository in your local environment.
3. Stack commits locally for a single PR (It should represent one topic).
4. After finishing writing code, run [formatter](#format), [linter](#lint), and [test](#test).
5. Push the commits to the remote forked repository.
6. Go to the forked repository web page and make a PR to this repository.
7. Add posgnu and junha1 as reviewers and ping them in the discord server.