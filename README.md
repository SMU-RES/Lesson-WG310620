# 数字图像处理基础（WG310620）

- **课程代码**：`WG310620`

本仓库收录一个名为 `yolo` 的 Python 工程。现有入口打印问候语、PyTorch 版本和 CUDA 是否可用。

## 目录结构

```text
.
├── README.md
└── content/
    └── yolo/
        ├── .gitignore        # Python 生成文件与虚拟环境的忽略规则
        ├── README.md         # 原工程说明文件，当前为空
        ├── main.py           # 打印 PyTorch 版本与 CUDA 可用状态的入口
        └── pyproject.toml    # Python 版本、依赖与 uv 索引配置
```

## 工程说明

`pyproject.toml` 要求 Python 3.13 或更高版本，并声明 `ultralytics`、`torch`、`torchaudio` 和 `torchvision` 依赖。安装依赖后，在 `content/yolo/` 中运行 `python main.py` 可执行现有入口。
