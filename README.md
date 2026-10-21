# CourtFlow · 测试1（Test 1）

篮球双队 5v5 实时技术统计交互原型。

- **当前版本**：CourtFlow V0.3.1 · 测试1 (Alpha)
- **建议分支**：`basketballrecord`
- **运行入口**：`index.html` （无外部依赖）
- **支持终端**：电脑浏览器、iPad Safari 横屏、手机浏览器

## 运行

直接用浏览器打开 `index.html`，或把此仓库通过 GitHub Pages 发布为网站。

## 已包含

- 左右半场：A 队在左 (1, 2 / 3, 4, 5)，B 队在右 (6, 7 / 8, 9, 10)
- 持球状态下的球员传球、失误及抢断关联
- 投篮、助攻、篮板、盖帽、犯规及罚球交互原型
- 罚球违例三种操作：撤销违例 / 取消本罚 / 重罚
- 事件日志和相关统计操作

## 测试提醒

当前仍为 **Alpha 交互测试版**，尚不能替代正式赛事统计软件；使用前请备份重要数据。

更多状态与限制见 [SPEC.md](SPEC.md)。

## 版本标记与测试预览

- 版本：**测试1 / Test 1**；分支：`basketballrecord`；建议 Git tag：`test1`。
- [桌面端布局](previews/desktop.png) · [手机端布局](previews/mobile.png)
- iPad 访问：需要仓库所有者在 GitHub Pages 设置中选中 **Deploy from a branch → basketballrecord → /(root)**，站点部署成功后才可访问预期地址 `https://yyysheng.github.io/basketballrecord/`。该地址并不代表已发布。
- 当前不支持多设备自动同步；请定期导出 JSON 备份比赛数据。
