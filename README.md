# Base16 Egui
This is a [Base16](https://github.com/base16-project/base16) theme template for styling the [Egui](https://www.egui.rs/) UI library (version 0.24).

After combining it with a colour scheme, copy the Rust file into your projcet and call `ctx.style_mut(|style| *style = style_from(style.clone()));` on your Egui context.
