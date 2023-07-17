# Lecture 1:Introduction of Deep Learning

## Machine learning $\approx$ **looking for function**
    
example: speech recognition, image recognition; Playing Go

## Different types of Functions

### Regression
The function outputs a scalar.(如预测明天的PM2.5浓度)  
### Classification
人类给出options(classes), the function outputs the correct one.(如判断是否是垃圾邮件：Yes/No)  
(Alpha go实际上也是个选择的问题，是不过选项非常多：each position is a class)  
### Strutured Learning
Create sth with structure(image,document)  
这个更难！  

## Case-study: Youtube Channel
目标：根据频道过往的咨询，预测将来某一天的观看次数？  
机器学习做这个事情有三个步骤：  

1. **Function with Unknown Parameters**  
初步猜测f长什么样子：假设Model是一个$y = b+w x_{1}$.  
$y$ is no. of views on 2.26 and $x_{1}$ is the no. of views on 2.25.  这两个叫做feature.  
$w$(weight) and $b$(bias) are unknown(learned form data).  
2. **Define Loss from Training Data**  
什么是Loss？  
Loss is a function of parameters $L(b,w)$  
Loss输出的值代表了how good a set of value is.  
计算$L(b,w)$的预测值$y$ 和真实数据$\hat{y}$的差距得到误差$e$  
Loss: $L = \frac{1}{N}\sum_{n}e_{n}$  
关于e有2种计算方式：MAE & MSE  
*MAE*: mean absolute error, $e = |y - \hat{y}|$  
*MSE*: mean square error, $e = (y - \hat{y})^2$  



    

    