# ImmortalWrt-Builder-24.10

这是一个用于自动编译 [ImmortalWrt 24.10](https://github.com/padavanonly/immortalwrt-mt798x-24.10) 固件的 GitHub Actions 工作流。支持每天检查源码更新、自动编译固件，并将 `sysupgrade.bin` 文件上传到 GitHub Release 和 WebDAV。

###下载固件
- **GitHub Release**：在仓库的 **Releases** 页面查找 `v24.10-<device_model>` 标签，下载 `sysupgrade.bin`。
- **WebDAV**：通过配置的 WebDAV 服务器访问固件，文件名为 `<device_model>_25dB-<on/off>_<version>_sysupgrade.bin`。

### 刷写固件
- 确认设备型号与固件匹配。
- 备份设备原有固件。
- 使用 Web 界面或 SSH 刷入 `sysupgrade.bin` 文件。

## 许可证
本项目遵循 MIT 许可证，详情见 [LICENSE](LICENSE)。
