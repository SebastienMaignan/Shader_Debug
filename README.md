# Shader_Debugger
A small application to customize and debug opengl shaders (requires opengl 4.6).
It is based on Qt5, Imgui and ideas from shadertoy.
The 2 main features are:
- Add GUI dials and sliders to control uniforms in the shader. The control is created when you add a specific comment to the uniform line in your shader and save it.
- Debug variables in your shader: select the variable, add it to the list of whatched variables and start debugging. Then point a pixel in the opengl window and press 'v'. the variable for this pixel is displayed in the debug window.

![debugger](https://user-images.githubusercontent.com/80265822/110457468-f5c4da00-80ca-11eb-8740-fe3d059a9521.png)
