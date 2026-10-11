# 边界与情感反馈

> **群聊通知（2026-10-11）：** 原群聊被停用一周，期间可先加入 bot 群：**145326153**。

这是一个独立的 AstrBot 插件。请从 [GitHub 仓库](https://github.com/menglimi/astrbot_plugin_nene_boundary) 获取，并将目录直接放在 AstrBot 的 `data/plugins/astrbot_plugin_nene_boundary` 下；它不能作为 `astrbot_plugin_private_companion` 的子目录启用。

启用前请确认已安装并启用私聊陪伴插件。边界插件通过 AstrBot 已注册插件实例联动；不要手工指定其他机器上的数据文件或数据库路径。

本地测试示例：

```powershell
$env:ASTRBOT_BACKEND_APP = 'C:\\path\\to\\AstrBot\\backend\\app'
python -m pytest -q tests/test_nene_boundary.py
```
