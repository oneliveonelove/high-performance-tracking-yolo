<div align="center">
  <h2>YOLO-based Real-time AI</h2>
  <p>
    <a href="https://github.com/ultralytics/assets/releases/tag/v8.2.0" target="_blank">
      <img width="100%" src="https://raw.githubusercontent.com/ultralytics/assets/main/yolov8/banner-yolov8.png" alt="YOLO Vision banner"></a>
  </p>
</div>


<img width="614" height="125" alt="Screenshot 2025-12-25 193733" src="https://github.com/user-attachments/assets/04acb954-35db-4495-88f4-8c8852eef664" />


This is the core code for a real-time AI vision project based on DXGI, TensorRT, and driver-level input.

---

### Core Ideas

1. **Screenshotting**: Low-latency image capture using DXGI Desktop Duplication.

2. **Inference**: Running an end-to-end YOLO model using the ONNX Runtime + TensorRT backend.

3. **Input**: Calling the `IbInputSimulator` library to simulate mouse movement via hardware drivers.

---

* The `.onnx` model in the repository is only an example. You need to train it yourself and replace it with your own model.

* **This project is for learning and technical exchange only.** It is strictly prohibited for any illegal use. All consequences are the sole responsibility of the user.

---

### **Dependencies & Credits**

This project is made possible by the following excellent open-source projects:

* **[IbInputSimulator](https://github.com/Chaoses-Ib/IbInputSimulator)** by Chaoses-Ib: Used to implement driver-level mouse input simulation, it is a crucial part of the entire project.

---

### **Running**

https://github.com/user-attachments/assets/da7c9cac-f699-4c3f-a5bf-7aaa32c2b172




