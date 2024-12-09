<div align="center">

# Renderer

</div>

## Table of Contents
- [Renderer Selection](#renderer-selection)
- [Renderer Comparison](#renderer-comparison)

## Renderer List

- [holy(gl4es)](https://github.com/FCL-Team/Holy-GL4ES)
- [zink](https://docs.mesa3d.org/drivers/zink.html)
- LTW(tiny wrapper)
- To be added...

## Renderer Selection

### 1. Performance-oriented Selection

- For versions below 1.17, always choose holy. For versions 1.17 and above, choose ltw (use in special cases such as with sodium) or holy.
- If you still feel it's not enough, you can use the [Vulkan mod](https://www.mcmod.cn/class/6626.html) (Minecraft Wiki) to get the best frame rate.

### 2. Compatibility-oriented Selection

- Choose zink, but you will sacrifice a significant amount of frames.
- Compatibility comparison: zink > ltw > holy

## Renderer Comparison

|   | holy(gl4es) | zink | LTW(tiny wrapper) |
| --- | --- | --- | --- |
| Compatibility | Average | Good | Good |
| Performance | Good | Poor | Good |
| Features | Default choice, strong optimization | Strong compatibility, sacrifices frame rate | Compensates for holy's lack of compatibility, strong optimization |

To be added...
