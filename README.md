# Shader_Debugger
A small application to customize and debug opengl shaders.
It is based on Qt5, Imgui and ideas from shadertoy.
The 2 main features are:
- Add GUI dials and sliders to control uniforms in the shader. The control is created when you add a specific comment to the uniform line in your shader and save it.
- Debug variables in your shader: select the variable, add it to the list of whatched variables and start debugging. Then point a pixel in the opengl window and press 'v'. the variable for this pixel is displayed in the debug window.

