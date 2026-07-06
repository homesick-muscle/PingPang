# Team Workspace

用于团队统一管理代码、文档和协作约定的仓库。

## Python 版本

- 统一版本：`Python 3.10`
- 本仓库通过 `.python-version` 和 `pyproject.toml` 固定到 `3.10`

## 推荐目录

- `src/`: Python 代码
- `docs/`: 文档、方案、会议记录
- `scripts/`: 本地辅助脚本

## Windows 快速开始

```powershell
py -3.10 -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -e .
```

安装完成后可直接运行：

```powershell
python -m team_workspace
```

## Git 初始化后建议

1. 在远程平台创建仓库。
2. 绑定远程地址：`git remote add origin <your-repo-url>`
3. 首次推送：`git push -u origin main`
