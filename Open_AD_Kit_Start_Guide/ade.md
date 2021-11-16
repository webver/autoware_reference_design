# Setup ADE

## Overview

**In general, Autoware.Auto runs by using the Agile Development Environment (ADE), so we need to install ADE.**

1. Install ADE on AVA platform by following the instructions; [Installation — ADE 4.4.0dev documentation](https://ade-cli.readthedocs.io/en/latest/install.html)

   Download and setup ADE.

   ```console
   wget https://gitlab.com/ApexAI/ade-cli/-/jobs/1341322852/artifacts/raw/dist/ade+aarch64 -O ade
   chmod +x ade
   mv ade /usr/bin/
   ```

1. Setup ADE home directory by following the instructions; [Installation with ADE](https://autowarefoundation.gitlab.io/autoware.auto/AutowareAuto/installation-ade.html)

   ```console
   mkdir -p ~/adehome
   cd ~/adehome
   touch .adehome
   ```
