# SummerSchool-Project


借鉴Lab2  我这里的图片是名为Leo的图片  
Lab （使用Sobel算子提取Leo的边缘）
因为自身能力也是有限，现在是已经做了三个Lab的复现，对于本次项目，我以Lab2为基础，主要做的是对代码的解释，以及换用其他自己的图片进行处理
包括后面report的记录，包括仿真综合的结果以及我认为需要注意比较重要的步骤点

# 本次项目主要用到三个软件 Vitis_HLS Vivado Jupyter Notebook

其中 他们使用的顺序是固定的 不能够颠倒
首先 使用Vitis_HLS对所写代码进行仿真和综合（结果在report均已呈现），最终导出RTL的压缩包以便后续Vivado的使用
然后 使用Vivado对上面得到的RTL
