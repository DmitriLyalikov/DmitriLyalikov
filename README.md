<h1 align="center">Hi, I'm Dmitri Lyalikov</h1>

-------------------
&emsp;
<h3 align="left">Hi, I'm Dmitri Lyalikov, CTO and Cofounder at eXistential-AI. I am also a graduate student and researcher at NYU. My work is very interdisciplinary as I believe hard problems in engineering require solutions across the entire technology stack, and I find myself working on projects bridging between IC design, deep learning, signal processing, and embedded hardware and software design.   </h3>
&emsp;

-------------------
&emsp;

- 🔭 I’m currently working on [An Autonomous Search and Rescue Drone for Man Over-board Victims](https://github.com/riverdale-soc/uav-mobfinder). 
- 🌱 I’m currently learning **Nueromorphic Computing, Spiking Neural Networks, Multi-Modal Imaging, Chisel, and ArduPilot**
- 💬 Ask me about ** Neuromorpic Computing, Brain Machine Interfaces, RISC-V, Rust, Computer Vision, Embedded Systems, Deep Learning, and PCB Design**

&emsp;

# Featured Projects
  ## [Pico-Bridge](https://github.com/DmitriLyalikov/pico-bridge)
<!-- Title -->
<p align="center">
  <img width=15% src="https://www.svgrepo.com/show/68860/microchip.svg">
  <h1 align="center">pico-bridge</h1>
</p>

**The **pico-bridge** is a project that implements an embedded RPC for interface bridging utilizing the programmable I/O peripherals on the RP2040. 
The application for the RP2040 is based on the RTIC Real Time Interrupt-Driven Concurrency environment for Rust.**

## [VecBoost: A RVV 1.0 Library of Image Processing and Deep Learning operations to support RISC-V Domain Specific System-on-Chips](https://github.com/DmitriLyalikov/VecBoost)
Developed as part of sponsored research project to identify and optimize memory and computation bottlenecks in heterogeneous SoC architectures executing deep learning inference.
Using a Quad Core Rocket Chip with a loosely coupled Nvidia Deep Learning Acclerator running YOLOv3 on FireSim through Chipyard environment, it was found that approximately 50% of YOLOv3 execution time was spent on CPU operations as a fallback for functions and operators that the NVDLA/NVCC architecture did not support. 
Using a vector accelerator and mapping these operations (FD-to-NCHW, NHCW-to-FD, INT8-FP32, FP32-INT8, Image load, store, memcpy) to the now ratified RVV 1.0 specification, I present VecBoost, a stable library of vectorized implementations that support preprocessing and fallback operations for a variety of deep learning models and architectures demonstrating 1x-63x speedup compared to a single core scalar large Rocket implementation. 
* Feature Map to NCHW
* Leaky Activation
* Relu Activation
* Scaling
* Normalization
* Fill
* Gather
* Conversion
![image](https://github.com/DmitriLyalikov/DmitriLyalikov/assets/68623356/0939cac6-a4b6-45a8-ba66-198c56f50116)
![image](https://github.com/DmitriLyalikov/DmitriLyalikov/assets/68623356/026e6211-1e7d-47d4-a84f-dc1855b59aec)


## [Man OverBoard Wearable Submersion Module](https://github.com/riverdale-soc/submersion-module)

**A custom coin cell battery powered ESP32 based PCB with NEO-7M GPS module that detects submersion and propagates GPS coordinates over ESP-NOW protocol. 
Built using Altium, FreeRTOS, C, ESP-NOW and ESP-IDF**
![image](https://github.com/DmitriLyalikov/DmitriLyalikov/assets/68623356/0e5cd2af-3501-4acf-8db2-8a9c28c7c7ab)
## [Search and Rescue Drone for Man Overboard Victims](https://github.com/riverdale-soc/uav-mobfinder)
**Application for Jetson Nano Drone Controller to Navigate Ardupilot UAV to Man-OverBoard Victim using YOLOv7 inference on RGB and thermal camera streams. Use TensorRT to optimize inference time for CUDA GPUs.**
![image](https://github.com/DmitriLyalikov/DmitriLyalikov/assets/68623356/1b80b6ba-c577-4ffe-9f33-2b172b51a936)

![image](https://github.com/DmitriLyalikov/DmitriLyalikov/assets/68623356/7e5eb969-e9cd-426a-a432-699d0718009e)

## [Pendant Drop Tensiometry Image Processing Application](https://github.com/DmitriLyalikov/pdt-extract)
A python implementation and library for extraction of edge profiles and characteristic features from images of pendant drops suspended from a capillary. Given a raw image of a pendant drop, the profile is extracted through a series of steps: a canny edge detection sequence, reflective noise removal, and splitting the profile at its apex.

## [Pendant Drop Tensiometry XGBoost Application](https://github.com/DmitriLyalikov/pdt_regressor)
A collection of ensemble models that predict interfacial tension (beta) from the edge profile of a pendant drop.
![image](https://github.com/DmitriLyalikov/DmitriLyalikov/assets/68623356/73210e1f-74da-452f-81dc-01760465ae28)


### Artificial Model
pdt-regressor can currently predict Beta values given a drop profile feature set with an RMSE of .004. feature datasets are currently generated by solving ODE to solve for radii of the droplet across a range of Beta and Smax values.

### Image Model
This model is also tested on a real droplet image profiles where the feature data sets are extracted from the output of the pdt-canny-edge-detector.
profile data will be stored in the /data folder in .csv format.

## [7x24 Exchange Design Competition Project for 2-phase Immersion Cooling of Data Center CPUs](https://github.com/DmitriLyalikov/7x24-App)
This is the software application that is part of the 2022 design for Manhattan College in the 7x24 Senior Design Competition for processor cooling (heat dissipation) systems in the context of data centers. Traditional solutions to the problem of cooling involve heatsinks and fans. With the goal of increasing energy-efficiency and scalabilty, our design involved a two-phase immersive cooling system using a dielectric fluid with a much lower boiling point than water to significantly reduce heat dissipation costs.

ESP32 based control system that controls pump for heat exchange using PID controller. Logs energy consumption, temperature, and pump usage to Amazon AWS IoT dashboard over secure MQTT protocol. 

![image](https://github.com/DmitriLyalikov/DmitriLyalikov/assets/68623356/d436e835-ff11-4217-8906-5e8e068ef2e5)

## [ESP32 Smart Clock](https://github.com/DmitriLyalikov/ESP32_Smart_Clock)
This is my Embedded Systems Design Semester Project. I am using the ESP32 platform to make a LCD digital clock that displays local time synchronised from an NTP server and local/current weather forecasts from a JSON weather API endpoint over HTTP.
![image](https://github.com/DmitriLyalikov/DmitriLyalikov/assets/68623356/fa7db1a2-cf01-4534-8d31-35d58b6aa56f)



