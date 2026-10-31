# RL-MPC 导航演示

比较固定权重 MPC 与强化学习自适应 MPC 在 6、12、18 行人走廊场景中的导航表现。

网站地址：https://rl4mpc.github.io/RL-MPC-site/ （启用 GitHub Pages 后生效）

## 演示内容

每个场景包含固定 MPC 1（W013）、固定 MPC 2（S012）、固定 MPC 3（S005）和 RL-MPC，共 12 段视频。各场景支持独立同时播放、暂停和从头重播。

三个场景均含 2 个静态箱体，行人在走廊内部随机出生，目标位于四周墙边，期望速度为 0.2–0.5 m/s。视频为选定案例展示，不代表整体成功率。

## 文件与预览

- `index.html`：网站页面。
- `assets/scenes/`：按场景保存的视频与 PNG 封面。
- `.nojekyll`：直接发布静态文件。

在仓库根目录运行 `python3 -m http.server 8000`，访问 http://localhost:8000 。

## GitHub Pages 发布

进入仓库 Settings → Pages，Source 选择 Deploy from a branch，分支选择 main，目录选择 / (root)，保存后等待部署完成。
