# NetGlow

NetGlow is an advanced network traffic visualizer built with Python and PyQt6. It provides real-time monitoring, visualization, and analysis of network packets with a user-friendly interface, supporting multiple themes and basic network diagnostic tools.

---

## Features

- **Real-time Packet Capture**: Monitor network traffic using Scapy on selected interfaces.
- **Visualizations**: Displays traffic, anomaly scores, protocol distribution, and top IP activity through interactive charts.
- **Anomaly Detection**: Detects unusual network activity using a simple moving average algorithm.
- **Export Data**: Save captured packet data and anomaly scores as CSV files.
- **Multilingual Interface**: Supports English, Persian, and Chinese (layout direction only, no full translation).
- **Customizable Themes**: Choose from Windows 11, Light, Dark, and Red-Blue themes.
- **Network Tools**: Includes ping and traceroute functionalities.
- **System Tray Integration**: Minimize to system tray with notifications for anomalies.

---

## Requirements

- Python 3.9+
- PyQt6
- pyqtgraph
- scapy
- psutil
- pandas
- numpy
- elasticsearch
- qdarkstyle
- qtawesome
- matplotlib
- seaborn
- Pillow

Install dependencies using:
```bash
pip install pyqt6 pyqtgraph scapy psutil pandas numpy elasticsearch qdarkstyle qtawesome matplotlib seaborn pillow
```

---

## Installation

1. Ensure you have Python 3.9 or higher installed.
2. Install the required dependencies listed above.
3. Download or clone the repository.
4. Run the application:
   ```bash
   python netglow.py
   ```

---

## Usage

1. Launch the application with `python netglow.py`.
2. Select a network interface from the dropdown menu.
3. Click the "Start Capture" button to begin monitoring.
4. Use the filter input to narrow down displayed packets.
5. Switch tabs to view different visualizations (Traffic, Anomalies, Protocol Distribution, Top IPs, Heatmap).
6. Access network tools (Ping, Traceroute) from the Tools menu.
7. Export data or configure settings (theme, language) from the File and View menus.

---

## Notes

- The application requires administrative privileges for packet capture on some systems.
- Elasticsearch must be running on `localhost:9200` for packet storage.
- The Red-Blue theme uses distinct blue and red colors for better contrast.
- Language support is limited to layout direction (RTL for Persian, LTR for English/Chinese).
- Ensure all dependencies are installed to avoid runtime errors.

---

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

---

## License

This project is licensed under the MIT License.

---

# NetGlow (فارسی)

NetGlow یک ابزار پیشرفته برای تجسم ترافیک شبکه است که با پایتون و PyQt6 ساخته شده است. این برنامه امکان نظارت بلادرنگ، تجسم و تحلیل بسته‌های شبکه را با رابط کاربری ساده فراهم می‌کند و از چندین تم و ابزارهای تشخیصی شبکه پشتیبانی می‌کند.

---

## ویژگی‌ها

- **ضبط بلادرنگ بسته‌ها**: نظارت بر ترافیک شبکه با استفاده از Scapy روی رابط‌های انتخاب‌شده.
- **تجسم‌ها**: نمایش ترافیک، امتیازات ناهنجاری، توزیع پروتکل و فعالیت IPهای برتر از طریق نمودارهای تعاملی.
- **تشخیص ناهنجاری**: شناسایی فعالیت غیرعادی شبکه با استفاده از الگوریتم میانگین متحرک ساده.
- **صدور داده‌ها**: ذخیره داده‌های بسته‌های ضبط‌شده و امتیازات ناهنجاری به‌صورت فایل CSV.
- **رابط چندزبانه**: پشتیبانی از انگلیسی، فارسی و چینی (فقط جهت‌گیری چیدمان، بدون ترجمه کامل).
- **تم‌های قابل تنظیم**: انتخاب از تم‌های ویندوز ۱۱، روشن، تیره و قرمز-آبی.
- **ابزارهای شبکه**: شامل قابلیت‌های ping و traceroute.
- **ادغام با سینی سیستم**: امکان کوچک‌سازی به سینی سیستم با اعلان برای ناهنجاری‌ها.

---

## پیش‌نیازها

- پایتون ۳.۹ یا بالاتر
- PyQt6
- pyqtgraph
- scapy
- psutil
- pandas
- numpy
- elasticsearch
- qdarkstyle
- qtawesome
- matplotlib
- seaborn
- Pillow

نصب وابستگی‌ها با استفاده از:
```bash
pip install pyqt6 pyqtgraph scapy psutil pandas numpy elasticsearch qdarkstyle qtawesome matplotlib seaborn pillow
```

---

## نصب

1. اطمینان حاصل کنید که پایتون ۳.۹ یا بالاتر نصب شده است.
2. وابستگی‌های موردنیاز را نصب کنید.
3. مخزن را دانلود یا کلون کنید.
4. برنامه را اجرا کنید:
   ```bash
   python netglow.py
   ```

---

## استفاده

