复杂三维模型显示实现内容
+ 支持三维模型文件格式：OBJ
+ 支持多个光源的光照效果，使用着色器渲染
    + 支持漫反射、高光、法线、高度贴图
    + 四个光源：红色、蓝色、绿色、白色
    + 光源位置在不同平面圆周旋转
+ 支持多种视点浏览方式
    + 以模型为中心的平移缩放旋转
        + 平移： 
            + 长按‘J’，向x轴正方向进行平移
            + 长按‘K’，向y轴正方向进行平移
            + 长按‘L’，向z轴正方向进行平移
        + 缩放：
            + 长按‘O’, 放大
            + 长按‘P’, 缩小
        + 旋转：
            + 长按‘Z’，以Z轴为轴对模型进行旋转
    + 以视点为中心的场景漫游：
        + ‘W’,‘S’，‘A’，‘D’前后左右移动

**OBJ格式模型**

![image](https://user-images.githubusercontent.com/44937001/211959845-89cb2a6a-d068-4f76-bd4a-1ef77b928513.png)

**多光源光照效果**

![still](https://user-images.githubusercontent.com/44937001/211963105-df75c4ca-97f9-481f-9c86-9a2e34148e4a.gif)



