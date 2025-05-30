# MyPublicMemo

## 勉強会notion
https://jstrieb.github.io/link-lock/#eyJ2IjoiMC4wLjEiLCJlIjoiRXR4T21uWk1kaytCT3l2Zk1KaGRhOGhrdmhlc0ZqUkRRTzVrcmt0ODJnYWhpYjQ0L1BFMTZPZjY2eDlGMlRab0U1bGgzcUMwOVpLMVpzZGNXSjFKblVpVWltYUs2UUxsZ3BYbkp2R05nazZNbkk4VzlLdnptckhmIiwicyI6IkdmYitHUEJRbGsvTUFEYStQaU9KdWc9PSIsImkiOiIwOU9CTFhQVnZNMC81MUxRIn0=

## AlphaPoseSetting
```bash
conda create -n alphapose python=3.7 -y
conda activate alphapose

conda install pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 pytorch-cuda=11.7 -c pytorch -c nvidia

git clone https://github.com/MVIG-SJTU/AlphaPose.git
cd AlphaPose

export PATH=/usr/local/cuda-11.7/bin:$PATH
export LD_LIBRARY_PATH=/usr/local/cuda-11.7/lib64/:$LD_LIBRARY_PATH

sudo apt install libyaml-dev

pip install cython==0.27.3 ninja easydict halpecocotools munkres natsort opencv-python pyyaml scipy \\ntensorboardx terminaltables timm==0.1.20 tqdm visdom jinja2 typeguard pycocotools

python setup.py build develop

conda install -c fvcore -c iopath -c conda-forge fvcore iopath
conda install -c bottler nvidiacub
```
