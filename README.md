# IO口说明
USB摄像头接入后默认为`video0`,在OpenCV调用就是`cv2.VideoCapture(0) `

舵机根据电路图来看自己分配，我用的是23和11，对应J1和J2

# 调整角度
可以先用程序把舵机调到90度再安装摄像头，就比较正

由于亚克力板有点阻挡，竖直方向的那个舵机经我测试旋转范围在0-120度
