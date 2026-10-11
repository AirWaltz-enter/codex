# FastMoss女士运动外套选品系统 V2.1

## 已有V2：下载更新包

[下载 V2.1 更新包](https://github.com/AirWaltz-enter/codex/raw/refs/heads/fastmoss-v2/downloads/FastMoss_V2_1_Update.zip)

[GitHub更新包文件页](https://github.com/AirWaltz-enter/codex/blob/fastmoss-v2/downloads/FastMoss_V2_1_Update.zip)：点击 Download raw file（下载原始文件）。私有仓库需要先登录有访问权限的账号。

1. 关闭Excel，备份原工具。
2. 解压更新包，将包内 `FastMoss选品清洗工具` 中的文件复制到原工具对应目录，覆盖同名代码和说明。
3. 保留新增 `target_config.json`。更新包不包含原始表、输出报告、图片和1688数据，也不覆盖现有关键词/评分配置。
4. 双击原来的 `运行V2.bat`。
5. 打开 `02_筛选后表格/选品报告.xlsx` 的“待人工复查”，在“图片款式审核”选择“确认女士运动外套”，保存关闭后重新运行。

明确男款、卫衣、裤子等非目标商品会被排除；未确认图片款式的候选进入人工复查。没有接入自动图像识别模型，首次推荐表可能为空。

自动生成的 `选品报告_轻量.xlsx` 不含图片，方便上传反馈。人工审核请填写原主报告。已有超大报告可双击 `04_脚本/导出轻量报告.bat` 导出轻量版。

## 新安装

[下载 V2.1 完整包](https://github.com/AirWaltz-enter/codex/raw/refs/heads/fastmoss-v2/downloads/FastMoss_V2_1.zip)

安装 Python 3.10+，解压到新目录，把最新FastMoss Excel放入 `01_FastMoss原始表`，双击 `运行V2.bat`。首次安装依赖需要联网。

36项自动测试通过；完整包及V2增量更新均已在隔离解压目录中运行通过。Windows桌面仍未实测。详细变更与验证日志见包内 `V2.1升级说明.md` 和 `V2.1测试运行结果.md`。随包旧样本是运动裤，不属于本版目标，请使用自己的最新外套数据。

## 文件校验

- `FastMoss_V2_1_Update.zip`：64297 字节；SHA256 `0fd9f6e33a5e5c9d72da8651e4ca99fc5336c299fc2dadf33ffe61f1886975b6`
- `FastMoss_V2_1.zip`：7822119 字节；SHA256 `6e023ebb84af7d121d58b6c3c3cb3ac7b9d38d2732f5cfabec36b587ad758f54`

[保留的原V2完整包](https://github.com/AirWaltz-enter/codex/blob/fastmoss-v2/downloads/FastMoss_V2.zip)
