 <center>
     <h1>彭韵贻</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             15016034468
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             2405848522@qq.com
         </span>
         ·
         <span>
             <img src="assets/github-brands.svg" width="18px">
             <a href="https://github.com/1231Lisette">1231Lisette</a>
         </span>
         ·
         <span>
             <img src="assets/rss-solid.svg" width="18px">
             <a href="#">My Blog</a>
         </span>
     </div>
 </center>


 ## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息 

 - 女，2004 年出生

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 学士，广东工业大学，信息工程专业，2023.9~至今
- 绩点：3.993，年级前
- 英语四级598分，六级581分

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- **基于 PCL 的建筑测绘点云处理与三维重建系统** 

  *C++(PCL库)，Linux Shell，CloudCompare，Cmake，Json*

  该项目开发了一套基于 PCL（Point Cloud Library）的自动化建筑测绘方案，通过点云预处理、特征提取及 Revit 协同建模，实现了低成本、高精度的三维模型重建 。在项目中，**我负责算法调研与系统调试**，利用 **PCL** 库深入实践了 条件滤波、体素下采样及欧式聚类等核心算法，并提出了“基于点云密度分布”的自适应高度测量思路以优化构件分割 。我通过 **Linux Shell** 脚本与 **CloudCompare** 建立了高效的开发调试流与质量分析体系，确保了 C++ 算法逻辑及 **JSON** 数据导出的稳定性 。在该流程下，构件提取精度较传统 PCA 方法提升了 1% 至 10%，有效支撑了建筑测绘从原始点云到 Revit三维重建的自动化方案 。

  https://github.com/1231Lisette/pcl

- **基于stm32与树莓派的ros小车**

  *C，Linux Shell，Python，Cmake，ROS*

  该项目是在电赛备赛2023年空地协防题目准备的小车，底盘包括亚博智能一套的铝合金、L型520电机、四路编码器电机驱动，顶层装有t265,负责视觉和定位；陶晶驰串口屏，负责显示当前位置信息；树莓派4b，装有ubuntu20.04,基于ros话题发布与订阅负责与上位机进行通信。

  https://github.com/1231Lisette/mycar（最初方案，带有stm32）

- **2025年电子设计大赛无人机H题《野生动物巡查系统》的地面站部分**

  *Python，Linux Shell，ROS，HMI*

  该地面站主要由陶晶驰串口屏、树莓派4b与电池构成，可实现巡查前根据现场指定的禁飞区方格代码，用按键设置禁飞区；画出巡查航线，航线需覆盖禁飞区以外所有方格；巡查发现某方格中有野生动物时，识别动物种类及数量；实时显示并保存方格代码、动物名称及数量；无人机完成巡查后,可调出显示所发现动物的名称及每种动物数量的功能。地面站显示是用一个陶晶驰写的软件usart来设计显示界面与逻辑，umi文件；串口屏幕通过串口与树莓派通信；地面站与无人机通过树莓派的wifi模块局域网通信，数据基于ros的话题发布与订阅进行转发。

  https://github.com/1231Lisette/2025TI_GS_and_Com

- **基于yolov8的ht22控制框智能化检测与分类**

  *Python，Linux Shell，Pytorch，YOLOv8，opencv*

  该项目基于 Python 与 PyTorch 框架，利用 YOLOv8 算法构建了 HT22 控制框图像智能检测系统，实现了电路板及螺丝状态的精准识别。在主导模型全流程训练与调优过程中，通过对 YOLOv8n/s/m 版本的性能对比，选定 YOLOv8s为最优方案，使 mAP50 指标达到0.9886。凭借敏锐的数据洞察力，纠正了原始数据中“无螺丝”与“电路板”标签互换的逻辑错误，消除模型误检；同时开展超参数敏感性实验，确定BatchSize=16为最佳配置，使电路板检测精度提升 0.956，成功实现了高精度的工业异常状态自动化检测。

  https://github.com/1231Lisette/htt2_classification

- **基于lerobot的SOarm101微调smolvla**

  本项目基于 Lerobot 框架与 SmolVLA 模型，实现了机械臂在视觉语言指令下的多任务抓取与放置操作。通过收集多样化的演示数据、微调预训练模型，并在真实机械臂上进行了部署与推理测试，验证了模型在有限数据下的泛化能力与任务理解能力。
  
  https://github.com/1231Lisette/smolvla_demo
  
  https://www.bilibili.com/video/BV1ChiwBiERY/?share_source=copy_web&vd_source=b2f5f15ffb50d524fd0a4fe436c43b83

- **基于lerobot和xlerobot微调pi0.5和smolvla**

  本项目基于 Lerobot 框架与 SmolVLA 、PI0.5模型，实现双臂抓取物品——打开抽屉——将物体放进抽屉——关闭抽屉的长任务。

  https://www.xiaohongshu.com/user/profile/5edb8bb4000000000101dc11/6967b7f7000000000a02c791?xsec_token=AB8AMgQ9_r1PC76AoAuyxwHv1muvphDFcrc59KmNhSfac=&xsec_source=pc_user

## <img src="assets/prize.svg" width="40px"> 获奖经历

- 2023-2024年优秀学生二等奖奖学金
- 2024年广东省大学生数学建模竞赛暨全国大学生数学建模竞赛广东省分赛三等奖
- 第十八届iCAN大学生创新创业大赛（华南赛区）三等奖
- 第十六届全国大学生数学竞赛（非数学A类）二等奖
- 第十六届蓝桥杯全国软件和信息技术专业人才大赛广东赛区EDA设计与开发大学组三等奖
- 第十二届“大唐杯”全国大学生新一代信息通信技术大赛ICT基础通识赛广东省赛区三等奖
- 2024-2025优秀学生一等奖奖学金
- 2025年全国电子设计大赛广东赛区成功参赛奖

## <img src="assets/tools-solid.svg" width="30px">  技能清单

- ★★★ Python
- ★★★ C
- ★★☆ C++
- ★★☆ ROS
- ★★☆ Shell
- ★☆☆ PR
- ★★☆ PS
- ★★★ word、ppt
- ★☆☆ excel

---

<a href="Resume.pdf" target="_blank">Download PDF</a>

