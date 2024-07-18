# Ryzentosh Lenovo IdeaPad 3 15ALC6

I share my experience and use of Ryzentosh on my Lenovo IdeaPad 3 15ALC6. See the specifications below:

- CPU: AMD Ryzen™ 7 5700U
- GPU: AMD Radeon™ Graphics
- RAM: 20GB
- ROM: External SSD 110GB

- [All Specs](https://psref.lenovo.com/syspool/Sys/PDF/IdeaPad/IdeaPad_3_15ALC6/IdeaPad_3_15ALC6_Spec.pdf)

Please generate your information with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

After installation, it shows me the processor as i5. I don't know why, but it doesn't matter as long as it's working.

## What's working?

| Device       | Working           | Observation                           |
| :----------- | :---------------- | :------------------------------------ |
| `touchpad`   | `yes`             |                                       |
| `bluetooth`  | `yes`             |                                       |
| `wifi`       | `no`              | Requires kexts to fix                 |
| `keyboard`   | `yes`             |                                       |
| `sound`      | `no`              | Kexts available to fix                |
| `hotkeys`    | `no`              |                                       |
| `brightness adjustment` | `no`   | Requires kexts to fix                 |

## Screenshots

![App Screenshot](https://github.com/adaosanto/ryzentosh-ideapad3-15alc6/blob/main/screens/Screenshot%202024-07-17%20at%2013.07.57.png?raw=true)

![App Screenshot](https://raw.githubusercontent.com/adaosanto/ryzentosh-ideapad3-15alc6/main/screens/Screenshot%202024-07-17%20at%2013.06.05.png)

## FAQ
#### How to use the internet if WIFI doesn't work?
You can use your phone to share the internet via USB. The kext [HoRNDIS](https://github.com/jwise/HoRNDIS) enables this functionality.

#### Does Xcode work?
Working in its latest version along with the iPhone Simulator 15 Pro.

#### Performance?
Very satisfactory performance. It runs smoothly with Xcode 15, iPhone Simulator, VS Code, and a browser open.

## Reference

- [Getting started with OpenCore](https://dortania.github.io/OpenCore-Install-Guide/)
