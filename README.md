# 中文办公常用的中文字体（字库）/Common Chinese office fonts (font library)
根据《中华人民共和国国家通用语言文字法》、《国务院关于公布<通用规范汉字表>的通知》（国发〔2013〕23号）、《信息技术产品国家通用语言文字使用管理规定》（中华人民共和国教育部令第54号）等有关规定，参考《党政机关公文格式》（GB/T 9704-2012）、《信息交换用汉字编码字符集 基本集》（GB/T 2312-1980）、原国家技术监督局标准化司和原电子工业部科技与质量监督司发布的《汉字扩展内码规范（GBK）1.0版》（技监标函〔1995〕229号）、《信息技术 中文编码字符集》（GB 18030-2022）等国家、国际技术性标准文件，现将办公常用的中文字体（字库）文件上传，供日常办公使用。
部分字体（字库）仅供非商业用途使用，如需商业用途使用，请自行联系字体（字库）厂商获取使用授权。

# 本文件提供了各个字体文件的安装方式，支持的字体包括以下几种：

* 大标宋体
* 小标宋体
* 黑体
* Times New Roman
* 仿宋_GB2312、楷体_GB2312、方正小标宋简体、方正楷体_GBK等

## 字体文件
需自行安装的字体，按照安装说明操作
| 字体   | 名称   | 广商   | 字符集 | 备注                       |
|--------|--------|--------|--------|----------------------------|
| 宋体   | 宋体   | 中易   | GB18030 | 简体中文版 Windows 7及以后的版本的系统自带 |
| 大标宋体 | 方正大标宋简体 | 方正   | GB2312 | 需自行安装                 |
| 小标宋体 | 方正小标宋简体 | 方正   | GB2312 | 需自行安装                 |
| 仿宋   | 仿宋   | 中易   | GB18030 | 简体中文版 Windows 7及以后的版本的系统自带 |
| 仿宋   | 方正仿宋简体 | 方正   | GB2312 | 需自行安装                 |
| 仿宋   | 方正仿宋_GBK | 方正   | GBK    | 需自行安装                 |
| 楷体   | 楷体   | 中易   | GB18030 | 简体中文版 Windows 7及以后的版本的系统自带 |
| 楷体   | 楷体_GB2312 | 长城   | GB2312 | 需自行安装                 |
| 楷体   | 方正楷体简体 | 方正   | GB2312 | 需自行安装                 |
| 楷体   | 方正楷体_GBK | 方正   | GBK    | 需自行安装                 |
| 黑体   | 黑体   | 中易   | GB18030 | 简体中文版 Windows 7及以后的版本的系统自带 |
| 黑体   | 方正黑体简体 | 方正   | GB2312 | 需自行安装                 |
| 黑体   | 方正黑体_GBK | 方正   | GBK    | 需自行安装                 |


## 安装说明

以下是不同操作系统中安装 TTF 格式字体文件的方式。

### macOS

1. **下载**所需的 TTF 字体文件。
2. **双击**字体文件，系统会自动打开**字体册**应用程序。
3. 在字体预览窗口中，点击底部的**安装字体**按钮。

这样字体将被安装到系统字体库中，所有应用程序都可以使用该字体。

### Windows

1. **下载**所需的 TTF 字体文件。
2. 右键点击字体文件并选择 **安装**。
3. 如果希望将字体提供给所有用户，可以选择 **为所有用户安装**。
4. 安装完成后，字体将对所有 Windows 应用程序可用。

或者你也可以：

* 打开 **控制面板** > **外观和个性化** > **字体**。
* 将 TTF 字体文件拖放到字体文件夹中。

### Linux (Ubuntu/Debian)

1. **下载**所需的 TTF 字体文件。
2. 打开终端并创建本地字体目录（如果没有的话）：

   ```bash
   mkdir -p ~/.fonts
   ```
3. 将 TTF 字体文件复制到该目录下：

   ```bash
   cp /path/to/font.ttf ~/.fonts/
   ```
