# Footprints

## Development
### General
* [GNU Coding Standards](https://www.gnu.org/prep/standards/standards.html)

### Initial setup (Linux)
* zsh, oh-my-zsh

* Essential components (build-essential, ...)

* ssh key generation

### WSL2
* WSL2 is based on Hyper-V, so this cannot be coexisted with CPU VT-x apps.
  * WSL2 + VM (X: VM uses VT-x)

* [Accelerated KVM guests on WSL2](https://boxofcables.dev/accelerated-kvm-guests-on-wsl-2/)

### VMWare + Ubuntu
* [Install Docker on Ubuntu [KOR]](https://keepdev.tistory.com/43)

* [Sharing Folder [KOR]](https://kinanadel.blogspot.com/2018/05/vmware.html)

### Docker
* [Docker without sudo [KOR]](https://blusky10.tistory.com/359)

## Programming Language
### Rust
* [How to resolve “unresolved import” in Rust when using VS Code?](https://stackoverflow.com/questions/60319273/how-to-resolve-unresolved-import-in-rust-when-using-vs-code)

* [Breakpoints Not Working With VS Code + Rust + LLDB](https://blog.dbrgn.ch/2020/12/20/rust-vscode-lldb-breakpoints-not-working/)

* Using [rust-analyzer](https://github.com/rust-analyzer/rust-analyzer) instead of Rust Language Server

### Python
* [virtualenv [KOR]](https://medium.com/@dan_kim/%ED%8C%8C%EC%9D%B4%EC%8D%AC-%EC%B4%88%EC%8B%AC%EC%9E%90%EB%A5%BC-%EC%9C%84%ED%95%9C-pip-%EA%B7%B8%EB%A6%AC%EA%B3%A0-virtualenv-%EC%86%8C%EA%B0%9C-a53512fab3c2)

### C++
* [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

* [Name mangling and extern "C"](https://5kyc1ad.tistory.com/343)

## Operating System Concepts
### Linux
* [VFS readahead](https://kernel.googlesource.com/pub/scm/linux/kernel/git/vfs/vfs/+/refs/tags/v2.6.32-rc1/mm/readahead.c): Readahead is a kind of VFS prefetching.
