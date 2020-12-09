+++
title = "HAL Implementation"

[extra]

level = 3

intro = '''Implementations of embedded-hal for microcontroller families and systems running some OS.

*NOTE* You may be able to find even more HAL implementation crates by searching for
the [`embedded-hal-impl`](https://crates.io/keywords/embedded-hal-impl) and 
[embedded-hal](https://crates.io/keywords/embedded-hal) keywords on crates.io!'''

os = [
  "bitbang-hal",
#  "ftdi-embedded-hal", # no release yet
  "linux-embedded-hal",
]

microchip = [
  "atsamd-hal",
#  "avr-hal", # no release yet
]

nordic = [
  "nrf51-hal",
  "nrf52810-hal",
  "nrf52832-hal",
  "nrf52840-hal",
]

nxp = [
  "lpc55s6x-hal",
  "lpc8xx-hal",
  "mkw41z-hal",
  "imxrt-hal",
]

sifive = [
  "e310x-hal",
]

stm = [
  "stm32f0xx-hal",
  "stm32f1xx-hal",
  "stm32f3xx-hal",
  "stm32f4xx-hal",
  "stm32f7xx-hal",
  "stm32f7xx-hal",
  "stm32h7xx-hal",
  "stm32l0xx-hal",
  "stm32l1xx-hal",
  "stm32l151-hal",
  "stm32l4xx-hal",
]

ti = [
  "tm4c123x-hal",
]

msp = [
  "msp430fr2x5x-hal",
]

xmc = [
  "xmc1100-hal",
  "xmc4-hal",
]

giga = [
  "gd32vf103xx-hal",
  "gd32vf103-hal",
]

newstag = "hal-implementation"
+++

<h2 id="os">OS {{ level(level=3) }}</h2>

{{ packages(packages='os') }}

<h2 id="microchip">Microchip {{ level(level=3) }}</h2>

{{ packages(packages='microchip') }}

<h2 id="nordic">Nordic {{ level(level=3) }}</h2>

{{ packages(packages='nordic') }}

<h2 id="nordic">NXP {{ level(level=3) }}</h2>
Also check the list of <a href="/topics/boards/#nxp">NXP board support crates</a>!

{{ packages(packages='nxp') }}

<h2 id="sifive">SiFive {{ level(level=3) }}</h2>

{{ packages(packages='sifive') }}

<h2 id="stm">STMicroelectronics {{ level(level=3) }}</h2>
Also check the list of <a href="/topics/boards/#stm">STMicroelectronics board support crates</a>!

{{ packages(packages='stm') }}

<h2 id="ti">Texas Instruments {{ level(level=3) }}</h2>

{{ packages(packages='ti') }}

<h2 id="msp">MSP430 {{ level(level=3) }}</h2>

{{ packages(packages='msp') }}

<h2 id="xmc">XMC {{ level(level=3) }}</h2>

{{ packages(packages='xmc') }}

<h2 id="giga">GigaDevice {{ level(level=3) }}</h2>

{{ packages(packages='giga') }}

