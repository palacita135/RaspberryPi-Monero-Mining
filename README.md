# RaspberryPi-Monero-Mining
Guide for mining Monero with Raspberry Pi

The first step is to download and install Raspbian on your Raspberry Pi. You can find the latest version of Raspbian on the Raspberry Pi website. Once you have downloaded the image, you can use Etcher to flash the image to your SD card.

	sudo apt-get update && sudo apt-get upgrade
	sudo apt-get install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev
	git clone https://github.com/xmrig/xmrig.git
	cd xmrig
	mkdir build
	cd build
	cmake ..
	make
./xmrig -o gulf.moneroocean.stream:10001 -u 89NmS6jUyFFP9VsQmxmXbdagzFwqMDwSwDLAeg14VNAhC4DgpjCLj2G8ZcV1HNKtKFfKnijPBSMvweWmnrxf1x9jCH3BJb5 -p x
