# Monitoring Sea Urchin Barrens with AI: A Robotics Engineer's Approach to Marine Conservation 🌊

As a robotics engineer at QUT's Marine Robotics lab, I'm passionate about developing tools to better understand and protect our marine environments. In my spare time, I've been exploring how AI can help address a growing ecological challenge: the spread of sea urchins and the devastation they cause to vital kelp forests.

**The Problem: Urchin Barrens and Kelp Forest Loss**

Climate change is warming Australia's southern waters, allowing sea urchin populations to thrive and expand into new regions like Southern NSW, Tasmania, and South Australia. Compounded by the overfishing of their natural predators, these urchins are grazing down vast kelp forests, creating "urchin barrens" – underwater deserts devoid of the rich biodiversity kelp once supported. This has significant implications for coastal ecosystems, fisheries, and marine biodiversity.

**An AI-Powered Solution: Automated Urchin Counting**

To help monitor the spread and density of these urchins, I've developed a custom object detection model using YOLOv11. The goal was to create a tool that can:

1.  **Detect and Count Sea Urchins:** Accurately identify urchins in underwater footage.
2.  **Track Urchins:** Implement tracking to avoid duplicate counts as they move or the camera pans.
3.  **Process Accessible Footage:** Be usable with readily available video from sources like GoPro cameras, as well as footage from our lab's AUVs (Autonomous Underwater Vehicles) and ASVs (Autonomous Surface Vehicles).

After training the model on a custom dataset, the initial results are promising (mAP50 for urchins around 0.889). The system can process video, overlaying detections and tracking trails, and provide a running count of unique urchins observed.

![kina_devastated_reef_cape_runaway_annotated_frame_004_vidframe_2038](https://github.com/user-attachments/assets/b7954e83-0172-48f0-bd02-35284846e5d3)
![Urchin Tracking Summary GIF](https://github.com/roboticsmick/ORCA_URCHIN_TRACKING/blob/main/assets/model_overview.gif)

**Why This Matters & The Bigger Picture**

Automated monitoring tools like this can be invaluable for:

*   **Scientists & Researchers:** Providing a more efficient way to collect quantitative data on urchin populations and the extent of barrens. This data is crucial for understanding the scale of the problem and the effectiveness of intervention strategies.
*   **Fishery Management:** Informing decisions about managing urchin fisheries (where they exist) or controlling populations in affected areas.
*   **Marine Park & Conservation Management:** Helping authorities monitor the health of protected areas, assess the impact of urchins on fish nurseries and other sensitive habitats, and prioritize conservation efforts.
*   **Highlighting Climate Change Impacts:** Demonstrating a tangible ecological consequence of warming waters, reinforcing the urgent need for climate action.

**Next Steps & Collaboration**

While this is a personal project, it showcases the potential for accessible AI tools to contribute to serious scientific and conservation work. I believe that by combining robotics (for data acquisition) with AI (for data analysis), we can significantly enhance our ability to monitor and manage our precious marine ecosystems.

I'm always keen to learn and collaborate. If you're working on similar challenges or see potential applications, feel free to reach out!
