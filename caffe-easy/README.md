SSD方面请参见：https://github.com/weiliu89/caffe/tree/ssd<br/>

# 编译：
## CPU编译
要求工具Visual Studio 2013<br/>
1.下载依赖库[3rd (158MB)](http://www.zifuture.com/fs/3.build/3rd.rar)并解压到这个目录下<br/>
2.打开windows-cpu/windows-cpu.sln<br/>
3.编译即可，结果会在Build目录下的相应位置<br/>

## GPU编译
1.下载依赖库[3rd (158MB)](http://www.zifuture.com/fs/3.build/3rd.rar)并解压到这个目录下<br/>
2.安装[CUDA](https://developer.nvidia.com/cuda-downloads)，注意要求先装VS2013再装CUDA<br/>
3.设置环境变量CC_CUDA_VERSION，值为CUDA版本，比如8.0或者7.5<br/>
4.打开windows-gpu/windows-gpu.sln编译即可<br/>


## 编译好的包包
[win32-cpu (13.1MB)](http://www.zifuture.com/fs/3.build/win32-cpu.rar)<br/>
[x64-gpu-cuda8.0 (18.99MB)](http://www.zifuture.com/fs/3.build/x64-gpu-cuda8.0.rar)<br/>
[x64-gpu-cuda7.5 (23.48MB)](http://www.zifuture.com/fs/3.build/x64-gpu-cuda7.5.rar)<br/>
