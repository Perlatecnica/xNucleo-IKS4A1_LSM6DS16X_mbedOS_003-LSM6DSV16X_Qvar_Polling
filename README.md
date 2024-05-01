# xNucleo-IKS4A1_LSM6DSV16X_mbedOS_003-LSM6DSV16X_Qvar_Polling

This application shows how to use LSM6DSV16X Qvar features in polling mode.

---
### Description:

This code demonstrates the usage of the LSM6DSV16X sensor's Quaternion Variance (QVAR) feature with an mbed microcontroller. It continuously reads QVAR data from the sensor and prints it over a serial connection.

### How it works:

- **Initialization**: 
  - It includes necessary libraries for communication (`mbed.h`) and for interfacing with the LSM6DSV16X sensor (`plt_iks4a1.h`).
  - It initializes objects for serial communication (`Serial`) and an LED for visual indication.
  - It initializes an object for the LSM6DSV16X sensor.

- **Sensor Configuration**: 
  - It initializes the LSM6DSV16X sensor and enables both the accelerometer and gyroscope.
  - It enables the QVAR feature on the sensor.

- **Main Loop**:
  - It enters an infinite loop where it continuously checks if QVAR data is ready from the sensor.
  - If QVAR data is ready, it retrieves the data and prints it over the serial connection.

---

This description provides an overview of the code's functionality, including initialization, sensor configuration, and continuous reading and printing of QVAR data from the LSM6DSV16X sensor.