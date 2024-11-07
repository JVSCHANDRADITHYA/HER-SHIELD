# HER-SHIELD
This project provides an AI-driven safety solution designed to enhance women’s security through real-time analysis of CCTV footage. By using advanced computer vision techniques, the system identifies potential risks and sends immediate alerts to authorities, facilitating rapid response.
Women Safety Analytics

This project provides an AI-driven safety solution designed to enhance women’s security through real-time analysis of CCTV footage. By using advanced computer vision techniques, the system identifies potential risks and sends immediate alerts to authorities, facilitating rapid response. Key features include:

    Gender Classification & Detection: Utilizing CSP-Darknet and RCNN for detecting and labeling individuals by gender in real-time.
    Risk Assessment: A location, time, and environmental factor-based risk scoring mechanism flags potentially dangerous situations, such as lone women in vulnerable settings.
    Behavioral Analysis: Vision Transformer models and OpenPose detect distress gestures or potential violence, triggering alerts to nearby authorities.
    Hotspot Identification: Uses historical and live data to identify high-risk zones, aiding in proactive safety measures.

The technical stack includes Python, PyTorch, CUDA-enabled GPUs, RCNN, Vision Transformers, and MediaPipe for robust and scalable performance. Designed for continuous monitoring, this solution aims to reduce crime rates and support law enforcement in safeguarding public spaces for women.
