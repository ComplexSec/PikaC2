<div align="center">
  <img width="400'px" src="images/pikac2.png" />
  <h1>PikaC2</h1>
  <br/>

  <p><i>PikaC2 is a modern command and control framework written in Go & Python3, created by <a href="https://twitter.com/SecComplex">Complexity</a>.</i></p>
  <br />

  <!-- <img src="assets/Screenshots/FullSessionGraph.jpeg" width="90%" /><br /> -->
  <!-- <img src="assets/Screenshots/MultiUserAgentControl.png" width="90%" /><br /> -->
  
</div>

> [!IMPORTANT]  
> PikaC2 is a labour of love created by an inexperienced developer to better understand how C2's function and operate. This is not meant to be a replacement of your current C2.

> [!CAUTION]
> PikaC2 is still in early development. Bugs and unexpected errors/problems may arise during use. These will be remedied in future patches and updates as the framework matures.

### Quick Start

> Please see the [Wiki](https://github.com/ComplexSec/PikaC2/wiki) for complete documentation.

PikaC2 works well on Debian 10/11, Ubuntu 20.04/22.04 and Kali Linux. It's recommended to use the latest versions possible to avoid issues. You'll need a modern version of Qt and Python 3.10.x to avoid build issues.

See the [Installation](https://github.com/ComplexSec/PikaC2/wiki#installation) guide in the Wiki for instructions. If you run into issues, check the [Known Issues](https://github.com/ComplexSec/PikaC2/wiki#known-issues) page as well as the open/closed [Issues](https://github.com/ComplexSec/PikaC2/issues) list.

---

### Features

#### Client

> Cross-platform UI written in C++ and Qt

- Modern, dark theme based on [Dracula](https://draculatheme.com/)


#### Teamserver

> Written in Golang

- Multiplayer
- Payload generation (exe/shellcode/dll)
- HTTP/HTTPS listeners
- Customizable C2 profiles 
- External C2

#### Demon

> PikaC2's flagship agent written in C and ASM

- Sleep Obfuscation via [Ekko](https://github.com/Cracked5pider/Ekko), Ziliean or [FOLIAGE](https://github.com/SecIdiot/FOLIAGE)
- x64 return address spoofing
- Indirect Syscalls for Nt* APIs
- SMB support
- Token vault
- Variety of built-in post-exploitation commands
- Patching Amsi/Etw via Hardware breakpoints
- Proxy library loading
- Stack duplication during sleep. 

### Community
You can join the official [PikaC2 Discord](https://discord.gg/J8raj7TaY9) to chat with the community! 
