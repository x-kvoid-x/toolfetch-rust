# toolfetch-rust
toolfetch GUI in rust

build instructions:  
```
git clone https://github.com/x-kvoid-x/toolfetch-rust
cd toolfetch-rust
cargo build --release
```
the executable will be in target/release/  

# dependencies
**druid**   (gui toolkit)  
**libmath** (round function)  
**winapi**  (dialog function)  

*platform-specific:*  
**num_cpus** [macos] (get cpu cores)

---  
# TODO  
- [x] *disk info* segment to UI  
- [x] linux/mac support
- [ ] light theme
- [ ] add taskbar icon
