# :wave: Hi, I'm Arnav!

I'm a **Computer Engineering** student at NJIT with a minor in **Data Analytics** (Class of Dec 2026). I'm passionate about the intersection of high-speed digital hardware design and low-level firmware development. When I'm not routing differential pairs, I'm usually simplifying life with a new sub-routine or micro-optimizing memory accesses for a loop in a microcontroller.

-----

## What I'm working on

- [**High-Speed PCB Design**][02]: Architected a 6-layer board for the **STM32N657I0H3Q** microcontroller. It boasts a 512Mb external XSPI Flash memory, 128Mb SDRAM via the FMC interface, MIPI CSI, and a plethora of other peripherals (4 UARTs, 2 SPIs, 2 I2Cs, Timers, etc.)
    - Originally intended for use on the [SolarVision Mower][01], but we ultimately didn't have time to get all the code functioning.
    - Currently working on unit tests for all supported peripherals.

## Past Projects

- [**BitSum Lecture Summarizer**][03]: A completely local, docker based AI stack which takes input of audio/video lectures, and transcribes and summarizes them. Uses OpenAI Whisper for transcription, and Microsoft BitNet for efficient CPU-based summaries.
- [**USB Logic Analyzer**][06]: A custom USB logic analyzer, built around an **STM32F446** microcontroller. Features UART, SPI, I2C, and CAN signal decoding, as well as waveform plotting, using Python and Go.
- **SessionSummary Email Generator**: Created a fully custom email generator for the Mathnasium of Chatham + 4 other centers. Utilizes Javascript and Node.js, and custom (effectively reverse-BNF grammar) email generation algorithm to generate 110-150 emails per day.
- [**The SolarVision Mower**][01]: An autonomous, solar-powered lawnmower utilizing YOLOv8 Segmentation, LiDAR, and Ultra Wideband Positioning for intelligent navigation and obstacle avoidance. Utilizing an STM32, ESP32, FreeRTOS for concurrent tasks, and custom firmware for both.

-----

## Technical Toolkit

| Category                     | Tools & Languages |
|:-----------------------------|:------------------|
| **Languages:**               | C, C++, MATLAB, Java, Python, Go, SQL (MySQL), GNU Octave, Latex, Javascript, VHDL |
| **Software Tools:**          | Linux (Debian), KiCAD, FreeCAD, STM32CubeMX & IDE, PlatformIO, ESP-IDF, Git, Docker, Excel |
| **Build Tools/Debuggers:**   | Apache Maven, Apache Ant, CMake, Make, MSVC & GCC, GDB, Valgrind |
| **Libraries:**               | STM32 HAL, FreeRTOS, NumPy, PyTorch, Scikit Learn, Matplotlib, Gnuplot |
| **Communication Protocols:** | UART, I2C, SPI, CAN, USB 2.0, TCP and Socket Programming in C/C++ and Go |

-----

## Resume

Find my resume [here!][05]

-----

## Connect with Me

- **LinkedIn:** <https://www.linkedin.com/in/avr33>
- **Website:** <https://avr34.github.io/>

<!-- Links -->

[01]: https://github.com/SolarVisionMower/SolarVision
[02]: https://github.com/SolarVisionMower/SolarVision/blob/dev/PCBDesign/Hardware/STM32N6_Board/schematic.pdf
[03]: https://github.com/avr34/ECE381-Final
[04]: https://github.com/avr34/NeuralNet
[05]: https://github.com/avr34/Resume/blob/main/Resume.pdf
[06]: https://github.com/ragusauce4357/ECE692-Final-Project
