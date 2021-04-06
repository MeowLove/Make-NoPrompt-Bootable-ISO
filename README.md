<div align="center">
  <a href="https://github.com/MeowLove/OpenWRT-Virtualization-Servers">
      <img src="https://raw.githubusercontent.com/MeowLove/Make-NoPrompt-Bootable-ISO/master/background/CXT_Logo.png"  >
  </a>
  <h1 align="center">
    Make-NoPrompt-Bootable-ISO <br>（制作-无需按键提示-可启动ISO）
  </h1>
  <h3 align="center">
    制作一个无需按键直接启动的Windows操作系统ISO。  <br> （Make a NoPrompt Bootable Windows ISO.  ） <br><br>
  </h3>
  <h3 align="center">
    禁用和去除Windows操作系统“按任意键从光盘或数字视盘启动”工具。    <br> （Disable and Remove Windows ISO "Press any key to boot form CD or DVD" Tools.   ） <br><br>
  </h3>
 

<br>
<img src="https://raw.githubusercontent.com/MeowLove/Make-NoPrompt-Bootable-ISO/master/background/Preview_press_any_key_to_boot_from.png">
<br>  

Is extracted from Windows 20H2 x64 by CXT and is generally compatible.  
If you have your own file, you can replace it with the startup file you own.  

CXT从Windows 20H2 x64中提取的，一般是兼容的。  
如果您有自己的文件，您可以用自己的启动文件替换它。  

- \efi\microsoft\boot\
- \boot\
- ...
<br>

# How to Use（如何使用）
- 1.Unzip the Windows ISO you downloaded.
- 2.remove \boot\bootfix.bin
- 3.Replace the [Replaced_Files] directory file, find the same name, and replace them in your unzipped folder.
- 4.Modify [Make_Bootable_NoPrompt_Windows_ISO.bat] the path of each file and folder to be your file local path.
- 5.Run [Make_Bootable_NoPrompt_Windows_ISO.bat], and you will get a windows installation image that starts directly without prompting.  

<br>

- 1、解压你下载的Windows ISO。
- 2、移除 \boot\bootfix.bin
- 3、替换【Replaced_Files】目录文件，在你的解压文件夹，寻找相同名称，替换掉他们。
- 4、修改【Make_Bootable_NoPrompt_Windows_ISO.bat】各个文件和文件夹的路径为你的文件本地路径
- 5、运行【Make_Bootable_NoPrompt_Windows_ISO.bat】，你将得到直接启动无需提示的Windows安装镜像。

<br>

# Reference and mention：
[Oscdimg Command-Line 选项](https://docs.microsoft.com/zh-cn/windows-hardware/manufacture/desktop/oscdimg-command-line-options)
[Microsoft official technical documents](https://docs.microsoft.com/zh-cn/archive/blogs/jhoward/hyper-v-generation-2-virtual-machines-part-9)

https://www.cxthhhhh.com