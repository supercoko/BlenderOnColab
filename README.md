# BlenderOnColab
Rendering Blender Animations using Google Colab

توضیحات مربوط به چگونگی رندر گرفتن با استقاده از نرم افزار بلندر در قالب توضیحات در نوتبوک ژوپیتر و فیلم آموزشی آمده است<p dir = "rtl" ></p>



<p dir = "rtl" >
ویدیوی آموزشی در یوتوب:
</p>

https://youtu.be/j14Z-sH5xLU


<p dir = "rtl" >
نکته :
دستگاهی که کولب به ما ارائه میدهد کاملا تصادفی است. این کارتهای گرافیک در کل 4 مدل هستند :
</p>

- T4 
- p4 
- k80 
- p100 (best)


برای دسترسی به بهترین کارت گرافیک :


1. run the cell that contains !nvidia-smi.
2. run cell to see the result below
3. if the gpu was Tesla p100 its OK! continuue with the code. if not, goto runtime tab and click Factory reset runtime. the notebook will reser. you need to click connect.
4. then go to step 1 . do these steps until you get gpu p100. you may need to do this 20 times to get p100 or in the first try!! 

<!-- language: lang-none -->
    +-----------------------------------------------------------------------------+   
    | NVIDIA-SMI 440.82       Driver Version: 418.67       CUDA Version: 10.1     |
    |-------------------------------+----------------------+----------------------+
    | GPU  Name        Persistence-M| Bus-Id        Disp.A | Volatile Uncorr. ECC |
    | Fan  Temp  Perf  Pwr:Usage/Cap|         Memory-Usage | GPU-Util  Compute M. |
    |===============================+======================+======================|
    |   0  Tesla P100-PCIE...  Off  | 00000000:00:04.0 Off |                    0 |
    | N/A   39C    P0    25W / 250W |      0MiB / 16280MiB |      0%      Default |
    +-------------------------------+----------------------+----------------------+
                                                                                   
    +-----------------------------------------------------------------------------+
    | Processes:                                                       GPU Memory |
    |  GPU       PID   Type   Process name                             Usage      |
    |=============================================================================|
    |  No running processes found                                                 |
    +-----------------------------------------------------------------------------+

