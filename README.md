# Open Stellarator Models

This repository contains simplified stellarator CAD models shared under a permissive usage license.

The CAD models contained within this repository are significantly simplified compared to the more detailed models created for internal analysis workflows.

The generic stellarator models provided may be of use to the stellarator and fusion energy communities. 

A potential use of these models is as a compuational benchmark for simulations codes such as [OpenMC](https://github.com/openmc-dev/openmc) and [DAGMC](https://github.com/svalinn/DAGMC).

- The scaled_w7x_stellarator.step CAD model is built around a scaled W7X plasma. The plasma has been scaled to power plant relevant sizes and the magnets have been shaped to allow space for a breeder blanket inbetween the magnet and firstwall. The radial build contains four uniform thickness layers representing the a gap between the plasma and firstwall (4cm), firstwall (2cm) breeder blanket (55cm) and vessel wall (4cm).

![scaled w7x](scaled_w7x_stellarator.png)