# Yet Another Terminal Image Viewer But This Time In Rust (YATIVBTTIR)

![demo1](https://user-images.githubusercontent.com/69741305/142180087-4f6f6125-137e-4833-9129-427ce78aad46.mp4)

Because there totally aren't hundreds of repos that do the same thing but better.
Displays RGB images in the terminal (terminal must have truecolor support).

## Building

```
git clone https://github.com/t0a5ted/YATIVBTTIR.git
cd YATIVBTTIR
cargo build --release
./target/release/yativbttir
```

#### Optional (BASH): Create Alias for easy access.
Add the following line to your `.bashrc` or `.bash_aliases`
```
alias tiv=./installdir/target/release/yativbttir
```
> change `installdir` to the root of your YATIVBTTR folder

Run YATIVBTTR with `tiv --help`

