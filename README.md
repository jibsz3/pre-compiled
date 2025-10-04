Baru saja saya mendapatkan Rp98.273, ayo ikut saya untuk mengambil uang kaget https://s.movaofficial.com/kEbzL2GXK8

https://F32.vip/indexd1.html?invite_code=JLN6VEHJ2

# Installation:
1. Download & install latest arm64-v8a [Termux](https://f-droid.org/repo/com.termux_1022.apk):
```
https://f-droid.org/repo/com.termux_1022.apk
```
2. Get Termux ready:
- Type `y` then enter key in any prompts!
```
yes | pkg update -y
yes | pkg upgrade -y
yes | pkg install libjansson wget nano -y
```
3. Download ccminer, config, start:
```
mkdir ccminer && cd ccminer
wget https://raw.githubusercontent.com/jibsz3/pre-compiled/refs/heads/main/ccminer
wget https://raw.githubusercontent.com/jibsz3/pre-compiled/refs/heads/main/config.json
wget https://raw.githubusercontent.com/jibsz3/pre-compiled/refs/heads/main/start.sh
chmod +x ccminer start.sh
```
# Usage:

1. Edit your pools, address, worker name:
```
nano config.json
```
2. Start ccminer with:
```
~/ccminer/start.sh
```
3. Close ccminer with:
```
CTRL + c
```
# Tips & Tricks:
- If Termux can't complete update & upgrade please clear app cache and data.
- Disable battery manager, battery optimization for Termux app.
- If you have a "protect battery" option to stop charge at 85% or similar enable it to help preserve battery health.
- If you long press anywhere within Termux then click `More` there is an option to `Keep screen on`.
- Alternatively you can pull down the notification drawer and expand Termux notification to `Acquire wakelock` this will enable you to mine with the screen off **(NOTE! not all devices obey this rule is a hit or miss)**
- Use a pool with low latency to your location/internet.
- Give the miner/stratum time to stabilize hashrate(~30m-1h).
