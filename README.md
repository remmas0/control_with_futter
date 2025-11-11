# 🐢 Turtle Controller – Control with Flutter

A simple *Flutter-based* application to control a turtle robot.  
This project is *fully ready to connect with ROSBridge (ROS)* through WebSocket communication.  
It provides a basic control interface that allows sending movement commands to the robot — forward, backward, left, and right.

---

## 🚀 Project Overview
This project demonstrates how Flutter can be used to build a robot control interface.  
The app includes direction buttons that send motion commands through a WebSocket connection.  
It’s structured to integrate smoothly with *ROSBridge* once a ROS environment is available.

---

## 📂 Files Description
| File | Description |
|------|-------------|
| *main.dart* | Main Flutter code and WebSocket logic for sending movement commands. |
| *11.png* | Main layout image for the central controller interface. |
| *up.png* | Represents the *Forward* movement command. |
| *rh.png* | Represents the *Right* movement command. |

---

## 🧠 Features
- Flutter-based control panel for a turtle robot  
- Clean UI with direction buttons (Forward, Backward, Left, Right)  
- Uses WebSocket for message transmission  
- ✅ *Fully ready to connect with ROSBridge*  
- Works as a standalone demo even without ROS  

---

## 🛠 Technologies Used
- *Flutter SDK*
- *Dart*
- *web_socket_channel* package
- *ROSBridge* (optional, for full ROS integration)

---

## 📦 Dependencies
Add the following dependencies in your pubspec.yaml file:

```yaml
dependencies:
  flutter:
    sdk: flutter
  web_socket_channel: ^2.4.0
  cupertino_icons: ^1.0.8
