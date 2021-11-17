# Checkout Autoware.Auto and Apply Merge Request

## Overview

**The Merge Request [Prepare launch files for scenario_simulator](https://gitlab.com/autowarefoundation/autoware.auto/AutowareAuto/-/merge_requests/1267) is not merged into master, so we need to checkout Autoware.Auto and apply this MR for now.**

## Fork Autoware.Auto into your space

[Autoware Foundation / Autoware.Auto / AutowareAuto · GitLab](https://gitlab.com/autowarefoundation/autoware.auto/AutowareAuto)

1. Press `Fork`.
   ![Fork](images/checkout_autoware/fork1.png)

1. Select your namespace and choose Public from Visibility level.

   ![Fork project](images/checkout_autoware/fork2.png)

1. Get Autoware.Auto on you host, not on AVA platform.

   ```console
   git clone git@gitlab.com:foo/AutowareAuto.git
   ```

   :speech_balloon: `foo` is your username.

   For example

   ```console
   git clone git@gitlab.com:ito-san/AutowareAuto.git
   ```

1. Apply MR and commit

   ```console
   cd AutowareAuto
   git cherry-pick 92d57a77969592f656dab0fbc2a1c949ef140f0c
   git push origin master
   ```
