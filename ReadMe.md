# VideoPipePerformance
这个仓库主要是收集相应的多媒体评价性能指标的工具集


## vmaf
Netflix开发的一套评价指标

sample:

> ./vmaf -r reference.yuv -d distorted.yuv -w 1920 -h 1080 --model model/vmaf_v0.6.1.json

## vqmt
Video Quality Measurement Tool 这个是开源的VQMT工具

sample:

> ./vqmt -o original_video.yuv -d distorted_video.yuv -m psnr,ssim

## MSU_VQMT
MSU_VQMT是开源的VQMT工具，是Windows平台下的工具
