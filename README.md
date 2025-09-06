# PCGExperiments
A collection of Unreal Engine experiments exploring Procedural Content Generation techniques using PCG graphs and custom tools.

## GPU Texture

![](https://raw.githubusercontent.com/proceduralit/PCGExperiments/main/Wiki/GPUTexture/Smile.png)

In this experiment, I explored the power of the GPU Texture node in PCG, using it to sample color data from a texture and drive the procedural spawning of various static meshes according to those sampled values.

To maximize performance, I kept the entire process on the GPU and avoided costly CPU data transfers.

[A Brief Overview](https://github.com/proceduralit/PCGExperiments/wiki/GPU-Texture)

## Book Row Stacker

![](https://raw.githubusercontent.com/proceduralit/PCGExperiments/main/Wiki/BookRowStacker/BookRowStacker.png)

Procedurally generating a row of books in Unreal Engine using PCG is fairly straightforward, but handling gaps and calculating lean angles was a fun challenge.

[A Brief Explanation Of PCG Graphs](https://github.com/proceduralit/PCGExperiments/wiki/Book-Row-Stacker)
