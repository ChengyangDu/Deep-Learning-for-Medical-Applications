1. DenseNet:
   a) 发现当前更深的网络都通过by-pass产生更多连接
   b) 一个block内部，x_l = H([x0,x1, .. x_l-1])
   c) Transition layer: block与block间的转接，通过1*1降维，再通过pooling缩小尺寸
   d) Bottleneck layer:b)中的channel数过高，通过1*1降维