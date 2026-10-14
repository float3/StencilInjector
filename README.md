# StencilInjector

Unity editor tool that rewrites a shader with stencil support. select a shader, run **Assets > Inject Stencils**, and a copy is written with `_Stencil*` properties and a `Stencil` block in every pass. built-in shaders are resolved from the bundled `builtin_shaders-2019.4.28f1.zip`.

## install

copy `StencilInjector/` into `Assets/`. editor only, nothing ships in builds.

parser and preprocessor come from [Lyuma's ShaderTools](https://github.com/lyuma/LyumaShader/tree/dev/ShaderTools); see `Editor/LICENSE`.
