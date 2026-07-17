---
title: "ESP32-S3-BOX-3: From Requirements to Retail"
date: 2023-09-01
category: Consumer Electronics
summary: "An open-source AIoT development kit I take from idea to launch."
cover_image: /assets/images/projects/esp32-s3-box-3-cover.jpg
gallery:
  - /assets/images/projects/esp32-s3-box-3-1.jpg
  - /assets/images/projects/esp32-s3-box-3-2.jpg
  - /assets/images/projects/esp32-s3-box-3-3.jpg
tags: [ESP32-S3, Industrial Design, Mechanical Design, Tooling, Project Management, Product Management, AI, IoT]
---

## ESP32-S3-BOX-3

This was my first major product from end to end. I collected the product requirements, drafted the scope, and got approval from the project sponsor before later proposing the full user experience. Along the way I wore several hats — industrial designer, mechanical design engineer, and the person running tooling with our vendor and liaising with suppliers for parts — all on top of being the project manager coordinating with marketing, sales, developers, and electrical engineers.

The result was the **ESP32-S3-BOX-3**, a fully open-source AIoT development kit built around the ESP32-S3 SoC.

## What It's For

The ESP32-S3-BOX-3 is a compact, ready-to-use development kit aimed at makers, engineers, educators, and product teams who want to prototype voice-controlled and AI-enabled devices without building hardware from scratch. It ships with pre-built firmware supporting offline voice wake-up and speech recognition, and pairs with a companion app for customizing voice commands to control smart devices.

Out of the box, it runs demos across sensor monitoring, IR learning (letting the box act as a universal remote for air conditioners, fans, TVs, and projectors), and media playback — all through a 2.4-inch touchscreen with dual microphones and a speaker built in. It's designed to sit comfortably in smart home, smart agriculture, energy management, and industrial IoT applications, as much as it is a teaching tool for IoT prototyping.

<a class="video-thumbnail-link" href="https://www.youtube.com/watch?v=KGVOi1Mrjb0" target="_blank" rel="noopener">
  <img src="https://img.youtube.com/vi/KGVOi1Mrjb0/maxresdefault.jpg" alt="ESP32-S3-BOX-3 Promo — click to watch on YouTube">
  <span class="video-thumbnail-link__play"></span>
</a>

## What Went Into It — Especially the Accessories

The main unit was only part of the job. A big share of my time went into the accessory ecosystem that turns the box from a standalone device into a modular platform:

- **DOCK** — a stand that connects to the main unit through an edge connector, exposing two Pmod-compatible headers, a USB Type-A port for peripherals like cameras and USB drives, and a USB Type-C power input.
- **SENSOR** — a functional accessory integrating a temperature and humidity sensor, an IR emitter/receiver pair, a radar presence sensor, an 18650 rechargeable battery slot, and a microSD card slot.
- **BRACKET** — a mounting adapter that lets the box be attached to other devices, effectively turning non-smart hardware smart through its Pmod headers.
- **BREAD** — a breadboard adapter exposing the ESP32-S3's GPIOs through standard 2.54mm pitch pins, aimed squarely at makers who want to wire up their own circuits.

Getting these into production meant working through mechanical tolerances and enclosure design as the industrial and mechanical design engineer on the team, then carrying those designs through DFM reviews and tooling with our manufacturing vendor. On the supply side, I liaised directly with component suppliers to keep parts on schedule, while also coordinating with electrical engineers on the PCB and connector interfaces and with developers on the firmware support to achieve the desired user experience.

<a class="video-thumbnail-link" href="https://www.youtube.com/watch?v=4W3w93GQk7E" target="_blank" rel="noopener">
  <img src="https://img.youtube.com/vi/4W3w93GQk7E/maxresdefault.jpg" alt="ESP32-S3-BOX-3 Unboxing — click to watch on YouTube">
  <span class="video-thumbnail-link__play"></span>
</a>

## Takeaways

This project taught me how a consumer electronics product actually gets made — not just the mechanical design and tooling, but everything around it: scoping requirements early enough to get sponsor buy-in, shaping the user experience once the hardware direction was set, and holding together the thread between marketing, sales, developers, and electrical engineers so the product actually shipped as one coherent thing.

What I'm proudest of is that the development kit is still on the shelf today. It continues to support makers and developers building their own AI agent gateways, home assistants, and prototypes for whatever they're trying to invent next — which, at the end of the day, is exactly what it was designed to do.
