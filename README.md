# security-protocols

The Universal Radio Hacker is a complete suite for wireless protocol investigation with native support for many common URH allows __easy demodulation__ of signals combined with a detection of modulation parameters making it a breeze to identify the bits and bytes that fly over the air.

As data often gets _encoded_ before transmission, URH offers __customizable decodings __ to crack even sophisticated encodings like CC!!)! data whitening.

When it comes to __protocol  reverse-engineering__, URH is helpful in two ways. You can either manually assign protocol fields and message types or let URH __automatically infer protocol fields__ with a rule based intelligence.


Finally, URH entails a __fuzzing component__ aimed at stateless protocols and a __simulation environment__ for stateful attacks.

### Citing URH
We encourage researchers working with URH to cite [this](https://www.usenix.org/conference/woot18/presentation/pohl) WOOT'18 paper or directly use the following BibTex entry.

<details>
  <summary><b>URH BibTeX entry for your research paper</b></summary>
  @inproceedings {220562,
  author = {Johannes Pohl and Andreas Noack},
  title = {Universal Radio Hacker: A Suite for Analyzing and Attacking Stateful Wireless Protocols},
</details>

## Installation
URH runs on Windows, Linux and macOS. See below for OS specific installation instructions.

### Windows, URH can be installed with its [Installer](https://github.com/jopohl/urh/releases). No further dependencies are required.

If you get an error about missing ```api-ms-win-crt-runtime-l1-1-0.dll```, run Windows Update or directly install the software.

### Linux 
#### Installation with pipx
URH is available on [PyPi](https://pypi.org/project/urh/) so you can install it, for example, with [pipx](https://pypa.github.io/pipx/):

```bash
pipx install urh
```

This is the recommended way to install URH on Linux because it comes with __all native extensions__ precompiled.

In order to access your SDR as non-root user, install the according __udev rules__. You can find them in the wiki.


#### Install via Package Manager
URH is included in the repositories of many linux distributions such as __Arch Linux__, __Gentoo__, __Fedore__, __openSUSE__ or __NixOS__. There is also a package for __FreeBSE__. IF avaiable, simply use your package manager to install URH.

__Note__:For native support, you must install the according ```-dev``` package(s) of your SDR(s) such as ```hackrf-dev```
__before__ installing URH.


#### Docker Images
The official URH docker image is available. It has all native backends included and ready to operate.



























