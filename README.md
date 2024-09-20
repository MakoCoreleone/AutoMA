<!-- markdownlint-disable MD033 MD041 -->
<p align="center">
  <img alt="LOGO" src="https://github.com/MakoCoreleone/AutoMA/blob/main/Ciallo.png" width="256" height="256" />
</p>



# AutoMA
帮你玩《乖离环》大富翁的自动化工具。

## 功能介绍

1.自动化大富翁。
2.（个人精力有限，其他日常慢慢做）

## 食用方法

### Windows

  对于绝大部分用户，请下载 AutoMA-win-x86_64-vXXX.zip
  
  若确定自己的电脑是 arm 架构，请下载 AutoMA-win-aarch64-vXXX.zip
  
  解压后运行 MaaPiCli.exe 即可
  
### macOS
  若使用 Intel 处理器，请下载 AutoMA-macos-x86_64-vXXX.zip
  
  若使用 M1, M2 等 arm 处理器，请下载 AutoMA-macos-aarch64-vXXX.zip
  
  使用方式：
  
  chmod a+x MaaPiCli
  ./MaaPiCli

## 使用说明

在使用工具前完成以下工作：

* 确保游戏可以在模拟器上流畅运行，没有严重的卡顿和延迟
* 将模拟器的显示调整为 横屏(必须) 1280*720(推荐) 240DPI(推荐)
* 打开模拟器的ADB调试选项
* 完成所有游戏资源的下载


> [!WARNING]  
> 对于 **mumu模拟器** 用户，必须**关闭**  其他->后台挂机时保活运行 

初次使用按照终端显示的文本操作：

1. 选择ADB，通常选择自动查找（Auto detect）后选择正在使用的模拟器。如果出现问题，也可以手动输入ADB的绝对路径和端口。
2. 添加任务至任务列表（暂时只有1个功能，慢慢来吧）
3. 默认1项任务是玩一次大富翁，每天最多1000点数，不要浪费体力了，后续更新成自动停止的吧。
4. **【重要】** 按照提示的任务要求操作模拟器，如“开始前无比位于游戏主界面（4个亚瑟打牌那里）”
5. 选择运行任务（Run Task）开始作业
6. 在完成所有任务后，工具会自动停止

如果运行遇到问题（如罢工不动），可以尝试自己点击应该点击的按钮，然后检查流程是否继续运行。若否，重启工具，重新开始流程。

后续再次使用工具时，可以根据需求对任务列表进行修改（Delete Task + Add Task），然后再次运行任务（Run Task）即可。
  
## 鸣谢

本项目由 **[MaaFramework](https://github.com/MaaXYZ/MaaFramework)** 强力驱动！



