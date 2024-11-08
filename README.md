# Smart Sericulture System
![WhatsApp Image 2024-11-08 at 06 18 30_cca64df8](https://github.com/user-attachments/assets/1242cc2c-ea76-4199-b7c5-8a73fc710d83)
<p align = "justify" >Traditional sericulture, a millennia-old practice of silk production, grapples with significant challenges. Disease outbreaks, pest infestations, and suboptimal environmental control threaten silkworm health, reduce silk yield, and jeopardize the livelihoods of artisans. The proposed groundbreaking innovation that seamlessly integrates cutting-edge technology with traditional sericulture practices. The system harnesses the power of webcams, NodeMCU microcontrollers, sensor modules, and advanced machine learning algorithms to create a comprehensive solution for silkworm health monitoring and protection. Webcams, coupled with the YOLOv8 object detection model, enable real-time identification of foreign objects and silkworms, while NodeMCU facilitates sensor data transmission and bidirectional communication, ensuring a seamless flow of information. Sensor modules, including DHT-11 for temperature and humidity, MQ 135 for air quality, and an ESP-32 camera, provide comprehensive environmental monitoring. The React - Native framework builds an intuitive user interface, empowering users to visualize data and fine-tune model parameters, making the system accessible to both technical and non-technical stakeholders. This integrated approach holds immense potential to revolutionize silkworm rearing, safeguard silkworm health, and enhance the overall productivity and sustainability of the sericulture industry. </p>

# Tech Stacks Used:

 1. React native ( App )
 2. YoloV8 Model ( Object Detection )
 3. Flask ( Backend )
 4. Mistral AI ( Zhagaram GPT )
 5. ESP32 Board ( Hardware Part )

# Working
![image](https://github.com/user-attachments/assets/981f8359-7445-4175-9343-86a87af04395) ![image](https://github.com/user-attachments/assets/27dc2fb7-2c90-4ea5-893c-4b0543f93da7) ![image](https://github.com/user-attachments/assets/01f7f0d7-d5fa-45bf-9f41-88f94d3aee60)

<p align="justify"> The overall set up of the room comprises of the racks installed inside a room, each rack with 6 to 7 slabs. These all slabs are the places for the growth of the silkworms where they used to move one above the other. These racks are installed into the farm with a specific gaps between each other. This is the place where mulberry leaves, to which the silkworms feed upon is also provided. The pest detection is made by installing cameras into the farm. These cameras are efficient enough to detect the foreign objects such as lizards, cockroaches, squirrels etc. The installed cameras are the IP cameras where they are fixed on the four corners of the room. These IP cameras detect the foreign objects and gives a amber alert to the farmer. These amber noise automatically gets the foreign object away from the specified place. The notification is also given to the farmer for further inspection of the foreign object. The disease detection is made by installing cameras into the farm. These cameras are set up on the top of each racks, hence whether the silkworm is affected by any disease/unhealthy silkworm or it is unaffected/healthy silkworm is notified to the farmer. As we know, the silkworm diseases are communicable ( easily spreads from one silkworm to another silkworm), therefore, it is the foremost duty of the farmers to separate the unhealthy silkworms from the rack and isolate them as soon as possible. So, the racks are installed with IP cameras for the detection process to take place effectively. </p>

#

# HARDWARE - OVERALL INTEGRATION OF HARDWARE
![WhatsApp Image 2024-11-08 at 08 04 38_d6909968](https://github.com/user-attachments/assets/7b06242f-29be-4e04-a221-dcf5ada527a7 = 400x400)

<p align="justify">The hardware system includes ESP32, temperature and humidity sensors (DHT-11), air quality sensors (MQ-135), and IP cameras. These components communicate with the server via IoT protocols, ensuring seamless data flow for monitoring temperature, humidity, and pest detection. The system integrates with the Node MCU, which triggers amber alerts and notifies the farmer through the app when pests are detected. Solar panels provide an alternative energy source, enhancing eco-friendliness.</p>

# SOFTWARE APP
![image](https://github.com/user-attachments/assets/0e54e5bd-738b-490b-93ed-69e927ed0b62)

<p align="justify">The software architecture is built using Flask, YOLOv8, and React Native. The Flask framework handles back-end processes, managing communication between the hardware and software components. YOLOv8 provides object detection for pests and disease detection using ML models, while React Native ensures a smooth, cross-platform user interface for mobile applications, allowing farmers to monitor their sericulture environments in real time.</p>
 
# ZHAGARAM GPT 
![image](https://github.com/user-attachments/assets/6a113d6c-900f-4a92-bc44-868ec4080ebc)

<p align="justify">Zhagaram GPT integrates generative AI models such as Mistral AI, together with APIs and Hugging Face, for enhanced decision-making in sericulture processes. This GPT system provides intelligent insights and predictions on pest management, disease prevention, and yield improvement based on historical data, helping farmers take proactive steps to improve sericulture practices.</p>

# MAP COMMUNITY INTEGRATION
![image](https://github.com/user-attachments/assets/d4462720-3ba0-446e-a6a5-1b1641d659d0)

<p align="justify">A map-based community platform allows sericulture farmers to connect and trade. The map shows locations where they can sell eggs or cocoons, and also find suppliers for their needs. This integration fosters a collaborative environment, allowing farmers to exchange resources, thereby enhancing the efficiency of the sericulture process. The map is dynamically updated based on community input.</p>

