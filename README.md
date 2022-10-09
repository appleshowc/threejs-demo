# threejs-demo

## 全景图切换

### [PanoramaBox](panorama/PanoramaBox.html)

模仿百度全景，添加箭头指示标。点击箭头时，实现简单的背景切换。
![1662349801486](imgs/README/1662349801486.png)

### [PanoramaMultiCamera](panorama/PanoramaMultiCamera.html)

在 `PanoramaBox` 的基础上分屏，以上帝视角观察全景盒子
![1662356494085](imgs/README/1662356494085.png)

### [PanoramaShader](panorama/PanoramaShader.html)

利用着色器实现全景图`淡入淡出`切换
![1662359834049](imgs/README/1662359834049.png)

### [Panorama](panorama/Panorama.html)

利用 `tween.js` 实现全景图`淡入淡出`切换
**注意：**当前版本发现 `BoxGeometry` 材质使用透明模式时，无法与其他物体叠加生效，待解决
