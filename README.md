# YoloGather
* V0.0 YoloGather 创建 2022.10.09 LightPC YL

## 库安装
* conda install pytorch torchvision cudatoolkit=10.2 -c pytorch

清华大学：https://pypi.tuna.tsinghua.edu.cn/simple
阿里云：http://mirrors.aliyun.com/pypi/simple/
中国科技大学 https://pypi.mirrors.ustc.edu.cn/simple/
华中理工大学：http://pypi.hustunique.com/
山东理工大学：http://pypi.sdutlinux.org/
豆瓣：http://pypi.douban.com/simple/
网易：http://mirrors.163.com

*  进入桌面，导出文件到桌面更直观
pip freeze>all_modules.txt
*  输出所有的包
pip uninstall -r all_modules.txt -y
*  删除所有的包，一路yes
*  conda update -n base -c defaults conda
*  nvidia-smi

## YoloBasics
* 基础学习
### YOLO v7
* install yolov7
* pip install -r requirements.txt
* python detect.py --weights weights/yolov7.pt --source inference/images
参数说明
    --weights weight/yolov7.pt   # 这个参数是把已经训练好的模型路径传进去，就是刚刚下载的文件
    --source inference/images   # 传进去要预测的图片
    预测的图片被保存在了/runs/detect/exp/文件夹下

CUDA Version: 11.7

pip3 install torch == 1.9.0+cu111 torchvision == 0.10.0+cu111 torchaudio==0.9.0 -f https://download.pytorch.org/whl/torch_stable.html

torch>=1.7.0,!=1.12.0
torchvision>=0.8.1,!=0.13.0


