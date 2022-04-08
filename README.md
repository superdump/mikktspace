# mikktspace

This is a fork of https://github.com/gltf-rs/mikktspace, which in turn is a port of the [Mikkelsen Tangent Space Algorithm](https://en.blender.org/index.php/Dev:Shading/Tangent_Space_Normal_Maps) reference implementation to Rust. It has been forked for use in the [bevy game engine](https://bevyengine.org/) to be able to update maths crate dependencies in lock-step with bevy releases. It will be vendored in the [bevy repository](https://github.com/bevyengine/bevy) itself as `crates/bevy_mikktspace`.

Requires at least Rust 1.52.1.

## Examples

### generate

Demonstrates generating tangents for a cube with 4 triangular faces per side.

```sh
cargo run --example generate
```

## License agreement

Licensed under either of

 * Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license
   ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.
