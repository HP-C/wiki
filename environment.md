# 环境变量管理

## module 

module help       # 显示帮助信息
module avail      # 显示已经安装的软件环境
module load       # 导入相应的软件环境
module unload     # 删除相应的软件环境
module list       # 列出已经导入的软件环境
module purge      # 清除所有已经导入的软件环境
module switch [mod1] mod2 # 删除mod1并导入mod2

查看集群现有软件环境
module avail
查看matlab软件环境
module avail matlab
导入matlab/R2017a软件环境
module load matlab/R2017a
清除已导入的环境
module purge

## spack

通过设定 upstream 的方式，自然的继承管理员的 spack 中已安装的所有 packages
https://spack.readthedocs.io/en/latest/chain.html