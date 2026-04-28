# VMware Workstation Pro 25H2 中文语言包

VMware Workstation Pro 25H2 官方界面默认是英文，可通过导入中文语言包实现汉化。

## 下载

在 [Releases](https://github.com/Hermione027/VMware-Workstation-Full-25H2-zh_CN/releases/tag/Luo) 中下载 `zh_CN.zip`。

## 使用方法

1. 解压 `zh_CN.zip`。
2. 将 `zh_CN` 文件夹复制到 VMware 安装目录下的 `Message` 文件夹中。
3. 按 `Win + R` 打开“运行”，输入：

```text
%APPDATA%\VMware\preferences.ini
```

4. 用记事本打开 `preferences.ini`。
5. 在文件末尾添加：

```ini
pref.locale = "zh_CN"
```

6. 保存文件后重启 VMware。

## 说明

汉化文件取自 VMware Workstation 17 Pro 语言文件。
