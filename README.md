<h1 align="center">Merhaba 👋, ben Ahmet</h1>
<h3 align="center">Silikonla yazılımın el sıkıştığı yerde yaşıyorum ⚡</h3>

```c
static const struct engineer ahmet = {
    .name     = "Ahmet Talha Ardıç",
    .role     = "Embedded Software Engineer",
    .speaks   = { "C", "C++", "Python", "C#", "Bash" },
    .silicon  = { "TI C2000", "MSP430", "TM4C", "STM32", "NXP", "ARM Cortex-M" },
    .os       = { "bare-metal", "FreeRTOS", "Zephyr", "TI-RTOS", "Embedded Linux" },
    .buses    = { "UART", "SPI", "I2C", "CAN", "RS232/422/485", "TCP/UDP", "LoRa" },
    .believes = "modüler > kopyala-yapıştır",
};

int main(void)
{
    board_bring_up(&ahmet);   /* ilk LED yandığında gelen o mutluluk */

    for (;;) {
        read_datasheet();
        write_code();
        blame_hardware();     /* genelde yazılım çıkıyor */
    }
}
```

### 📚 Yaşadığım katmanlar

```
┌────────────────────────────────┐
│           Uygulama             │  ◄── buraya sağlam zemin hazırlarım
├────────────────────────────────┤
│     RTOS · Embedded Linux      │  ◄── zamanlama da benden sorulur
├────────────────────────────────┤
│     BSP · HAL · Sürücüler      │  ◄── evim burası 🏠
├────────────────────────────────┤
│          Bootloader            │  ◄── ilk çalışan kod benimki
├────────────────────────────────┤
│      MCU / DSP · Donanım       │  ◄── şematiğiyle, datasheet'iyle tanışırım
└────────────────────────────────┘
```

### 🧠 Know-how

- 🔌 **Board bring-up:** Şematiği okur, karta ilk kez güç verilirken nefesimi tutar, saat ağacını ayağa kaldırırım
- 🧱 **BSP, HAL ve sürücüler:** Platformdan bağımsız, taşınabilir sürücü ve sensör kütüphaneleri yazarım
- 🚀 **Bootloader ve firmware güncelleme:** Flash yönetimi, wear leveling; güncelleme sırasında kartın tuğlaya dönmemesi için
- ⏱️ **Gerçek zamanlı yazılım:** Bare-metal ya da RTOS üzerinde deadline kaçırmayan firmware
- 🐧 **Embedded Linux:** Çekirdek sürücüleri (HDMI/SDI alıcıları dahil) ve Yocto ile kendi dağıtımını pişirmek
- 📡 **Haberleşme:** lwIP ile TCP/UDP (unicast/multicast), seri hatlar, CAN ve LoRa; hattan son baytına kadar veri sıkıştırmak
- 🔬 **Donanımda hata ayıklama:** Osiloskop ve lojik analizör; çünkü sinyal yalan söylemez
- 🧪 **Test:** Unit test, TDD, HIL ve CI/CD; hata sahada değil masada patlasın
- 🤖 **Robotik:** ROS ve LIDAR tabanlı SLAM ile otonom bir mobil robot
- ✨ **Yapay zekâ destekli geliştirme:** Claude Code ile datasheet'ten koda daha hızlı

### 💬 Benimle konuşabileceğin konular

"Bu SPI neden çalışmıyor?", "Bu sürücüyü başka bir karta nasıl taşırım?", "Bootloader'ım nereye zıpladı?" ve gömülü dünyaya dair her şey 🙂

### 📫 Bana ulaş

<p align="left">
<a href="https://linkedin.com/in/ahmet-ardic" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="ahmet-ardic" height="30" width="40" /></a> &nbsp; <b>5ahmettardic8@gmail.com</b>
</p>

### 🧰 Alet çantam

<p align="left"> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40"/> </a> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> </p>

![FreeRTOS](https://img.shields.io/badge/FreeRTOS-3C8F3C?style=for-the-badge) ![Zephyr](https://img.shields.io/badge/Zephyr-7929D2?style=for-the-badge) ![Yocto Project](https://img.shields.io/badge/Yocto_Project-0D5EAF?style=for-the-badge) ![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white) ![Texas Instruments](https://img.shields.io/badge/Texas_Instruments-CC0000?style=for-the-badge) ![NXP](https://img.shields.io/badge/NXP-000000?style=for-the-badge&logo=nxp&logoColor=white) ![ARM Cortex-M](https://img.shields.io/badge/ARM_Cortex--M-0091BD?style=for-the-badge&logo=arm&logoColor=white) ![CMake](https://img.shields.io/badge/CMake-%23008FBA.svg?style=for-the-badge&logo=cmake&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) ![Altium Designer](https://img.shields.io/badge/Altium_Designer-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white) ![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white) ![ROS](https://img.shields.io/badge/ros-%230A0FF9.svg?style=for-the-badge&logo=ros&logoColor=white) ![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)

🔬 Masamda da: osiloskop, lojik analizör, sinyal jeneratörü ve her zaman biraz eksik çıkan jumper kablolar.

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=AhmetArdic&theme=synthwave&hide_border=false&include_all_commits=false&count_private=true)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=AhmetArdic&theme=synthwave&hide_border=false&include_all_commits=false&count_private=true&layout=compact)

---
<p align="center"><i>Bir LED yanıp söndüyse, gün iyi geçmiştir. 💡</i></p>

[![](https://visitcount.itsvg.in/api?id=AhmetArdic&icon=5&color=0)](https://visitcount.itsvg.in)
