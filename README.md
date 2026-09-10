# StencilInjector

Unity editor tool that rewrites a shader with stencil support. Select a shader, run **Assets > Inject Stencils**, and a copy is written with `_Stencil*` properties and a `Stencil` block in every pass. Built-in shaders are resolved from the bundled `builtin_shaders-2019.4.28f1.zip`.

## Install

Copy `StencilInjector/` into `Assets/`. Editor only, nothing ships in builds.

Parser and preprocessor come from [Lyuma's ShaderTools](https://github.com/lyuma/LyumaShader/tree/dev/ShaderTools); see `Editor/LICENSE`.
