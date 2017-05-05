# NEON
A class library for implementation of NEON UI in your UWP app.

NOTE : THIS RUNS ONLY ON RS2 BUILDS OR ABOVE.	

How to use it in your own projects:

First add the "SamplesNative" and "SamplesCommon" project to your solution, then reference them to your host project.

Then add these two files (Noise.jpg & Noise.png) to the "Assets" folder in your host project which is in Sample project. 
After that set initializer to your MainPage's code behind. So add this code in your constructor:

            ImageLoader.Initialize(ElementCompositionPreview.GetElementVisual(this).Compositor);

Then use the controls in your XAML :

            xmlns:Neon="using:SamplesCommon"

			<Neon:HostBackDrop BlurAmount="30" />

			




DONE !
You have some other controls. Like HostBackDrop which is for making a blur window container, BackDrop which is for making a blur control and other controls which are documented on Windows UI Labs.


This sample and controls are drived from Windows UI Labs.

Credits:
Microsoft Windows UI Labs,
MAH Studio,
Gustave M

Don't forget to credit us in your project ;)
