# DGX Spark builds

Things I build on two NVIDIA DGX Spark machines on my desk: local AI pipelines that use open models and no cloud GPUs.

| # | Build | What it is |
|---|---|---|
| 01 | [ComfyUI video pipeline](01-comfyui-video-pipeline/) | A 35-second video made with open image, video and music models in ComfyUI, split across both Sparks |

## The hardware

- 2× NVIDIA DGX Spark, 128 GB of unified memory each
- Spark 1 is online and downloads models; Spark 2 has no internet and gets its models over a direct link from Spark 1
- I drive both from a MacBook through NVIDIA Sync
