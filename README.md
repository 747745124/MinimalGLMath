### Minimal GL Math

A header-only, minimal library for common OpenGL or general rasterization-related math. Supports SIMD optimization. (Uses Neon counterpart on ARM machine)

* `matrix.hpp`
  * Matrix and vec classes
  * Conform to GLSL-style value assignment etc.
  * Currently only supports dimension up to 4.
* `quat.hpp`
  * Quaternion class uses for rotation
* `transformations.hpp`
  * Basic transformation functions that returns homogenous transformation matrix. Support MVP matrix in both left-handed coordinate system and right-handed coordinate system.