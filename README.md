# Main Project

Status: In development
Team: Documentation

# Sally: Wearable Device
<table border="0">
  <tr>
    <td width="50%" align="center">
      <img src="images/sally_logo.svg" width="50%" alt="Sally Logo">
    </td>
    <td width="50%" align="center">
      <img src="images/RiceStackedHoriz_Blue.png" width="50%" alt="Rice Logo">
    </td>
  </tr>
</table>

## 📝 Abstract

Information retention and the cognitive load of tracking professional interactions represent significant barriers to productivity. This paper introduces a necklace-form wearable assistant designed to streamline task management through intelligent conversation capture and context analysis. Utilizing a privacy-centric edge-computing architecture, the device transmits audio to a localized Raspberry Pi server for secure processing.
Advanced speech-to-text and small language models synthesize raw transcriptions into structured, context-aware summaries and personalized journals. A core contribution is the automated extraction of "action items" from natural dialogue, which the system uses to notify users and facilitate task execution via a mobile application. Technical evaluations demonstrate a 90\% transcription accuracy and optimized power management, achieving an 9.52-hour operational battery life. By automating the transition from verbal commitments to digital tasks, the system reduces the cognitive effort required for recall and interaction review, transforming ambient conversation into organized, actionable productivity insights.

### ⚙️ System Overview

- **Edge Architecture:** Utilizing a low-power hardware design, the device records and buffers ambient conversations, offloading data to a local **Raspberry Pi server** for intensive processing.
- **Intelligence:** Advanced **STT (Speech-to-Text)** and **NLP (Natural Language Processing)** algorithms synthesize transcriptions into concise, context-aware summaries and actionable items.

### 📊 Technical Benchmarks

| **Metric** | **Target / Performance** |
| --- | --- |
| **Transcription Accuracy** | 90% |
| **Summary Accuracy** | ≥ 90% |
| **Battery Life** | 8 Hours (via interrupt-driven power management) |
| **Sampling Rate** | 16kHz (Mono) |

### 📋 Project Structure

This repository contains several submodules that direct to another repository, which organized as follows:

```
wearable_closure --> **3D Printed design for the wearable device**
wearable_repo    --> **Source code for embedded part and its requirements**
sally_server     --> **Source code for set-up and running server**
sally_app        --> **Source code for developing mobile application**
```

## 👥 Project Team

- **Sugiarto Wibowo** ([sw183@rice.edu](mailto:sw183@rice.edu))* — *Lead Developer*
- **Jeeven Balasubramaniam** ([jb310@rice.edu](mailto:jb310@rice.edu))** — *Collaborator*

### 🎓 Supervision

- **Nakul Garg** ([ng83@rice.edu](mailto:ng83@rice.edu))* — *Project Supervisor*

**Affiliation:** *Rice University, Houston, Texas, USA*

> <small>* Electrical and Computer Engineering Department</small>
> 
> 
> <small>** Data Science Department</small>
>