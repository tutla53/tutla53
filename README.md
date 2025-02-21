## Hi there 👋
- I am currently working on embedded project with Raspberry Pi Pico W RP2040, ESP32, and STM32 for hobby. 
- This is my personal journal to learn microcontroller mainly with Rust and Real Time Operating System (RTOS), and hopefully it can lead to the development of an intelligence mobile robot with SLAM.


![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
<img src ="https://user-images.githubusercontent.com/32474027/105848287-1c024f00-6022-11eb-8a6f-6bdae761b44d.jpg" height=28)>
<img src ="https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fbucketeer-e05bbc84-baa3-437e-9518-adb32be77984.s3.amazonaws.com%2Fpublic%2Fimages%2F8b0afbee-2dcd-4ab4-8cb9-659a0fabc755_359x198.png" height=28)>
<img src ="https://m.media-amazon.com/images/S/abs-image-upload-na/d/AmazonStores/A1F83G8C2ARO7P/4087e55f2f303ebc54d6fa96c58fe3cc.w980.h290._CR0%2C47%2C980%2C196_SX980_.jpg" height=28)>
<img src ="https://developer.espressif.com/img/espressif_logo_contour.png" height=28)>

### Software Configuration
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tutla53&layout=compact&theme=github_dark&hide=Makefile,CMake,RPC&size_weight=0.5&count_weight=0.75&&card_width=10&line_height=10&exclude_repo=stm32f103c8t6,toki-tlx-c-solution" align="right"/>

<table>
  <tr> 
    <th width=120> Board </th>
    <th >Language </th>  
    <th>HAL </th> 
    <th>RTOS </th> 
    <th>Template </th> 
  </tr>
  
  <tr>
    <td>Raspberry Pi Pico W </td>
    <td>Rust 🦀 </td>
    <td>embassy-rp </td>
    <td>embassy-rs </td>
    <td> <a href= https://github.com/tutla53/pico-server.git>pico-server</a> </td>
  </tr>  

  <tr>
    <td>ESP32-C3 Mini</td>
    <td>Rust 🦀 </td>
    <td>esp-hal </td>
    <td>embassy-rs </td>
    <td> <a href= https://github.com/tutla53/esp32c3-server.git>esp32c3-server</a> </td>
  </tr> 

  <tr>
    <td>STM32F1 Blue Pill</td>
    <td>C</td>
    <td>libopencm3</td>
    <td>FreeRTOS</td>
    <td> <a href= https://github.com/tutla53/stm32f1-c-template.git>stm32-c-template</a> </td>
  </tr> 
</table>

### Custom Embassy Library:
<table>
  <tr> 
    <th width=120> Board </th>
    <th> Library Item </th>  
    <th> Repository </th> 
  </tr>
  
  <tr> 
    <td> Raspberry Pi Pico W </td>
    <td>
      <ul>
        <li>rp2040-servo (PWM Driver)</li>
        <li>rp2040-servo-pio (PIO Driver)</li>
       </ul>  
    </td> 
    <td> <a href= https://github.com/tutla53/embassy-rp-library.git>embassy-rp-library</a> </td>
  </tr>
</table>

### Active Project:
<table>
  <tr> 
    <th> Project </th>
    <th width=120> Board </th> 
    <th> Description </th>
    <th> Repository </th> 
  </tr>
  
  <tr> 
    <td> Two DOF Camera Monitor </td> 
    <td> Raspberry Pi Pico </td>
    <td> Very simple 2 D.O.F camera monitor robot with two servo motors. This is my first project to use Rust + embassy-rs for microcontroller </td>
    <td> <a href="https://github.com/tutla53/camera-monitor-robot">camera-monitor-robot</a> </td>
  </tr>
  
  <tr> 
    <td> Bluetooth Remote Control </td>
    <td> STM32F1 Blue Pill </td> 
    <td> General purpose bluetooth remote control with HC-05 and STM32F1 Blue Pill with the example to control Camera Monitor Project </td>
    <td> <a href="https://github.com/tutla53/remote-control-stm32.git">remote-control-stm32</a> </td>
  </tr>
  
  <tr> 
    <td> TCP Communication </td>
    <td> ESP32-C3 & Raspberry Pi Pico W </td> 
    <td> Project to test TCP communication between ESP32-C3 and Raspberry Pi Pico W with embassy-net</td>
    <td> <a href="https://github.com/tutla53/tcp-comm.git">tcp-comm</a> </td>
  </tr>

  <tr> 
    <td> DC Motor Control</td>
    <td> Raspberry Pi Pico</td> 
    <td> Controlling DC Motor Speed and Position with Rotary Encoder and PID Control</td>
    <td> <a href="https://github.com/tutla53/dc-motor.git">dc-motor</a> </td>
  </tr>
</table>


