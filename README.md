# nvm-tuturial
a simple nvm-tutorial on windows
#1 修改settings.txt // root => nvm.exe 的位置  Path => nodejs的快捷方式的位置（与nvm文件夹平行或自选） arch => 32/64 

#2 加入环境变量win+r => sysdm.cpl =>  用户变量 NVM_HOME = root  //  NVM_SYMLINK = Path 

#3 测试 PATH XX 

#4 $nvm => nvm help ... OK

#5 - $nvm ls => 列出所有安装的node版本
   - $nvm use => 使用需要的node版本
   - $nvm install/uninstall => 安装卸载