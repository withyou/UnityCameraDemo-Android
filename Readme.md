# Unity Android Camera Demo

This demo use Camera1 api.

![](./screenshot.png)



## Build Android Plugin

cd to `AndroidPlugin` folder and run:

```
./gradlew buildAARForUnity
```
## Unity Player Settings insues
```
1.Disable Auto Graphics API and make sure only use OpenGLES2;(when accure GLError 1282)
```
```
2.Check if you have multithreaded rendering enabled. Disable it if so. 
```
