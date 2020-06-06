# Guided Spatially-Varying Convolution for Fast Semantic Segmentation on Video (GSVNet)

## Performance and Benchmarks

The experimental results were conducted on Nvidia GTX 1080Ti. 
Avg. mIoU: the average mIoU over the keyframe and non-keyframes. 
Min. mIoU:the minimum mIoU among frames. (It should be the last non-keyframe) 
$\gamma$:

### Cityscapes

|**Model**|**Method**|**Backbone**|**# of Non-keyframes**|**Avg. mIoU**|**Min. mIoU**|**FPS**|
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
|GSVNet(ours)|Video|SwiftNet-ResNet18|2|72.5|70.5|125|
|BiSeNet|Image|ResNet-18|

