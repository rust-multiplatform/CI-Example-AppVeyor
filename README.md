# Rust Multi-Platform CI Example for AppVeyor

This repository contains the required files to build your [Rust-Multiplatform] project on [AppVeyor].

## How to use this repository?

To build your project (clone or fork of [Rust-Multiplatform]) and simply add the `appveyor.yml` folder to your project folder following whatever method (copy, init-script, submodule, subtree, etc.) you deem best.

> ⚠️ Please note that you have to register at [AppVeyor] and activate your project before builds will happen.

## Compatibility note

This configuration is working with the [Base-Project-Template].  
Most of our projects _should_ work fine using this configuration, however a few may require additional dependencies and/or setups.
Refer to your clone/fork of [Rust-Multiplatform] for further information on what may need to be added.

[Rust-Multiplatform]: https://github.com/rust-multiplatform
[AppVeyor]: https://www.appveyor.com/
[Base-Project-Template]: https://github.com/rust-multiplatform/Base-Project-Template
