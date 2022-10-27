# fontforge-typeconv.rlib

Rudimentary routines for the conversion of FontForge types, like `SplineSet`, to Rust types like e.g. `glifparser::Outline<T>`, itself able to become a `kurbo::BezPath` or a `Skia::Path`.
