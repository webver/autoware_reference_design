# Open AD Kit Start Guide

## Overview

A new era of automotive development has been emerging: SDV. SDV was first used to stand for Self Driving Vehichles. The Autoware Foundation was founded to encourage collaboration among academia and industry to build the new generation of SDV. With more and more software expertise contributing, a new picture of SDV, the Software Defined Vehicle, is emerging, and Arm, Autoware and AutoCore are leading the way:
- https://www.arm.com/blogs/blueprint/software-defined-vehicle
- https://www.autoware.org
- https://github.com/autocore-ai/SDV

As mentioned in Arm's blueprint, once the system architecture is defined, the software will progress very quickly, and we will also need future-proof hardware built for automotive to enable the software developers to get started very quickly. Thus was born the Open AD Kit to achieve just that.

This instruction explains how to build development platform for Open AD Kit and run Autoware.Auto on Open AD kit.

## HPC for Open AD Kit is available for purchase

ADLINK provides High Performance Computer(HPC) for Open AD Kit in their website.

- [SOAFEE for Software Defined Vehicles | ADLINK](https://www.adlinktech.com/en/soafee)

Please feel free to contact ADLINK customer support.

- [AVA Developer Platform](https://www.ipi.wiki/pages/com-hpc-altra) is used in this instruction.

## PCU for Open AD Kit is available for purchase

PCU is an automotive grade reference design board designed by AutoCore, introduction of PCU is available on github. 

- [AutoCore PCU Specification](https://github.com/autocore-ai/autocore_pcu_doc/blob/master/docs/Pcu_specification.md)

Please feel free to contact AutoCore customer support.

- Email: contact@autocore.ai

## Table of contents

### AVA Platform
1. [Test Configuration](test-configuration.md)
1. [Getting started with EWAOL](getting-started.md)
1. [Boot EWAOL via SSD Boot](boot-ewaol.md)
1. [Extend rootfs partition](extend-rootfs.md)
1. [System Setup on AVA platform](system-setup-ava.md)
1. [System Setup on your host](system-setup-host.md)
1. [Run Autoware.Auto and scenario simulator](run-autoware.md)
1. [Cloud native CI/CD - Web.Auto](cloud-native-cicd-webauto.md)
1. [Known limitations and issues](limitations-issues.md)

### PCU Platform
1. [Test Configuration](test-configuration-pcu.md)
1. [Getting started with PCU](getting-started-pcu.md)
1. [System Setup on PCU](system-setup-pcu.md)
1. [System Setup on your host](system-setup-host.md)
1. [Run Autoware.Auto and scenario simulator](run-autoware.md)
1. [Cloud native CI/CD - Web.Auto](cloud-native-cicd-webauto.md)
1. [Known limitations and issues](limitations-issues.md)
