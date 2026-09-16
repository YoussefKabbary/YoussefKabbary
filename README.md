<img src="assets/banner.png" alt="Real-time Computer Vision: detection, tracking, crowd analytics, embedded AI" width="100%">

## Hi, I'm Youssef Kabbary

**AI & Computer Vision Engineer** · R&D Engineer at Smart Technology, Alexandria
B.Sc. Artificial Intelligence, Pharos University in Alexandria (2025)

I build computer vision systems that run in real time, and I measure them before I make claims about them.
When a number can't be backed by a test yet, the README says so.

<p>
  <a href="https://www.linkedin.com/in/youssef-kabbary"><img src="https://img.shields.io/badge/LinkedIn-youssef--kabbary-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:youssefkabbary1152003@gmail.com"><img src="https://img.shields.io/badge/Email-youssefkabbary1152003%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Open_to-AI_%2F_Computer_Vision_roles-2EA043?style=flat-square" alt="Open to AI and computer vision roles">
</p>

---

### 👥 [Crowd Master v2](https://github.com/YoussefKabbary/Crowd-Intelligence-System) — real-time crowd analytics

<table>
<tr>
<td width="46%"><a href="https://github.com/YoussefKabbary/Crowd-Intelligence-System"><img src="assets/crowd-master.gif" alt="Crowd Master: detection, gate counting, zones, heatmap, zoom and enhancement on real footage"></a></td>
<td>

People counting, doorway entry/exit counting, zone occupancy and anomaly clips for CCTV, webcams, IP/RTSP cameras and phones.

- An audited rebuild of my own v1: **28 documented defects** found and fixed
- **43–72 ms per frame** (v1: 95–232 ms) and **0.6 s** to the first useful frame (v1: 10.4 s), on a laptop RTX 3050
- YOLOv8 bodies fused with YOLOv8-pose head points, ByteTrack IDs, multi-threaded pipeline, REST API
- v1 and v2 recorded running side by side on the same video
- Detection accuracy on real footage is not benchmarked yet, and the repo says so

![Computer Vision](https://img.shields.io/badge/Computer_Vision-555?style=flat-square)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square)
![Tracking Systems](https://img.shields.io/badge/Tracking_Systems-555?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

</td>
</tr>
</table>

### 🛣️ [SafeRoute AI](https://github.com/YoussefKabbary/SafeRoute-AI) — road risk scoring API

<table>
<tr>
<td width="46%"><a href="https://github.com/YoussefKabbary/SafeRoute-AI"><img src="assets/saferoute.png" alt="SafeRoute AI dashboard"></a></td>
<td>

Scores how dangerous a road is, 0 to 1, in English and Arabic, from four independent signals:

- **Geometry** measured from OpenStreetMap + SRTM and scored with AASHTO formulas (reproduces AASHTO's own tables)
- **Transformer accident predictor** trained on 191,454 real FARS fatal crashes: **AUC 0.628** on 47 locations it never saw, beating logistic regression (0.606) and gradient boosting (0.624)
- **Sentinel-2 hazards**: flooding, sand and roadside canals, compared against the same road a year earlier
- **YOLOv8 pavement defects** from street-level photos

A model that cannot run contributes nothing instead of a fake 0.5, and every response names the models that actually ran.

![Transformer Models](https://img.shields.io/badge/Transformer_Models-555?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-555?style=flat-square)

</td>
</tr>
</table>

### 🏗️ Operations platform for a piling contractor — *confidential, no public code*

<table>
<tr>
<td width="46%"><img src="assets/ops-platform.png" alt="Production planning calculator, company name removed"></td>
<td>

An internal system I built end to end: **141 API routes** over **43 PostgreSQL tables**, **28 schema migrations** and **254 automated tests**.

Piling and concrete-pour records, a pile quantity and cost estimator, HR and attendance, global search and a full audit trail, behind an Arabic right-to-left interface built for use on site.

The tests are written around the risks: one account can never read another's rows, login hardening, request limits, a cold start on an empty database, and pinned estimator arithmetic.

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-555?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Software Development](https://img.shields.io/badge/Software_Development-555?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

</td>
</tr>
</table>

---

### 🧩 Earlier work

| Project | What it is | Tech |
|---|---|---|
| **AgliFly** | Graduation project, graded Excellent: autonomous surveillance drone with CNN object detection running on board a Raspberry Pi | Python · CNN · OpenCV · Raspberry Pi |
| **Smart Aquarium IoT** | Arduino Nano controller with temperature control, ammonia sensing, automated feeding and Bluetooth monitoring, with a Windows desktop app | Arduino · Bluetooth · Python |

### 🧠 Stack

**Computer vision & deep learning** <br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

**Backend & deployment** <br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA_%2F_FP16-76B900?style=flat-square&logo=nvidia&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Embedded** <br>
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)

**Languages** <br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
