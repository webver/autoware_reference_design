# Known limiations and issues

## Limitations

- Simulation by using LGSVL is not supported because map for scenario simulator(`kashiwanoha`) is not registered in LGSVL Simulator Content Store.

## Issues

- The ego vehicle drives slowly.

- `UC-001-0018-Kashiwa:1` failed with simulation timeout. The ego vehicle stucks after NPC crossed ahead of ego vehicle. This might be caused by the slow driving.
  ![Home Cyclone DDS](images/limitations-issues/scenario_a7effa60-c07d-4df4-b082-bc0d6cbae825_1.png)
