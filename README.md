<h1 align="left">DogeWorkFlow</h1>
<p2>Github Actions Project for the following purposes.</p2>
<br>

- RDP (Windows,Mac-OS,Linux)
- Apk Builder (Build apk from android studio files hosted in any repo on github)
- DDoS Tool (Rath-DDoS)
- SSH (Free SSH trminal, [Ubuntu & Mac-OS])

<h1 align="center">Disclaimer for RDP</h1>
<p2>You must create Ngrok account & Add your authtoken in secrets</p2> <br>
<br>

- Create account [Ngrok](https://dashboard.ngrok.com/)
- Get Auth Token [https://dashboard.ngrok.com/get-started/your-authtoken](https://dashboard.ngrok.com/get-started/your-authtoken)
- Add it in your repository as secrets [NGROK_AUTH_TOKEN](https://github.com/Did-Dog/RDP/settings/secrets/actions)
- VNC_PASSWORD & VNC_USER_PASSWORD [Fill it according to your needs.
- 
  ![image](https://github.com/Did-Dog/RDP/assets/94751052/36312e6d-1e7b-4706-b549-200c48586d2e)

## Windows 10 RDP
- Using NGROK & Github Actions
- ./actions/workflows/main_windows_RDP.yml

## Ubuntu RDP
- Using NGROK & Github Actions
- ./actions/workflows/main_ubuntu_RDP.yml

## Mac-OS RDP
- Using NGROK & Github Actions
- ./actions/workflows/main_macOS_RDP.yml

<br>

------------------------------

## Android Apk Builder
- Build apk from repositories which contain android app build files
- ./actions/workflows/build_android_apk.yml
- Sample Repo [here](https://github.com/android/sunflower)
  ![image](https://github.com/Did-Dog/RDP/assets/94751052/f680566d-4f57-42d7-ae9d-f665c88b0354)

<br>

------------------------------



## Terminal Share SSH
- Share terminal across internet using Github Actions & https://tmate.io
- ./actions/workflows/remote_terminal_ssh.yml

## DDoS Tool
- Using Github Actions DDOS attack.
- ./actions/workflows/rath_ddos.yml
 ![image](https://github.com/Did-Dog/RDP/assets/94751052/d54ab5e4-50e5-4019-8698-d543fd015bbc)

<br>

------------------------------


