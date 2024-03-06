此为第五学期开设的ML课程项目，当时完成课堂展示后，便忙于处理期末考试，2024年春有闲暇时间，将其整理归档   


## 课程项目要求：
搜集训练数据，提取手写体汉字特征，训练机器学习模型，使其能够以较高的准确率分类汉字。   
测试数据由老师统一给出（共10张图像）


### 数据预处理
运行2preprocessing文件夹的 Datapreprocessing.ipynb 文件，完成数据预处理。  
注： 
1. 使用前需先创建一个储存处理后的空文件夹，并修改路径，否则只会显示已执行而看不到结果。
2. 腐蚀操作对于每个像素，将内核覆盖在图像上，然后计算内核覆盖区域内像素值的最小值，并将该最小值作为结果图像中对应像素的新值。这样，腐蚀操作会使图像中的物体**边缘变得更加锐利**，便于识别图像轮廓特征。

### 特征提取

ppt中介绍了￥种特征提取方法，




## 进一步工作：
项目在课堂上进行展示，老师提出改进意见：  
数据处理时二值化抹平了汉字图像光影等特征，而在实际的手写体识别任务中，光线阴影的变化是不可避免的。但是若使训练图片携带较多的光线阴影等特征，或许会降低模型预测精度。这一点有待进一步工作的考证。


## notes
1. This project was completed with November to December 2023, due to lack of time and the fact that this is only an undergraduate final course project. I would like to ask for your tolerance for any shortcomings in the project. Modifications are also welcome.
