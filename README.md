# Homeassistant - Visualization for BWT soft water systems
Inspired by a screenshot from @deepandsteven in the HA community [Link](https://community.home-assistant.io/t/bwt-best-water-tech-nology-support/270745/119?page=2) I created a dashboard for my BWT Aqua Perla:

<img width="383" alt="image" src="https://github.com/Naboo2604/homeassistant/assets/13333609/99e88484-b306-4312-963b-49739a92ffbd">

## Prerequisites
- HACS BWT Integration from @dkarv [Link](https://github.com/dkarv/hacs-bwt-perla)
- Custom card from @amoebelabs: [Link](https://github.com/AmoebeLabs/flex-horseshoe-card)
## Installation
Follow the instruction from the prerequisite links and install the integration from @dkarv and from @amoebelabs.

This dashboard includes two cards - first one is the flex-horseshoe-card and the second the standard picture-element card.
In HA create a new dashboard and add the flex-horeseshoe-card - paste the content of the bwt-flex-card.yaml file and create a second picture-element card and paste the content of picture-element.yaml from the repo.

Thanks to @dkarv and @amoebelabs for their great work!
