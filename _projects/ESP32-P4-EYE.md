---
title: "ESP32-P4-EYE: AI Vision Development, from Ground Up"
date: 2025-05-01
category: Consumer Electronics
summary: "From vision to reality, how an AI Vision Development Kit can inspire you to create."
cover_image: /assets/images/projects/esp32-p4-eye-cover.jpg
gallery:
  - /assets/images/projects/esp32-p4-eye-1.jpg
  - /assets/images/projects/esp32-p4-eye-2.jpg
  - /assets/images/projects/esp32-p4-eye-3.jpg
tags: [ESP32-P4, Industrial Design, Mechanical Design, Tooling, Project Management, Product Management, AI, IoT]
---

## Every Design Decision Matters: Building the ESP32-P4-EYE

The design of ESP32-P4-EYE is a story of balancing AI vision, engineering constraints, and thoughtful product design. Often, great products are usually the result of hundreds of small decisions. Decisions about people, trade-offs, costs, manufacturability, usability, and understanding what users are ultimately trying to achieve.

The ESP32-P4-EYE is no exception.

Serving as the Project Manager while contributing to the product management, industrial design, and mechanical design of the ESP32-P4-EYE was a particularly memorable experience for me. Not because it was the most complicated product I've worked on, but because it beautifully demonstrates how every design decision matters in hardware product development.

## Why a Camera?

When we first started designing the ESP32-P4-EYE, we knew we wanted to showcase everything that makes the ESP32-P4 special.

The ESP32-P4 is Espressif's first chip featuring both MIPI CSI and MIPI DSI interfaces alongside image rendering capabilities such as the Pixel Processing Accelerator (PPA) and 2D DMA. Naturally, AI vision and Human Machine Interface (HMI) applications became some of the most compelling use cases we wanted developers to explore.

The question then became: What should an AI vision development kit look like?

We could have designed another conventional development board, but we felt that would have significantly undersold what the ESP32-P4 was capable of. If we envisioned developers building smart cameras, AI-powered edge devices, and interactive applications, then perhaps the development kit itself should inspire those possibilities from the moment developers pick it up. The answer eventually became surprisingly simple.

A camera.

Inspired by the simplicity of a kid's camera, we wanted something approachable enough to sit comfortably on a developer's desk while remaining portable enough to be powered by a lithium-ion pouch battery. The stock firmware boots directly into a point-and-shoot photography experience, while underneath that simplicity lies a surprisingly capable platform for experimentation. Out-of-the-box, developers can explore offline image recognition using a YOLO-v11 model running on the device. Beyond that, they are free to flash their own applications and imagine entirely different use cases for the hardware.

Sometimes, good product design isn't about adding more features. It's about helping users immediately understand what a product could become.

## Why Not a Touchscreen?

One of the more interesting discussions we had early in development revolved around user interaction. Should we use buttons? A touchscreen? Or something else entirely? We eventually settled on a rotary encoder.

While touchscreens are incredibly intuitive, we realised many camera interactions such as scrolling through menus, zooming in and out, or tuning exposure are actually much more enjoyable with a rotary encoder than conventional buttons would allow. In terms of practicality, it is also more ergonomic and keep our fingers away from covering the precious display real estate, much needed for viewfinding.

This was simultaneously a functional decision, an industrial design decision, and a user experience decision.

My favourite products are often the ones where functionality and aesthetics complement one another so naturally that users don't consciously notice the design decisions being made.

The rotary encoder became one of those decisions for the ESP32-P4-EYE.

## Wrestling for Every Square Millimetre

One discussion that happened repeatedly throughout development was perhaps the most common problem in hardware product development - fighting for space. The electrical engineers wanted a larger PCB for easier routing and better engineering practices. I wanted to keep the overall dimensions closer to a typical development kit so that it remained approachable, portable, and comfortable to use. What followed were countless iterations of component placement, PCB layouts, and industrial design adjustments until we arrived at a compromise we were all happy with. I owe them their patience to work with me and understanding my perspective as well.

Packing both the ESP32-P4 SoC and ESP32-C6 connectivity module into such a compact device proved particularly challenging. Components needed to be placed intuitively for developers while simultaneously satisfying PCB routing constraints and manufacturing requirements.

Product development often looks glamorous from the outside. In reality, it usually looks more like negotiating for every square millimetre of PCB space.

That's perhaps one of my favourite things about this discipline. Good products are rarely the result of one brilliant idea. They're usually hundreds of thoughtful compromises made by multidisciplinary teams working towards the same goal.

## Small Details Matter

There are many design decisions within the ESP32-P4-EYE that developers may never consciously notice, but they each serve a purpose.

The small bump on the top of the enclosure wasn't simply designed for aesthetics. Inspired by the flash modules commonly seen on DSLR cameras, it provides an intuitive visual cue indicating which way the device should face while simultaneously giving us valuable PCB real estate for the microphone and flash module. More importantly, users are less likely to accidentally obstruct either component while holding the device.

Another subtle feature is the overmoulded 1/4" UNC tripod mount integrated directly into the enclosure. Combined with its onboard camera and AI capabilities, developers can quickly prototype smart cameras and edge AI applications with minimal additional hardware.

The remaining 20 GPIOs are exposed on the side of the development kit for expansion. Developers are free to connect additional sensors, speakers, motors, LED strips, or entirely new hardware modules limited only by their imagination.

None of these decisions were individually revolutionary. Together, however, they contribute significantly to how developers experience the product.

Thoughtful product design often lives within these small details.

## Designing for Curiosity

Consumer electronics are often designed defensively. Opening a product usually means voiding your warranty.

Development kits are the complete opposite. They should encourage curiosity.

We want developers to take them apart, understand how they're assembled, and perhaps even improve upon our ideas. That philosophy significantly influenced many of our manufacturing decisions throughout development.

By designing around off-the-shelf camera modules and LCD components, utilising a simple two-part injection moulded enclosure with minimal undercuts, and carefully planning our parting lines and snap-fit features, we were able to keep tooling costs low while maintaining ease of assembly and disassembly.

Manufacturability wasn't simply a cost consideration. It was equally a user experience consideration. A development kit shouldn't simply teach developers how to program hardware. It should also invite them to understand how hardware products are built.

## Final Reflections

From my experiences working on ESP32-P4-EYE from idea to launch, it solidify my belief that great products are started from a good idea, then built from a series of thoughtful decisions.

In product development, dehind every visible feature are countless conversations, compromises, redesigns, and lessons learnt along the way. From debating whether a touchscreen was necessary to negotiating for PCB space and balancing manufacturability with usability, every decision ultimately came back to one simple question:

Does this help the product become better for our customers?

Serving as the Project Manager while contributing to the product management, industrial design, and mechanical design of this project was both challenging and incredibly rewarding, and I'm excited to see how developers will continue pushing the boundaries of what the ESP32-P4 can achieve.

After all, good products don't happen by accident. They're designed intentionally.
