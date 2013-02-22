linaro
======

This is the linaro toolchain needed to compile my kernel

git clone this repo in $HOME_DIRECTORY/android/system/prebuilt/linux-x86/toolchain

e.g.

cd ~/
cd android/system/prebuilt/linux-x86/toolchain
git clone git://github.com/Albinoman887/linaro.git

Then just make sure in your BoardConfig.mk your hare TARGET_KERNEL_CUSTOM_TOOLCHAIN := linaro
