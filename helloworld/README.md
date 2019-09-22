## 1. To build project with cargo:

### 1.1. cd to project folder contain Cargo.toml file
```
cd ../helloworld
```

### 1.2 Run the build command

- If you want to build `debug` version

```
cargo build
```

- If you want to build `release` version:

```
cargo build --release
```

## 2. To run project with cargo:

### 2.1 cd to project folder output source and run

- For `debug` version:

```
./target/debug/helloworld
```

- For `release` version:


### 2.2 in case of using window, it will be:

```
.\target\debug\hello_cargo.exe
```

### 2.3 Shortcut

- The shortcut version for build and run will be:

```
cargo run
```

- If you only want to check (to see if the project can be built or not):

```
cargo check
```