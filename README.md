Our project used VS2013 Opencv 2.4.10 for matrix calculation.

There is a precompiled exe in main dir naming CS580HW4.exe.
It should work perfectly if opencv_core2040.dll and MFC x86 runtime library exists.
If you want to recompile it yourself, be sure to add Opencv header and static lib in VS2013 build and link option.

You could use Open command under File menu to import mesh data. Otherwise RunRender has nothing to draw(Mesh files are in objects directory).
You can try Demo command too, they automatically read mesh file as well as push suitable transform matrix making the objects looks better.

Matrix menu has transform and light controls. Effect can switch add-on functions. Just a remind that turn on texture map on ".obj" with no texture defined will simply makes the object brighter.

Need no explain on RunRender :)

Animation do 3-axle rotate, you can pause animation by press button again during animating. Paused Animation will occupy render and invalidate RunRender.