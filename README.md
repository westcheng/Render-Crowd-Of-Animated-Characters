# AnimMap Baker For Animated Characters 
![GitHub](https://img.shields.io/github/license/chenjd/Render-Crowd-Of-Animated-Characters)
![](https://img.shields.io/badge/platform-win--64-brightgreen)
![](https://img.shields.io/badge/unity-2019.4%2B-brightgreen)
![Build my project](https://github.com/chenjd/Render-Crowd-Of-Animated-Characters/workflows/Build%20my%20project%20%F0%9F%98%8E/badge.svg)

#### Description：
Using GPU to implement large-amount animation characters rendering. The animation map for vertex shader to modify the vertex position of the mesh at runtime. Useing GPU instancing to reduce draw calls. 

#### Supporting Shadows
[![](https://i9.ytimg.com/vi/WUNq5sDMAg8/mq2.jpg?sqp=CMSGmpYG&rs=AOn4CLDPhbgagjKYE-ayuBFHznpgyUSQJQ)](http://www.youtube.com/watch?v=choBOPO1xgo "")


#### Using Unity’s AR Foundation to create 10,000 toy soldiers in the real world on an Old iPhone 7.
[![](http://img.youtube.com/vi/choBOPO1xgo/0.jpg)](http://www.youtube.com/watch?v=choBOPO1xgo "")


The initial version was released on GitHub on 30 Jul 2017, and of course, it is still on GitHub. However, if you can buy me **a cup of coffee**, I will be very
happy :-).

[:heart: Sponsor](https://github.com/sponsors/chenjd)

[:heart: Animation Baker and Instancing for Animated Characters on Asset Store](https://assetstore.unity.com/packages/tools/animation/animation-baker-and-instancing-for-animated-characters-183598)

Recently I added support for Unity 2021 and the Universal Render Pipeline (URP), so it can be used from Unity 5.x to Unity 202.

And I will create a video tutorial to demonstrate how to use it. If you want to know more about the implementation behind it, you can read this [article](https://medium.com/chenjd-xyz/how-to-render-10-000-animated-characters-with-20-draw-calls-in-unity-e30a3036349a) I wrote.

#### Features:

✅ Support Shadows.

✅ Using the animation map to modify the position of vertices of your characters at runtime to avoid a lot of cost of skin calculation.

✅ Using GPU Instancing to reduce the number of draw calls, only 20 draw calls are
needed to render 10,000 soldiers playing attack actions in the demo scene.

✅ Using the animation map to modify the position of vertices of your characters at runtime to avoid a lot of cost of skin calculation.

✅ Using GPU Instancing to reduce the number of draw calls, only 20 draw calls are needed to render 10,000 cats playing idle actions in the demo scene.

✅ Support AR Foundation.

✅ Support URP(SRP Batcher)only 7 draw calls are needed to render 10,000 cats playing idle actions in the demo scene.

#### Model Resource Link：

[RTS Mini Legion Footman Handpainted](https://www.assetstore.unity3d.com/en/#!/content/86576)

---
#### Bake legacy animation info into anim map：

![1201111111111111.gif](http://upload-images.jianshu.io/upload_images/1372105-004a0ddd0f256df1.gif?imageMogr2/auto-orient/strip)



![120111111111111.gif](http://upload-images.jianshu.io/upload_images/1372105-35954dfd4ca03f7b.gif?imageMogr2/auto-orient/strip)
animated characters without animator & skinnedmeshrender.

#### GPU Instancing & mesh render for large number of animated characters：
![1372105-fa2cb8df2d12c0b3.gif](http://upload-images.jianshu.io/upload_images/1372105-310c57df8cfc83bc.gif?imageMogr2/auto-orient/strip)
10,000 animated characters with 22 drawcalls.

#### BlogPost

[How To Render 10,000 Animated Characters With 20 Draw Calls In Unity](https://medium.com/@chen_jd/how-to-render-10-000-animated-characters-with-20-draw-calls-in-unity-e30a3036349a)

