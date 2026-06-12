<div align="center">

# Tianchun Wu - Personal Homepage

### Personal academic homepage of Tianchun Wu | 武天淳

[Live Website](https://evan0610.github.io/) ·
[GitHub Profile](https://github.com/evan0610) ·
[LinkedIn](https://www.linkedin.com/in/tcwu/)

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-c2714f?style=flat-square)](https://evan0610.github.io/)
[![Stack](https://img.shields.io/badge/Stack-HTML%20%7C%20CSS%20%7C%20JavaScript-e28a67?style=flat-square)](https://github.com/evan0610/evan0610.github.io)
[![Focus](https://img.shields.io/badge/Focus-Medical%20Robotics%20%7C%20VLA-3d3929?style=flat-square)](https://evan0610.github.io/)

</div>

## About

This repository contains the source code for my personal academic homepage:

**Tianchun Wu | 武天淳**

I am an Electronic Engineering undergraduate in the ELITE Stream at The Chinese University of Hong Kong. My research focuses on:

- Vision-Language-Action models
- Medical robotics
- Robotic endoscopy
- Multimodal robot learning
- Embodied intelligence
- Computer vision
- Embedded robotic systems

The website presents my education, research experience, selected projects, professional experience, technical activities, skills, awards, and future publications.

## Live Website

The website is deployed through GitHub Pages:

```text
https://evan0610.github.io/
````

## Website Features

* Responsive academic homepage layout
* Desktop, tablet, and mobile support
* Light and dark theme switching
* Fixed profile sidebar on desktop
* Smooth navigation between sections
* Scroll-triggered section animations
* Education and experience timelines
* Research project descriptions
* Social links and downloadable CV
* Static deployment with no build process

## Main Sections

| Section      | Content                                                          |
| ------------ | ---------------------------------------------------------------- |
| About        | Research interests and technical background                      |
| Education    | CUHK Electronic Engineering and HIT–CUHK Winter School           |
| Research     | Research experience in robotic endoscopy and VLA systems         |
| Projects     | ColonVLA, EndoNav, EndoVLA-OOV / OpenHDS, continuum robot agents |
| Experience   | Smartphone R&D experience at TCL Technology                      |
| Leadership   | Chung Chi International Association and CUHK RoboMaster          |
| Skills       | AI model training, computer vision, robotics, embedded systems   |
| Publications | Future papers and manuscripts                                    |

## Selected Research Projects

### ColonVLA

A motor-based mixture-of-experts vision-language-action framework for autonomous colonoscopy withdrawal using a six-actuator robotic endoscope.

The project investigates:

* Latent action-mode decomposition
* Motor-space multimodal distributions
* Mixture-of-experts action prediction
* Clinical phase and anatomy conditioning
* Electromagnetic tracker-based withdrawal velocity estimation
* Phantom-based robotic validation

### EndoNav

A clinician-supervised autonomous endoscopic navigation system integrating:

* Vision-language models
* Autonomous robot control
* Human instruction interruption
* Instrument assignment
* Binary safety verification
* Endoscopic video and motor-state logging
* Anatomical phantom experiments

### EndoVLA-OOV / OpenHDS

A multimodal endoscopic data and training infrastructure project involving:

* Endoscopic video acquisition
* Motor-state synchronization
* Clinical phase and anatomy labels
* YOLO-assisted annotation
* Vision-language model fine-tuning
* Vision-language-action training pipelines

### Continuum Robot Agents for Fire Rescue

A continuum-robot agent concept for navigation and rescue assistance in structurally constrained building-fire environments.

## Technology Stack

### Front End

* HTML5
* CSS3
* Vanilla JavaScript
* Font Awesome
* Academicons
* Google Fonts

### Research and Engineering

* Python
* C
* C++
* PyTorch
* YOLO
* Vision-Language Models
* Vision-Language-Action Models
* Qwen-based model training
* GR00T-style action architectures
* ROS
* ROS 2
* STM32
* CAN communication
* Electromagnetic tracking
* Linux

## Repository Structure

```text
evan0610.github.io/
├── index.html
├── README.md
├── assets/
│   ├── css/
│   │   ├── font_sans_serif.css
│   │   └── theme-evan.css
│   ├── files/
│   │   └── Evan_Wu_CV.pdf
│   ├── img/
│   │   ├── avatar.jpg
│   │   ├── favicon.jpg
│   │   ├── institution.jpg
│   │   ├── HIT.jpg
│   │   ├── TCL.jpg
│   │   └── CCIA.jpg
│   └── js/
│       └── scale.fix.js
```

## Local Preview

No build tools or package installation are required.

Clone the repository:

```bash
git clone https://github.com/evan0610/evan0610.github.io.git
```

Enter the repository:

```bash
cd evan0610.github.io
```

Open `index.html` directly in a browser, or run a local server.

Using Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## GitHub Pages Deployment

This repository is configured as a GitHub user site.

The repository name must remain:

```text
evan0610.github.io
```

To deploy:

1. Open the repository on GitHub.
2. Go to `Settings`.
3. Open `Pages`.
4. Under `Build and deployment`, select `Deploy from a branch`.
5. Select the `main` branch.
6. Select `/ (root)`.
7. Save the settings.

After deployment, the website will be available at:

```text
https://evan0610.github.io/
```

## Updating the Website

### Update personal information

Edit:

```text
index.html
```

### Update the visual theme

Edit:

```text
assets/css/theme-evan.css
```

### Replace the profile image

Replace:

```text
assets/img/avatar.jpg
```

### Replace institution logos

Replace the corresponding JPG files in:

```text
assets/img/
```

### Update the CV

Replace:

```text
assets/files/Evan_Wu_CV.pdf
```

Make sure the filename matches the CV path used in `index.html`.

## Theme System

The website supports both light and dark modes.

The selected theme is stored in browser local storage. When no manual preference has been saved, the website follows the operating system theme.

Theme variables are defined in:

```text
assets/css/theme-evan.css
```

Main variables include:

```css
--evan-bg
--evan-text
--evan-accent
--evan-secondary
--evan-border
--evan-shadow
```

## Contact

* Email: `tianchunwu10@gmail.com`
* GitHub: [github.com/evan0610](https://github.com/evan0610)
* LinkedIn: [linkedin.com/in/tcwu](https://www.linkedin.com/in/tcwu/)
* Homepage: [evan0610.github.io](https://evan0610.github.io/)

## Copyright

Copyright © 2026 Tianchun Wu. All rights reserved.