4. 更新字体缓存：

   ```bash
   fc-cache -fv
   ```

字体安装完成后，可以在应用程序中使用。

### Linux (Fedora/RHEL/CentOS)

1. **下载**所需的 TTF 字体文件。
2. 将字体文件复制到系统字体目录：

   ```bash
   sudo cp /path/to/font.ttf /usr/share/fonts/
   ```
3. 更新字体缓存：

   ```bash
   sudo fc-cache -fv
   ```

---

# Font Library Overview

This document provides installation instructions for various font files in TTF format. The following fonts are included in the collection:

* Songti
* Daziti
* Xiaoti
* Fangsong
* Kaiti
* Heiti
* Times New Roman
* Fangsong_GB2312、Kaiti_GB2312、Founder Small Standard Song Simplified、Square regular script_GBK等

## Font Files
Fonts that need to be installed by yourself, follow the installation instructions
| Font   | Name   | Vendor   | Character Set | Notes                       |
|--------|--------|----------|---------------|-----------------------------|
| Songti | Songti | Zhongyi  | GB18030       | Simplified Chinese version for Windows 7 and later system pre-installed |
| Large Songti | Fangzheng Large Song Simplified | Fangzheng | GB2312       | Requires manual installation |
| Small Songti | Fangzheng Small Song Simplified | Fangzheng | GB2312       | Requires manual installation |
| Fangsong | Fangsong | Zhongyi  | GB18030       | Simplified Chinese version for Windows 7 and later system pre-installed |
| Fangsong | Fangzheng Fangsong Simplified | Fangzheng | GB2312       | Requires manual installation |
| Fangsong | Fangzheng Fangsong_GBK | Fangzheng | GBK          | Requires manual installation |
| Kaishu | Kaishu | Zhongyi  | GB18030       | Simplified Chinese version for Windows 7 and later system pre-installed |
| Kaishu | Kaishu_GB2312 | Changcheng | GB2312       | Requires manual installation |
| Kaishu | Fangzheng Kaishu Simplified | Fangzheng | GB2312       | Requires manual installation |
| Kaishu | Fangzheng Kaishu_GBK | Fangzheng | GBK          | Requires manual installation |
| Heiti  | Heiti  | Zhongyi  | GB18030       | Simplified Chinese version for Windows 7 and later system pre-installed |
| Heiti  | Fangzheng Heiti Simplified | Fangzheng | GB2312       | Requires manual installation |
| Heiti  | Fangzheng Heiti_GBK | Fangzheng | GBK          | Requires manual installation |


## Installation Instructions

Below are the installation instructions for the supported operating systems.

### macOS

1. **Download** the TTF font file you want to install.
2. **Open** the font file by double-clicking it.
3. The **Font Book** application will open automatically.
4. Click the **Install Font** button located at the bottom of the preview window.

This will add the font to the system-wide font library, making it available for all applications.

### Windows

1. **Download** the TTF font file.
2. Right-click the font file and select **Install** from the context menu.
3. If you want the font to be available to all users, right-click and select **Install for all users**.
4. The font will now be available to all applications on Windows.

Alternatively, you can:

* Open **Control Panel** > **Appearance and Personalization** > **Fonts**.
* Drag and drop the TTF font file into the font folder.

### Linux (Ubuntu/Debian)

1. **Download** the TTF font file.
2. Open a terminal and create a directory for local fonts if it doesn't already exist:

   ```bash
   mkdir -p ~/.fonts
   ```
3. Copy the TTF font file into the directory:

   ```bash
   cp /path/to/font.ttf ~/.fonts/
   ```
4. Update the font cache:

   ```bash
   fc-cache -fv
   ```

The font will now be available for use in applications.

### Linux (Fedora/RHEL/CentOS)

1. **Download** the TTF font file.
2. Copy the TTF font file to the system-wide font directory:

   ```bash
   sudo cp /path/to/font.ttf /usr/share/fonts/
   ```
3. Update the font cache:

   ```bash
   sudo fc-cache -fv
   ```