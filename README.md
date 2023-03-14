# hw_os
> Simples kernel em rust que mostra "Hello World" e nada mais.

Você vai precisar da toolchain nightly do Rust e da dependencia `bootimage`.

Baixe o `bootimage` com:

```bash
$ cargo install bootimage
```

Depois disso, compile:

```bash
$ cargo build
```

Pra rodar em VM, você vai precisar do `qemu-system-x86_64`. Então, rode:

```bash
$ cargo run
```
