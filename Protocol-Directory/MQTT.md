## MQTT

Main site		https://mqtt.org/					

Members		https://mqtt.org/mqtt-specification/		see  'TC Member Organizations' on this page			

Software, toolkits, services		https://mqtt.org/software/					

Certified products							

Use cases / Industries		https://mqtt.org/use-cases/					

MQTT Standard		https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=mqtt					

MQTT projects on GitHub. Find open source solutions here		https://www.google.com/search?q=site%3A+github.com+mqtt	https://re.public.polimi.it/bitstream/11311/1118563/1/main.pdf

## Brief

MQTT (Message Queuing Telemetry Transport) is a lightweight messaging protocol designed for IoT (Internet of Things) applications. It is based on the publish-subscribe model, where devices can publish messages to a broker, which then distributes the messages to all the subscribed devices. MQTT is designed to be lightweight, with a small code footprint, low bandwidth requirements, and minimal network overhead. It uses a binary message format, which is efficient for low-bandwidth networks, and allows devices to connect and disconnect easily, enabling efficient use of battery-powered devices. MQTT supports different levels of quality of service (QoS), ranging from QoS 0 (at most once delivery) to QoS 2 (exactly once delivery), allowing for trade-offs between reliability and network overhead. MQTT is widely used in IoT applications, where it enables efficient and reliable communication between different devices and systems. It is used in various IoT applications, including home automation, industrial automation, and smart cities.

## Use Cases

Home Automation: MQTT is used in home automation systems to enable communication between different smart home devices, such as thermostats, lighting, and security systems. MQTT allows for efficient control and monitoring of different home systems, improving comfort and security.

Industrial Automation: MQTT is used in industrial automation systems to enable communication between different industrial devices, such as sensors, actuators, and control systems. MQTT allows for real-time monitoring and control of industrial processes, leading to improved efficiency and productivity.

Asset Tracking: MQTT is used in asset tracking applications to enable real-time tracking and monitoring of assets, such as vehicles, equipment, and products. MQTT allows for efficient communication between different tracking devices, such as GPS trackers and sensors, enabling efficient asset management and optimization.

Smart Cities: MQTT is used in smart city applications to enable communication between different systems, such as traffic control, lighting, and waste management. MQTT allows for efficient control and monitoring of different city systems, leading to improved sustainability, safety, and quality of life.

Healthcare: MQTT is used in healthcare systems to enable communication between different medical devices and systems, such as patient monitoring, telemedicine, and healthcare analytics. MQTT allows for efficient exchange of data and information between different healthcare systems, leading to improved patient care and safety.

MEC: ENABLING IOT IN 5G NETWORKS

MQTT plays a significant role for various use cases like V2X etc between the 5G network infra and MEC facilities on the edge.

With evermore increasing data, Scale becomes the Key, Edge aggregations in 5G plays a very important role in the network optimizations, MQTT broker coupled with data pipelines can operate within the network infrastructure as a MEC solution for device data collection and aggregation at scale.

Multi-access Edge Computing (MEC) is identified as one of the key technologies required to support low latency for future services in 5G networks. The main idea is to bring computational power, storage resource and services typical of nowadays cloud infrastructures to the edge of the network, at
close proximity to the users. By doing this latency is greatly reduced, as well as the amount of traffic to be managed by the core network. MEC use case examples include computation offloading, distributed content delivery and caching, web performance enhancements and, of course, IoT applications.

IoT devices may be served with different types of connectivity (including
WiFi) from the 5G base stations, and communicate through IP and TCP or UDP with the MEC servers and with the Internet, where traditional cloud services are located

