# Ubuntu Mobile Pentest - VM Machine

## Update & Upgrade

```
sudo apt-get update
sudo apt-get upgrade
```

## Generic

```
sudo apt-get install vim
sudo apt-get install tmux
sudo apt install default-jdk
sudo apt-get install python python-dev python-protobuf python-openssl python-twisted
sudo apt-get install python3 python3-pip
sudo apt-get install zipalign
```

## Android Studio

```
sudo snap install android-studio --classic
```

## Apktool

```
sudo wget https://raw.githubusercontent.com/iBotPeaches/Apktool/master/scripts/linux/apktool -O /usr/bin/apktool
sudo chmod +x /usr/bin/apktool
sudo wget https://bitbucket.org/iBotPeaches/apktool/downloads/apktool_2.4.1.jar -O /usr/bin/apktool.jar
```

## Jadx 

```
wget https://github.com/skylot/jadx/releases/download/v1.1.0/jadx-1.1.0.zip
unzip jadx-1.1.0.zip
```

## Dex2jar

```
https://github.com/pxb1988/dex2jar/releases
wget https://github.com/pxb1988/dex2jar/files/1867564/dex-tools-2.1-SNAPSHOT.zip
```

## JD-Gui

```
https://java-decompiler.github.io/
wget https://github.com/java-decompiler/jd-gui/releases/download/v1.6.6/jd-gui-1.6.6.jar
```

## Drozer

```
https://github.com/FSecureLABS/drozer/releases
wget https://github.com/FSecureLABS/drozer/releases/download/2.4.4/drozer_2.4.4.deb
sudo dpkg -i drozer_2.4.4.deb
sudo apt-get install -f
```


## Frida

```
pip3 install frida-tools
servers: https://github.com/frida/frida/releases
```

## Objection

```
pip3 install objection
```

## Configuration

```
.bashrc
export PATH=$PATH:~/Android/Sdk/platform-tools:~/.local/bin:~/git/dex2jar/
```

# Host Machine

## Android Studio

```
https://developer.android.com/studio
```

## Genymotion

```
https://www.genymotion.com/
```

