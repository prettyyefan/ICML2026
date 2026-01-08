# 上传github仓库步骤
# first 合并
git init

git add memo.md

git commit -m "first commit code"

git branch -M main

git remote add origin https://github.com/prettyyefan/ICML2026.git

git pull origin main --allow-unrelated-histories

# after

git add memo.md

git commit -m "update 2026.01.08"

git push -u origin main

# 激活虚拟环境
.\venv\Scripts\activate 







# 硬件信息
    Python版本：Python 3.10.11
    CUDA版本：（nvidia-smi）CUDA Version: 12.2
    PyTorch版本：2.5.1+cu121
    TorchVision版本： 0.20.1+cu121

pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121

