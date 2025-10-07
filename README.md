# Week 8 Quiz – Artwork idea Exploration

## Part 1: Imaging Technique Inspiration

The artistic inspiration for this final art programming project stems from the sci-fi film 《Blade Runner 2049》. Through the ingenious use of color, light and shadow, combined with a hazy visual effect, the film constructs a uniquely cyberpunk-style scene. The film employs light reflections piercing through dust particles and neon light scattering, with intense color contrasts delivering exceptional visual impact. This showcases an advanced technological society alongside a decaying cyber world. Inspired by this, I sought to apply its visual layering to my final artistic creation. Through experiments with gradient colors, transparency, and shifting luminous hues, I utilized tonal variations and light-dark contrasts across different visual layers to achieve this programming contrast.

![Scene 1](https://image.tmdb.org/t/p/original/8QXGNP0Vb4nsYKub59XpAhiUSQN.jpg)

![Scene 2](https://image.tmdb.org/t/p/original/uKbX1ha7KWyTecvpPpRCB3iFfj3.jpg)


## Part 2: Coding Example

As for the technique used in the image，we can use p5.js.When coding In p5.js, the holographic neon look can be achieved by combining additive blending, bloom blur, RGB color offset, and scanline shaders. Bright areas are isolated and blurred to create glow, while slight channel shifts produce digital fringes. Scanline and noise textures simulate holographic projection, and exponential fog softens the edges to create depth.The method above could reproduce an effect visually similar to the image.

This shows a shader effect in p5.js that demonstrates how it look like.
![p5.filterShader Example](https://github.com/BarneyWhiteman/p5.filterShader/raw/main/example_posterise.png)

**Example implementation**

-[Code Example 2](https://github.com/aferriss/p5jsShaderExamples)

-[Code Example 3](https://codepen.io/kekkorider/pen/yRvbzm)
