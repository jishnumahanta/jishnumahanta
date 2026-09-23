# Jishnu Mahanta

**Full-stack and embedded engineer.** I build systems that span a web dashboard, a phone,
and a microcontroller — and I write the firmware at the bottom of that stack myself.

Guwahati, Assam · [jishnumahanta.in](https://jishnumahanta.in) · [LinkedIn](https://linkedin.com/in/jishnumahanta) · [X](https://x.com/jishnumahanta17)

---

### What I work on

**Edge AI and embedded systems.** ESP32 and ESP32-S3 firmware in C++ under FreeRTOS, with
TensorFlow Lite inference running on the microcontroller rather than in a cloud round-trip.
Quantising a model to int8 so it fits in 520KB of RAM is a different discipline to calling
an inference API, and it is the one I find most interesting.

**Full-stack web.** Next.js, TypeScript and React front to back, Python and Node services,
deployed on AWS. Motion-first work with GSAP when the brief calls for it.

**Android.** Kotlin and Jetpack Compose, with a bias toward offline-first architectures —
encrypted local storage, sync when the network decides to show up. Most software written for
Indian field conditions assumes the connection is the default and the outage is the exception.
In the Northeast it is the other way round.

**Applied security, at the edges of the above.** AES-GCM at rest, SHA-256 verification in a
firmware update path, and a CLI that catches secrets before they reach a repository.

---

### Selected work

**[GitReleaseOTA](https://github.com/jishnumahanta/GitReleaseOTA)** — `C++` · MIT · on the PlatformIO Registry

Over-the-air update infrastructure for ESP32. Firmware ships through GitHub Releases, so there
is no update server to run, and SHA-256 is verified before anything is written to flash — because
a device in a sealed enclosure that half-writes a corrupt image is recoverable by someone with a
ladder, not over the air. Non-blocking version check on a FreeRTOS task, proper semantic version
comparison, and a one-command release pipeline.

**[SecretGuard-CLI](https://github.com/jishnumahanta/SecretGuard-CLI)** — `JavaScript`

Developer-first tool that detects, fixes and prevents credential leaks in source code using
multi-layer detection. Built to catch secrets before the commit, not after the incident.

**[Medical AI Assistant](https://github.com/jishnumahanta/Medical_Ai_Assistant_Track2)** — `Vue` · MIT

Built for the Patient Journey Challenge, run by the PathCheck Foundation with HIE of One.
Placed 1st Runner-Up in the UI/UX track and 2nd in the AI track.

**Fyra** — `Next.js` · `Gemini API` · [live on my site](https://jishnumahanta.in)

Conversational assistant embedded in my portfolio that answers questions about my work and
captures enquiries.

---

### Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-3DDC84?style=flat-square&logo=freertos&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-FF7F00?style=flat-square&logo=platformio&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![TensorFlow Lite](https://img.shields.io/badge/TensorFlow%20Lite-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

---

Currently building a smart-home voice node with the wake word running on-device.

Open to freelance and contract work in IoT, edge AI and full-stack — reach me at
[jishnumahanta17@gmail.com](mailto:jishnumahanta17@gmail.com).
