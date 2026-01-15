# STM32F405RGT6-INAV-FIRMWARE

sudo apt update
sudo apt-get install git
sudo apt-get install make
sudo apt-get install cmake
sudo apt-get install ruby
sudo apt install -y git make gcc-arm-none-eabi python3 python3-pip

cd ~
git clone https://github.com/iNavFlight/inav.git
cd inav

git checkout tags/9.0.0-RC4

cd inav
mkdir build
cd build
cmake ..
generating done

make (You File)




