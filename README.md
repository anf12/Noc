这里是一个示例config文件，
把它下载到$spec17root/config目录下。
然后把rv64g.cfg文件中的define gcc_dir 后面的部分改为/path/to/toolchain。
cd $spec17root
source shrc
runcpu -config=rv64g -action build all tune=base
