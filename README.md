# CUCUMBER-9
The CUCUMBER-9 dataset

## Description
### ProtoType-1
![proto1]
キュウリを上から撮影した画像セットです。

This dataset consists of 2970 32x32 color images in 9 classes.
All images taken from directly above.
The dataset layout is the same as [CIFAR-10 python version](http://www.cs.toronto.edu/~kriz/cifar.html "The CIFAR-10 dataset").

### ProtoType-2
![proto2]
キュウリを上/下/側面から撮影した画像セットです。

This dataset consists of 8400 32x32 color images in 9 classes.
All images taken from the above, below and side.
The data are arranged in the order of above(RGB), below(RGB), and side(RGB).

>[ above R channel data (32x32 entries, following the same) ],  
[ above G channel data ],  
[ above B channel data ],  
[ below R channel data ],  
[ below G channel data ],  
[ below B channel data ],  
[ side  R channel data ],  
[ side  G channel data ],  
[ side  B channel data ],  
...


## Sample
### ProtoType-1
![sample]

### ProtoType-2
![sample2]

[proto1]: http://workpiles.com/wordpress/wp-content/uploads/2016/06/ccb9_proto1-203x300.jpg "proto1"
[proto2]: http://workpiles.com/wordpress/wp-content/uploads/2016/06/ccb9_proto2-181x300.jpg "proto2"
[sample]: http://workpiles.com/wordpress/wp-content/uploads/2016/02/cucumber_classification.jpg "sample"
[sample2]: http://workpiles.com/wordpress/wp-content/uploads/2016/08/ccb9_proto2_images.jpg "sample2"

