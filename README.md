# QDHelper

面向起点读书的功能增强模块，模块入口：长按宿主「书架」页右上角的「更多」，或长按「我的」页左上角的「设置」。

- **模块包名**：`io.github.xiyunmn.qdhelper`
- **作用域**：`com.qidian.QDReader`（起点读书）
- **源码**：[xiyunmn/QDHelper](https://github.com/xiyunmn/QDHelper)
- **最新版本**：[GitHub Releases](https://github.com/xiyunmn/QDHelper/releases/latest)
- **问题反馈**：[Issues](https://github.com/xiyunmn/QDHelper/issues)

## 安装要求

- Android **9 及以上**，仅支持 **arm64-v8a**；液态玻璃效果需要 Android **13 及以上**。
- 使用支持 **libxposed API 102** 的 LSPosed。
- 在 LSPosed 中启用模块，作用域勾选「起点读书」，为宿主开启「还原内联钩子」，随后强制停止并重新打开宿主。
- **若使用 Zygisk Next，需禁用「匿名内存」和「ZN链接器」。**

模块没有独立的桌面设置入口，请通过上述长按入口进入设置。

## 许可与声明

项目自有代码采用 [AGPL-3.0-only](https://github.com/xiyunmn/QDHelper/blob/main/LICENSE)，第三方代码保留原许可证。

本模块免费，谨防倒卖；如付费获取，请联系卖家退款。本项目为非官方工具，与阅文集团、起点中文网及起点读书无隶属、合作或授权关系。

仅供学习与技术研究，请在下载后 24 小时内删除用于研究测试的安装包及相关副本；此提醒不改变开源许可证授予的权利。功能不保证持续可用，使用可能导致应用异常或账号风险，请自行评估并承担。
