# Homeassistant - Visualization for BWT soft water systems
Inspired by a screenshot from @deepandsteven in the HA community [Link](https://community.home-assistant.io/t/bwt-best-water-tech-nology-support/270745/119?page=2) I created a dashboard for my BWT Aqua Perla:

<img width="383" alt="image" src="https://github.com/Naboo2604/homeassistant/assets/13333609/99e88484-b306-4312-963b-49739a92ffbd">

## Prerequisites
- HACS BWT Integration from @dkarv [Link](https://github.com/dkarv/hacs-bwt-perla)
- Custom card from @amoebelabs: [Link](https://github.com/AmoebeLabs/flex-horseshoe-card)
## Installation
- Follow the instruction from the prerequisite links and install the integration from @dkarv and the custom card from @amoebelabs.
- Copy the picture file (background) from the repo on a public available web-server (if you want to use HA GUI from everywhere) or on a local path (if you want to use it only internally).
- Edit the picture-element.yaml and paste the link to your background png file in the last line.
- Create a new dashboard in HA and add a flex-horseshoe-card, paste the content of flex-horseshoe.yaml file
- Add a second picture-element-card and paste the content of picture-element.yaml file


Thanks to @dkarv and @amoebelabs for their great work!
