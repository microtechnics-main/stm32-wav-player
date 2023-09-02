# STM32 audio player.

Example project for playing WAV audio files from SD-card connected to SDIO microcontroller interface. Block diagram looks like the following:

<img src="https://microtechnics.ru/wp-content/uploads/2020/12/sd-card-stm32-3.jpg" width="400">

SDIO is used in 4-bit mode, one DAC channel is connected directly to LM386 amplifier input:

<img src="https://microtechnics.ru/wp-content/uploads/2020/10/lm386-600x325.jpg" width="400">

Detailed description is available [there](https://microtechnics.ru/audio-pleer-na-stm32-vosproizvedenie-wav-fajla/). Demo project is built for STM32F103VE with IAR Embedded Workbench.
