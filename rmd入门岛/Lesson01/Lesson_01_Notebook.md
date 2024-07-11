书生大模型实战营-第三期-L0-Linux


#创建开发机



#设置SSH登录


失败了，需要检查iis和openssh服务状态是否正常：


#远程操作

创建hello_world.py程序并运行，提示需要安装pip依赖，使用pip install gradio==4.29.0命令安装以下依赖包

#配置conda环境

conda create -n demo python==3.10 -y
conda activate demo
conda install pytorch==2.0.1 torchvision==0.15.2 torchaudio==2.0.2 pytorch-cuda=11.7 -c pytorch -c nvidia


#激活环境
conda activate demo


#安装包的依赖
pip install huggingface-hub==0.17.3
pip install transformers==4.34 
pip install psutil==5.9.8
pip install accelerate==0.24.1
pip install streamlit==1.32.2 
pip install matplotlib==3.8.3 
pip install modelscope==1.9.5
pip install sentencepiece==0.1.99

#Linux命令操作

    1  ls
    2  cd xmwan/
    3  ls
    4  python --version
    5  gradio --version
    6  conda env list
    7  conda create -n demo python=3.11
    8  ll
    9  mkidr xmwan
   10  cd xmwean
   11  cd xmwan
   12  ll
   13  vi hello_world.py
   14  chmod 777 *.py
   15  ll
   16  python -v
   17  python hello_world.py 
   18  pip install gradio==4.29.0
   19  pwd
   20  ll
   21  mkdir xmwan
   22  mv hello_world.py xmwan/
   23  l
   24  cd xmwan
   25  ll
   26  python hello_world.py 
   27  vi hello_world.py 
   28  python hello_world.py 
   29  cat /etc/os-release
   30  apt-get install netstat
   31  apt-get install net-tools
   32  netstat -lantp | grep -i 48382
   33  ll
   34  netstat -lantp | grep -i 22
   35  stat
   36  hostnmae
   37  hostname
   38  unmae
   39  uname
   40  nvida-smi
   41  nvidia-smi
   42  lsb-release
   43  lsb-release -a
   44  lsb_release -a
   45  python hello_world.py 
   46  conda env list
   47  conda activate demo
   48  python --version
   49  pip install gradio==4.29.0
   50  ls
   51  cd xmwan/
   52  ls
   53  python hello_world.py 
   54  pip install gradio==4.29.0
   55  python hello_world.py 
   56  gradio
   57  gradio --version
   58  history
