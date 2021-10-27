![logo](images/thelema-logo-256.png)
### Thelema Engine

[![Awesome Kotlin Badge](https://kotlin.link/awesome-kotlin.svg)](https://github.com/KotlinBy/awesome-kotlin)

**Thelema** is multiplatform 3d graphics engine on Kotlin. It was based on libGDX sources and completely redesigned.

#### Download

Enter your credentials to download engine libraries.
[How to get token.](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

```kotlin
repositories {
    mavenCentral()
    maven {
        url = uri("https://maven.pkg.github.com/zeganstyl/thelema-engine")
        credentials {
            username = "username"
            password = "token"
        }
    }
}
```
```kotlin
dependencies {
    implementation("app.thelema:thelema-jvm:0.6.0")
}
```

[Quick Start](https://github.com/zeganstyl/thelema-engine/wiki/Quick-Start)

[Live TeaVM tests](https://zeganstyl.github.io/thelema-teavm-tests/)

[Live Kotlin/JS tests](https://zeganstyl.github.io/thelema-kxjs-demo/)

[Thelema vs LibGDX](https://github.com/zeganstyl/thelema-engine/wiki/Thelema-vs-LibGDX)

[![youtube](images/youtube.png)](https://www.youtube.com/playlist?list=PLS4PI9m5p5MmodmfBNVft1_mUges3x35O)

#### Features
* Shaders
  * Autogenerating shaders by shader nodes
  * Deferred shading
  * Physicaly based rendering (PBR)
  * Emissive materials
  * Tonemapping
  * Bloom
  * SSAO
  * Cascaded shadow mapping
  * Motion blur
  * IBL
* 3D graphics
  * VBO, VAO, Instancing buffers
  * Skinned meshes
  * Lights: directional, point
  * glTF 2.0 loading
* Audio
  * Ogg/Vorbis loading
  * WAV loading
  * Procedural sound generation
* JSON
* Image loading from JPG, PNG, TGA, BMP, PSD, GIF, HDR, PIC
* ODE physics
* Platforms: Desktop JVM, HTML5, Android

#### Work in progress
* 3D Editor
* HTML5 rigid body physics
* GUI (redesign)
* Audio API (redesign)

#### Things that may be implemented in future
* Vulkan API
* Kotlin/Native
* Navigation mesh