1. برنامه را با دستور `python netglow.py` اجرا کنید.
2. یک رابط شبکه را از منوی کشویی انتخاب کنید.
3. روی دکمه "شروع ضبط" کلیک کنید تا نظارت آغاز شود.
4. از ورودی فیلتر برای محدود کردن بسته‌های نمایش‌داده‌شده استفاده کنید.
5. تب‌ها را تغییر دهید تا تجسم‌های مختلف (ترافیک، ناهنجاری‌ها، توزیع پروتکل، IPهای برتر، نقشه حرارتی) را مشاهده کنید.
6. از منوی ابزارها به ابزارهای شبکه (Ping، Traceroute) دسترسی پیدا کنید.
7. داده‌ها را صادر کنید یا تنظیمات (تم، زبان) را از منوهای فایل و نمایش پیکربندی کنید.

---

## نکات

- برنامه برای ضبط بسته‌ها در برخی سیستم‌ها نیاز به دسترسی ادمین دارد.
- Elasticsearch باید روی `localhost:9200` در حال اجرا باشد.
- تم قرمز-آبی از رنگ‌های آبی و قرمز متمایز برای کنتراست بهتر استفاده می‌کند.
- پشتیبانی زبانی به جهت‌گیری چیدمان محدود است (راست‌چین برای فارسی، چپ‌چین برای انگلیسی/چینی).
- اطمینان حاصل کنید که همه وابستگی‌ها نصب شده‌اند تا از خطاهای زمان اجرا جلوگیری شود.

---

## مشارکت

از مشارکت استقبال می‌شود! لطفاً این مراحل را دنبال کنید:
1. مخزن را فورک کنید.
2. یک شاخه جدید ایجاد کنید (`git checkout -b feature-branch`).
3. تغییرات خود را اعمال کنید و کامیت کنید (`git commit -m "Add feature"`).
4. شاخه را پوش کنید (`git push origin feature-branch`).
5. یک درخواست کشش باز کنید.

---

## مجوز

این پروژه تحت مجوز MIT منتشر شده است.

---

# NetGlow (中文)

NetGlow 是一个使用 Python 和 PyQt6 构建的先进网络流量可视化工具。它提供实时监控、可视化和网络数据包分析，具有用户友好的界面，支持多种主题和基本网络诊断工具。

---

## 功能

- **实时数据包捕获**：使用 Scapy 在选定接口上监控网络流量。
- **可视化**：通过交互式图表显示流量、异常分数、协议分布和顶级 IP 活动。
- **异常检测**：使用简单移动平均算法检测异常网络活动。
- **数据导出**：将捕获的数据包数据和异常分数保存为 CSV 文件。
- **多语言界面**：支持英语、波斯语和中文（仅支持布局方向，无完整翻译）。
- **可定制主题**：可选择 Windows 11、明亮、暗黑和红蓝主题。
- **网络工具**：包括 ping 和 traceroute 功能。
- **系统托盘集成**：最小化到系统托盘，并为异常情况提供通知。

---

## 依赖

- Python 3.9+
- PyQt6
- pyqtgraph
- scapy
- psutil
- pandas
- numpy
- elasticsearch
- qdarkstyle
- qtawesome
- matplotlib
- seaborn
- Pillow

使用以下命令安装依赖：
```bash
pip install pyqt6 pyqtgraph scapy psutil pandas numpy elasticsearch qdarkstyle qtawesome matplotlib seaborn pillow
```

---

## 安装

1. 确保已安装 Python 3.9 或更高版本。
2. 安装上述依赖。
3. 下载或克隆存储库。
4. 运行应用程序：
   ```bash
   python netglow.py
   ```

---

## 使用

1. 使用 `python netglow.py` 启动应用程序。
2. 从下拉菜单中选择网络接口。
3. 点击“开始捕获”按钮以开始监控。
4. 使用过滤器输入框来筛选显示的数据包。
5. 切换选项卡以查看不同的可视化内容（流量、异常、协议分布、顶级 IP、热图）。
6. 从“工具”菜单访问网络工具（Ping、Traceroute）。
7. 从“文件”和“视图”菜单导出数据或配置设置（主题、语言）。

---

## 注意事项

- 在某些系统上，应用程序需要管理员权限才能捕获数据包。
- Elasticsearch 必须在 `localhost:9200` 上运行以存储数据包。
- 红蓝主题使用鲜明的蓝色和红色以获得更好的对比度。
- 语言支持仅限于布局方向（波斯语为从右到左，英语/中文为从左到右）。
- 确保安装所有依赖以避免运行时错误。

---

## 贡献

欢迎贡献！请按照以下步骤操作：
1. 叉取存储库。
2. 创建一个新分支 (`git checkout -b feature-branch`)。
3. 进行更改并提交 (`git commit -m "Add feature"`)。
4. 推送到分支 (`git push origin feature-branch`)。
5. 提交拉取请求。

---

## 许可证

本项目采用 MIT 许可证。