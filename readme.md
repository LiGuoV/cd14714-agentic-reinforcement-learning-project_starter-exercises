课程仓库:https://github.com/udacity/cd14714-agentic-reinforcement-learning-project_starter-exercises

# 环境准备

conda create -n agent-course python=3.14

`$ nvidia-smi`核对touch对cuda的版本要求，进而装了最新显卡驱动更新了cuda版本

pip3 install torch torchvision --index-url https://download.pytorch.org/whl/cu130

确认安装成功
```
import torch
x = torch.rand(5, 3)
print(x)
print("CUDA Available:", torch.cuda.is_available())
```

