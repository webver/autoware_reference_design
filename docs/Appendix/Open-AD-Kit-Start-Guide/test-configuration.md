# Test configuration for Open AD Kit 1.0

## Overview

This guide explains how to run Autoware.Auto by using multiple docker container with same docker image and how to test by using scenario simulator.

We need 2 computers to complete test execution;

- One is the __ARM-Based__ computer to run Autoware.Auto.

- The second is __Intel x64__ computer to run Rviz and scenario simulator.

## Test bed

The following describes test bed for Open AD Kit 1.0.

![Test bed](images/test-configuration/test-bed.png)

:speech_balloon: The docker image of Autoware.Auto is provided for `arm64`.

:speech_balloon: The docker image of scenario simulator is provided for `x86_64` so far.
