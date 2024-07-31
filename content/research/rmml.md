---
title: "Research Intern"
description: "National Taiwan University, Taipei, Taiwan"
dateString: Mar 2024 - Jun 2024
draft: false
tags: ["Research", "Robotics", "Machine Learning"]
showToc: false
weight: 301
--- 

### Description
**Guide:** **Dr. Ping-Lang Yen** (Professor, Department of Biomechatronics Engineering, National Taiwan University)

I interned with the Robotics and Medical Mechatronics Laboratory in National Taiwan University through the Taiwan Education Exchange Program (TEEP) for a period of three months. In this time, I conducted a feasibility study to explore the potential of GPT-4 in robot-assisted surgical path planning. I leveraged GPT-4 and 3D Slicer to develop a tool that assists doctors in interactively planning multidimensional needle paths for tumor ablation.  This project involved not only the creation of the tool itself, but also the proposal of a novel workflow methodology for surgical path planning.  By integrating GPT-4 with prompt engineering and 3D Slicer for visualization, I developed a customized solution with the potential to significantly improve surgical efficiency.

&nbsp; 

![Certificate](/research/rmml/Certificate.png#center)


<Feasibility Study of Robot-Assisted Tumor Ablation Surgery using Generative AI>
&nbsp; 

<For the task of planning a path for needle insertion, GPT-4 acts as an assistant to the doctors. Initially, the doctors provide an entry point (the point for needle insertion) and a target point (the point the needle should reach on the surface of tumor) on a segmented image (with blood vessels, organs and tumor demarcated) as an input to GPT-4. We then generate six planes around the line of the original proposed path in 30° increments (through rotation), covering the entirety of the 3D space. For each of the resultant CT slices, GPT-4 checks for intersection of the proposed path with any “danger zone” (blood vessels or organs). GPT-4 can then tweak the original path (if need be) and also create additional alternate paths initiated from the vicinity of the originally selected entry point chosen by the doctor while avoiding intersection with any danger zones. The doctors are able to interact with GPT-4 by providing suggestions and feedback on the generated paths. According to the suggestions provided by the doctor, GPT-4 is able to modify its approach and generate a new path. GPT-4 is also able to rank these generated paths from “best” to “worst,” and also provide the distance of needle path from nearby danger zones. Once the doctor selects the most appropriate path, we input the transformed path coordinates into 3D Slicer for visualization.>

