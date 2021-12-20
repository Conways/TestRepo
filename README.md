# TestRepo
TestRepo



sudo apt-get install git-core gnupg flex bison build-essential zip curl zlib1g-dev gcc-multilib g++-multilib libc6-dev-i386 libncurses5 lib32ncurses5-dev x11proto-core-dev libx11-dev lib32z1-dev libgl1-mesa-dev libxml2-utils xsltproc unzip fontconfig



repo init -u https://android.googlesource.com/platform/manifest -b android-11.0.0_r46


repo init -u https://aosp.tuna.tsinghua.edu.cn/platform/manifest -b android-11.0.0_r46


c35s1.jamjams.net





29233    aes-256-gcm  


10，开始下载对应的驱动
https://source.android.com/setup/start/build-numbers
这里找到对应的编号如android-11.0.0_r46 对应 RQ3A.211001.001
进入https://developers.google.com/android/drivers 搜索编号 找到驱动下载链接

下载完成后，在源码目录下解压
执行 ./extract-google_devices-blueline.sh
./extract-qcom-blueline.sh
命令后，同意协议后开始提取，会生成vendor文件夹
