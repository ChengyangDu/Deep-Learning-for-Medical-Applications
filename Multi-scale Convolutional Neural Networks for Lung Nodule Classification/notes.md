使用multi-scale策略：
   a) 不同尺度的feature map共享参数，提取到尺寸各异的新feature map，通过up sampling堆叠在一起
   b) 对不同尺度的图像进行上/下采样，得到同一尺寸，输入网络。
   c) 无论是 a) 还是 b),不同尺度的