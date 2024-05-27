# Projects

Robotics involves various disciplines, including mechanical engineering, electronics, software development, and theoretical knowledge. Building projects is the best way to deepen your understanding. This section is divided into projects designed to make it easy for you to get started in robotics.

# Low Cost Projects

### [Low Cost Robot](https://github.com/AlexanderKoch-Koch/low_cost_robot)

The low-cost robot arm adapts the ACT model, making it easy to set up and use.

### [UMI Gripper](https://umi-gripper.github.io/)

A data collection policy and framework that easily enables the transfer of skills from real world human interaction to robot manipulation.


# Single Board Computers (SBCs)

## [Raspberry Pi](https://www.amazon.com/Raspberry-Pi-Quad-core-Cortex-A76-Processor/dp/B0CTQ3BQLS/ref=sr_1_2_sspa?crid=1UFOSCMJMYBQM&dib=eyJ2IjoiMSJ9.tbZ0EMR289jYGuOEXI8_Rh7ZFivo67gudYLC4ENELtvWaic-gE_ceTOLyl__9r0Olv89eUoqlc4KbQIboEtVYatlThzGexyqlfEDNuzae9WHedzPpH3oTADxY2DMXBsqUvtu7jMO4oSq-bYm3R5cRXDGGnPwJknUQ_IUwug1UthwMevAhQzVhERAIuFhfXG5_9WN6bsEZdTpm6enhpZRTdLbId_-8TCiTG3yz5WJZeHP2tj8ci46qGQJtlXymPp0V-MMbff5I0JQ3g1o51uaADEXO2tmrtFdSnxR3l4mF2c.7eAQpYtWXQE4PEnbtdBXpFuIADtu0KQkGfK0KNWkg-o&dib_tag=se&keywords=raspberry+pi+5&qid=1716497131&s=electronics&sprefix=raspberr%2Celectronics%2C170&sr=1-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1)

**Parts Not Included:**

- HDMI Cable
- Micro SD Card
- Power Supply

## Setup:

### 1. Download the Raspberry Pi Imager:

- Visit the [Raspberry Pi website](https://www.raspberrypi.org/software/) and download the Raspberry Pi Imager for your operating system (Windows, macOS, or Linux).
- Install the Raspberry Pi Imager on your computer.

### 2. Prepare the Micro SD Card:

- Insert the Micro SD Card into your computer.
- Open the Raspberry Pi Imager.
- Choose the operating system you want to install (e.g., Raspberry Pi OS).
- Select the Micro SD Card as the storage device.
- Click "Write" to flash the operating system onto the Micro SD Card.
- Once flashing is complete, safely eject the Micro SD Card from your computer.

### 3. Set Up the Hardware:

- Insert the flashed Micro SD Card into the appropriate slot on your Raspberry Pi.
- Connect the HDMI Cable from the Raspberry Pi to your monitor.
- Connect a USB keyboard and mouse to the Raspberry Pi.
- Plug in the power supply to the Raspberry Pi.

### 4. Initial Boot:

- Power on the Raspberry Pi by connecting it to a power source.
- Wait for the initial boot process to complete, which may take several minutes.
- Follow the on-screen prompts to complete the initial setup, including setting up Wi-Fi, username, and password.

### 5. Update and Upgrade:

- Open a terminal window on the Raspberry Pi.
- Run the following commands to update and upgrade the system packages:
  ```sh
  sudo apt-get update
  sudo apt-get upgrade
  ```

## [Nvidia Jetson](https://www.amazon.com/dp/B0BZJTQ5YP?nvid=em-945-13766-0005-000&th=1)

**Parts Not Included:**

- Display Port Cable
- Micro SD Card

## Setup:

### 1. Flash Linux onto your Jetson:

- Visit the [JetPack SDK page](https://developer.nvidia.com/embedded/jetpack) and download the latest version of JetPack.
- Follow the installation directions provided on the page.
- If you encounter issues with Linux booting, install and run [JetPack 5.1.3](https://developer.nvidia.com/embedded/jetpack-archive).

### 2. Prepare the Micro SD Card:

- Insert the Micro SD Card into your computer.
- Use an imaging tool (e.g., Etcher, Rufus) to flash the downloaded JetPack image onto the Micro SD Card.
- Once flashing is complete, safely eject the Micro SD Card from your computer.

### 3. Set Up the Hardware:

- Insert the flashed Micro SD Card into the appropriate slot on your Jetson device.
- Connect the Display Port Cable from the Jetson to your monitor.
- Connect a USB keyboard and mouse to the Jetson.
- Plug in the power supply to the Jetson.

### 4. Initial Boot:

- Power on the Jetson by connecting it to a power source.
- Wait for the initial boot process to complete, which may take several minutes.
- Follow the on-screen prompts to complete the initial setup, including setting up Wi-Fi, username, and password.

### 5. Update and Upgrade:

- Open a terminal window on the Jetson.
- Run the following commands to update and upgrade the system packages:
  ```sh
  sudo apt-get update
  sudo apt-get upgrade
  ```
