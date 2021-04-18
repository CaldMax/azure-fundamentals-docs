# Azure IoT services

# Azure IoT Hub
- central hub for bi-direction caommunication between IoT application and devices managed
- supports multiple message patterns
- can route received message to other Azure services
- allows command and control from cloud to device

## Azure IoT Central
- stands on top of an IoT hub adding a dashboard
- provides templates to manage devices and messages via UI
- can specify device templates that must be respected by device developers

## Azure Sphere
- end2end IoT solution to have high security from device hardware to message hub
- has 3 parts:
  - Azure Sphere micro controller unit (OS processing and sensors' signals)
  - customized Linux OS (can run vendor's software)
  - Azure Sphere Security Service (device security check)


