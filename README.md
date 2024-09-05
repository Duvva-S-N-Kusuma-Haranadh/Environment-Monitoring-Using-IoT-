# Environment Monitoring Using IoT

## Introduction
Environmental monitoring has become critical in assessing and mitigating the impacts of pollution and climate change. The integration of Artificial Intelligence of Things (AIoT) provides a robust solution for real-time environmental data acquisition and analysis. This project presents an advanced environmental monitoring system leveraging AIoT, utilizing gas sensors, humidity sensors, and the Raspberry Pi Pico microcontroller.

The proposed system is designed to measure various environmental parameters, including gas concentrations and humidity levels, providing real-time data that can be processed and analyzed to detect anomalies and predict trends. The Raspberry Pi Pico serves as the central processing unit, interfacing with gas sensors (e.g., MQ-135 for air quality monitoring) and humidity sensors (e.g., DHT22) through wired connections.

The AIoT-based environmental monitoring system offers a scalable and efficient approach to environmental data management, providing essential insights for policymakers, researchers, and the general public. The integration of AI enhances the system's capability to predict environmental trends and respond proactively to potential hazards, contributing to a healthier and more sustainable environment.

## Features
- Real-time monitoring of environmental parameters
- Gas concentration measurement using MQ-135 sensor
- Humidity level measurement using DHT22 sensor
- Data processing and anomaly detection using AI algorithms
- Trend prediction for proactive environmental management
- Scalable and efficient data management

## Components
- **Raspberry Pi Pico**: Central processing unit
- **MQ-135**: Gas sensor for air quality monitoring
- **DHT22**: Humidity sensor
- **Wired Connections**: For interfacing sensors with Raspberry Pi Pico

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Duvva-S-N-Kusuma-Haranadh/Environment-Monitoring-Using-IoT-.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Environment-Monitoring-Using-IoT-
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Connect the MQ-135 and DHT22 sensors to the Raspberry Pi Pico as per the wiring diagram provided in the `docs` folder.
2. Run the main script to start monitoring:
    ```bash
    python main.py
    ```
3. Access the real-time data and analysis through the web interface or console output.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements
- Special thanks to the contributors and the open-source community for their invaluable support.
- References to any libraries or tools used in the project.

## Contact
For any questions or suggestions, please open an issue or contact the project maintainer at [22761a1286@gmail.com].

