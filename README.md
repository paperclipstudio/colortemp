# colortemp.rs

Simple functions to calculate color temperatures and RGB values.

Conversion uses work found at [[https://tannerhelland.com/2012/09/18/convert-temperature-rgb-algorithm-code.html]]

```rust
extern crate colortemp;

let mut rgb = colortemp::temp_to_rgb(2000);
println!("{:?}", rgb);
```
