Hi, I'm Sathvik
I'm an 11th grader in San Jose, CA. I build things at the intersection of mechanical engineering and software — mostly robotics, embedded systems, and lately, using LLMs to control CAD tools with your voice.

I got into engineering through FRC robotics and haven't really stopped building since.


Projects
voice-to-cad — My main project right now. A fully local pipeline that lets you speak and have parts built in Onshape in real time. You talk, Whisper transcribes it, Llama 3.1 interprets the intent, and the Onshape REST API builds the geometry. No cloud, no API costs after setup. Fine-tuned on ~5,600 synthetic FRC CAD examples using Unsloth + LoRA on an RTX 3060. Has a self-correction loop so it retries when the API throws errors.

env-monitor — Arduino sensor station logging temperature, humidity, and air quality. Python script reads serial output, saves to CSV, plots trends with Matplotlib. Built it to see how ventilation actually affects indoor air quality.

gripper-v1 — 3D-printed underactuated robotic gripper. Three fingers, one servo each, fishing line tendons. Designed in Fusion 360, printed at the local makerspace, went through three design revisions before it could hold a water bottle reliably.

smart-rover — Autonomous obstacle-avoiding rover. Ultrasonic sensing, H-bridge motor control, Bluetooth app interface. Capstone project, in progress.


Stack I use
Python, C/C++ (Arduino), Fusion 360, TinkerCAD, faster-whisper, Ollama, Onshape API, Git, Matplotlib, KiCad (learning)


Currently
Finishing the fine-tuning pipeline for voice-to-cad
Working toward CSWA SolidWorks certification
Looking for a mentorship or hands-on project with an engineering team in the South Bay this summer

Based in Evergreen, San Jose. Open to unpaid work, shadowing, or colloborating on projects.

rajolisathvik@gmail.com

