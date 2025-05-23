# Smart Orthopedic Cast

The Smart Orthopedic Cast is a wearable prototype designed to support and enhance the bone healing process using embedded electronics. This system addresses common challenges associated with traditional casts, such as discomfort from heat and sweat, by introducing smart features like temperature control, Near-Infrared (NIR) therapy, and Electrical Bone Stimulation (EBS). The goal is to create a cast that not only supports physical recovery but also improves overall patient comfort.

## Project Objective

This project aims to create a cast that:

- Regulates internal temperature to ensure comfort and prevent sweat accumulation.
- Promotes bone and tissue healing using NIR therapy.
- Stimulates bone regeneration through low-frequency Electrical Bone Stimulation.
- Lays the foundation for integrating infection detection and wireless health monitoring in future versions.

## Features

- **Temperature Monitoring and Cooling System**  
  A temperature sensor continuously monitors the internal conditions of the cast. If the temperature exceeds a preset threshold, a micro fan is automatically activated to cool the area and is turned off once a safe range is restored.

- **Near-Infrared Therapy (NIR)**  
  Integrated IR LEDs provide light-based therapy to promote cell repair and tissue healing.

- **Electrical Bone Stimulation (EBS)**  
  Low-intensity electrical pulses are applied through electrode pads to stimulate bone cell activity and accelerate healing.

- **OLED Display Interface**  
  Displays live temperature, humidity, and system activity to keep users informed of the internal environment.

## Components Used

- Arduino UNO R3  
- DHT11 or DHT22 temperature and humidity sensor  
- IR LEDs for NIR therapy  
- Transistors for circuit control  
- OLED Display (I2C interface)  
- Micro fan  
- LiPo battery  
- Electrodes for EBS  
- Additional components: jumper wires, breadboard or custom PCB

## Technologies and Tools

- Arduino IDE  
- Embedded C / Arduino C++  
- Real-time sensor integration  
- PWM and transistor-based control circuits  
- Power management systems

## Future Improvements

- Integration of biosensors to detect infections (e.g., pH or color-based sensors)  
- Wireless communication via Bluetooth or Wi-Fi for remote monitoring  
- Battery level indicator and low-power optimization  
- AI-based analytics for healing prediction and alerts

## How to Use

1. Connect all components according to the circuit diagram.  
2. Upload the code to the Arduino UNO using the Arduino IDE.  
3. Power the system using a LiPo battery.  
4. Monitor internal conditions on the OLED display.  
5. The NIR and EBS modules operate automatically or based on sensor thresholds and manual switches.

## About the Author

This project was developed by Sidharth.M.B and his team mates , 3rd year BTech students in Electronics and Communication Engineering at Rajagiri College of Engineering & Technology, Kochi. The Smart Orthopedic Cast is a part of an academic project focused on designing innovative healthcare solutions through embedded systems and IoT.

Email:sidharthbalakrishnan21@gmail.com
LinkedIn: linkedin.com/in/sidharth-m-b
GitHub: github.com/Sidharthbalakrishnan

