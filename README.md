# PyTorch wheels for Raspberry Pi 4 
![output image]( https://qengineering.eu/images/PyTorch_icon.webp )<br/><br/>

Find your operating system and Pytorch version in the table below. Follow the instructions in the provided guide.<br/>
There is no Raspberry Pi 32-bit wheel available due to unsupported libraries.<br/>
The Jetson Nano wheels supports **CUDA 10.2**, **cuDNN 8.0** and **NEON**. They can also be used on the (AGX) Xavier.<br/>

-----------------

Wheel: the installation wheel torch-_version_-cp**xx**-cp**xx**-linux_aarch64.whl (xx is the used python version)<br/>
Vision: the accompanying torchvision.<br/>
LibTorch: the C++ API for those who like to program. (The aarch64 version of libtorch-cxx11-abi-shared-with-deps-1.10.1+cpu.zip)<br/>
Guide: link to the installation tutorial.<br/>
## Roadmap.
| Operating system  | PyTorch 1.12.0 | PyTorch 1.11.0 | PyTorch 1.10.0 |  PyTorch 1.9.0 |  PyTorch 1.8.0 |  PyTorch 1.7.0 |
| ----------------- | :------: | :------: | :------: | :------: | :------: | :------: |
| Raspberry Pi **64-bit Buster**<br/>(Python 3.7)| |[Wheel](https://drive.google.com/file/d/1gAxP9q94pMeHQ1XOvLHqjEcmgyxjlY_R/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1btEPxKYfL6OP1Xaedly-ttfPTH-mu4fp/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1sj2V0RONtSLHHjmQ904U82YjdV0TM5bf/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-raspberry-pi-4.html)|[Wheel](https://drive.google.com/file/d/1y-X1UGC43xUfnycJcuDp7tlyFi8QHxvs/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1uQgjrucNSfpliGBWeKUOuo4XGWiBaxQx/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1nC_gWNjFirZz74wV4z7t2un4ktCtlRpI/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-raspberry-pi-4.html)| [Wheel](https://drive.google.com/file/d/18KztAf3W_kqFYP2f9uqLj3HBdhoMvVe4/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1XyYG6hHh7QYaLrvE-mByvhNK_0rLOd0G/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1yhFMxngRq_RY2DPWwqZ8wwNmzBBjzrHR/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-raspberry-pi-4.html) | [Wheel](https://drive.google.com/file/d/1JF3x556B1ZPe7rp3ogyZiCJPCDsu57RY/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1isEX4w4oegkYpv7WalvYPkTpPCcI4CUR/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1kpAb7qIGD0ICy8HYHDGMiY0Yj-K-eGAP/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-raspberry-pi-4.html) | [Wheel](https://drive.google.com/file/d/1o2PjvvKkHpYx7QMfMLUoNck7ZiE_TGgR/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1H3YLkOicAN78tBLAmzCx2lt_WBjjmFCz/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1XpdE-AG4QMz1HE8bDdpiKw1Fpl3Em0kK/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-raspberry-pi-4.html) ||||||||
| Raspberry Pi **64-bit Bullseye**<br/>(Python 3.9) | | [Wheel](https://drive.google.com/file/d/1ilCdwQX7bq72OW2WF26Og90OpqFX5g_-/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1oDsJEHoVNEXe53S9f1zEzx9UZCFWbExh/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1-kTx72-6eePrXVjFtJN-3ntu1DCI8FuD/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-raspberry-pi-4.html) | [Wheel](https://drive.google.com/file/d/10zJmU1f7PoxN8ARZol4mtbwok4G23XKZ/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1nX4uSoubwq8NB9k-2DF6LbPyiqwocgEW/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1z58SN6Inh3ka_jFs97LefBuvfGq9o1to/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-raspberry-pi-4.html) | [Wheel](https://drive.google.com/file/d/1p9Sp5YmCJwIkmQIWkpuIkE4NgeYPOr-U/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/13fKq1V-zLbLBWPw3zP4EZxyMXyOiJWPi/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1My9PPoa9oYv7ZaPdsoXq4FyqRCHHA_4c/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-raspberry-pi-4.html) | [Wheel](https://drive.google.com/file/d/1E4bP9NAG5pDSXGWYPGsJ5uzFBq47VN14/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1mqNqUC1t0MekF5h1WCEqt3soKWhc6Py4/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1PrqFOPHxrbLGEMuxBTxYY-Ubjk-l88_Z/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-raspberry-pi-4.html) |  ||||||||
| Raspberry Pi **Ubuntu 18.04**<br/>(Python 3.6) | |  |  |  | [Wheel](https://drive.google.com/file/d/18WNCbSLeQCZUJuXf-0yhzopDR6p4SkYn/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1QhUPbWvotJQyUfF8ZxYgFHDPHLQagC3U/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1ORi9-9q82CoxdL7TmnZ7-e3qFzqJ-DAD/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-raspberry-pi-4.html) | [Wheel](https://drive.google.com/file/d/1ciFrD5BekDd1ubVOCwK-oGfSUJwF8_WA/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1hpJ_5esV4VAHy8Bq8ZJ8SuD2w8M8Dw3m/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1wbJTRxrFHZ6UOAzZ8w8RU0rYdyWibDNS/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-raspberry-pi-4.html) |  
| Raspberry Pi **Ubuntu 20.04**<br/>(Python 3.8) | |  | [Wheel](https://drive.google.com/file/d/1W7hhNG_HJUyY0sk1dBikbSRyAJr_Nyc4/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1SmWRjEyizWT7iumXUZATZuBSfQt0gJ8o/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1iV2c7fENEG8L6-9l2CL_0o5Z1kJ53YB-/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-raspberry-pi-4.html) | [Wheel](https://drive.google.com/file/d/12GH3r-uaRxUIzcHHWcfXtisXk71OZbF0/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1VgEinJIu5e38h1aKaFSn8A1F1MaNeM5g/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1bC34mTPJbtHZX_c675dUdmFHo8d8X9jT/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-raspberry-pi-4.html) ||||
| Jetson Nano JetPack 4.6<br/>(Python 3.6) | | | [Wheel](https://drive.google.com/file/d/1TqC6_2cwqiYacjoLhLgrZoap6-sVL2sd/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1C7y6VSIBkmL2RQnVy8xF9cAnrrpJiJ-K/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1izv6kmcnqXk9i7-Ey-vldjC-CGfHOGCl/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-jetson-nano.html)| [Wheel](https://drive.google.com/file/d/1wzIDZEJ9oo62_H2oL7fYTp5_-NffCXzt/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1Q2NKBs2mqkk5puFmOX_pF40yp7t-eZ32/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1E4Hfz1cj6bwGz8a72OS5uH3SnlvRyrOi/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-jetson-nano.html) | [Wheel](https://drive.google.com/file/d/1-XmTOEN0z1_-VVCI3DPwmcdC-eLT_-n3/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1BdvXkwUGGTTamM17Io4kkjIT6zgvf4BJ/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-jetson-nano.html) | [Wheel](https://drive.google.com/file/d/1aWuKu8eqkZwVzFFvguVuwkj0zdCir9qX/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1aWuKu8eqkZwVzFFvguVuwkj0zdCir9qX/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-jetson-nano.html) |
| Jetson Nano Ubuntu 20.04<br/>(Python 3.8) | [Wheel](https://drive.google.com/file/d/1MnVB7I4N8iVDAkogJO76CiQ2KRbyXH_e/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/11DPKcWzLjZa5kRXRodRJ3t9md0EMydhj/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1t0MM1Bec2XIIKK8PhQbEDOrM1Z2Xym5-/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-jetson-nano.html) | [Wheel](https://drive.google.com/file/d/1AQQuBS9skNk1mgZXMp0FmTIwjuxc81WY/view?usp=sharing)<br/>[Vision](https://drive.google.com/file/d/1BaBhpAizP33SV_34-l3es9MOEFhhS1i2/view?usp=sharing)<br/>[LibTorch](https://drive.google.com/file/d/1OSWB_Wv7rghpiBI3V9Rvj0ZR6bRcAZsY/view?usp=sharing)<br/>[Guide](https://qengineering.eu/install-pytorch-on-jetson-nano.html)|||

We compiled all wheels with the **clang** compiler to prevent issues with the ARM NEON registers and the GNU compiler.<br/>
For instance [#61110](https://github.com/pytorch/pytorch/issues/61110) and [#65673](https://github.com/pytorch/pytorch/issues/65673).<br/><br/>
![output image]( https://qengineering.eu/images/ClangRPi.png )<br/><br/>
![output image]( https://qengineering.eu/images/Torch_1_10_0_Jetson_Succes_GitHub.webp )<br/><br/>


#### :heavy_exclamation_mark: C++ programmers please note
You should also use the clang compiler if you want to compile C++ code yourself.<br/>
The GNU GCC compiler will give you 'no expression errors'.<br/>
```
# set clang compiler at the command line
$ export CC=clang
$ export CXX=clang++

```
Don't worry if you plan to use Python. It only applies to C++ users.<br/>

-----------------

![output image](https://qengineering.eu/images/SDcard16GB_tiny.jpg) Find PyTorch and TorchVision with other frameworks and deep-learning examples on our [SD-image](https://github.com/Qengineering/RPi-image)

-----------------

[![paypal](https://qengineering.eu/images/TipJarSmall4.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CPZTM5BB3FCYL)
