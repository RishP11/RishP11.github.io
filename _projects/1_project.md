---
layout: page
title: DVB-S2x
description: An ISRO RESPOND Project
img: assets/img/dvbs2x.png
importance: 1
category: work
related_publications: false
---
[📄 Documentation](https://dvb.org/?standard=second-generation-framing-structure-channel-coding-and-modulation-systems-for-broadcasting-interactive-services-news-gathering-and-other-broadband-satellite-applications-part-2-dvb-s2-extensions)


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dvbs2x_transmitter.png" title="system_diag" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The prescribed architecture of the transmitter sub-system of DVB-S2x.
</div>
I contributed to the DVB-S2x project developed by the European Telecommunications Standards Institute (ETSI) for digital satellite television broadcasting. Successfully integrated a preliminary version of the transmitter subsystem, which showed promising results in simulations with MATLAB's "DVB-S2 waveform generator" tool.

I was responsible for designing and implementing key transmitter components on an FPGA using Verilog, including:
- Cyclic Redundancy Check (CRC) 8  
- BB Signalling and Slicer  
- Zero Padder  
- BB Scrambler  
- Bose-Chaudhuri-Hocquhem (BCH) Encoder  

I did this project during my third year (Aug 2023 to April 2024) at IIT Dharwad. The project was supervised by <a href="https://rajshekharvbhat.github.io/">Prof. Rajsekhar V. Bhat</a>, IIT Dharwad.