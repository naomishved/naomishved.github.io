---
layout: archive
title: "Tools"
hide_title: true
permalink: /tools/
author_profile: true
---

TopoSlice
======

**3D reconstruction from low resolution, serial histological sections**

Take your fluorescence slide scanner images of slide-mounted tissue sections (uniform sectioning not required) and reconstruct them into volumes for visualization and analysis. Reconstruct and calculate the path, implant angle, and imaging field of view of surgically implanted microendoscopes (optional).

<div style="display:flex; flex-wrap:wrap; gap:16px; justify-content:center; align-items:stretch; margin:1em 0;">
  <figure style="flex:1 1 240px; max-width:340px; margin:0; text-align:center; display:flex; flex-direction:column; align-items:center; gap:6px;">
    <img src="/images/tools/dcai149_slide_before.jpg" alt="Before: a fluorescence slide scan of 15 mouse brain sections" style="width:100%; aspect-ratio:16/10; object-fit:contain; background:#000; border-radius:4px;" loading="lazy">
    <figcaption style="font-size:0.9em; font-family:inherit; text-align:center; width:100%;"><em>Before: the slide scan</em></figcaption>
  </figure>
  <figure style="flex:1 1 240px; max-width:340px; margin:0; text-align:center; display:flex; flex-direction:column; align-items:center; gap:6px;">
    <img src="/images/tools/dcai149_volume_after.png" alt="After: the same sections reconstructed as a 3D volume with the implant track" style="width:100%; aspect-ratio:16/10; object-fit:contain; background:#000; border-radius:4px;" loading="lazy">
    <figcaption style="font-size:0.9em; font-family:inherit; text-align:center; width:100%;"><em>After: the reconstructed volume</em></figcaption>
  </figure>
  <figure style="flex:1 1 240px; max-width:340px; margin:0; text-align:center; display:flex; flex-direction:column; align-items:center; gap:6px;">
    <img src="/images/tools/dcai149_volume_rotate.gif" alt="The reconstructed volume rotating" style="width:100%; aspect-ratio:16/10; object-fit:contain; background:#000; border-radius:4px;" loading="lazy">
    <figcaption style="font-size:0.9em; font-family:inherit; text-align:center; width:100%;"><em>The volume, rotating</em></figcaption>
  </figure>
</div>

**Status:** work in progress.
<!-- Re-enable when the repo is public: [GitHub repository](https://github.com/naomishved/TopoSlice) -->

ChairPile
======

Turn stream-of-consciousness written or spoken notes into chunkable project tasks. Organize complex multi-project to-do lists, plan out your day every morning, and visualize your niche "language" that expands the more you use ChairPile.

<p align="center">
  <img src="/images/tools/chairpile_language_map.png" width="460" alt="ChairPile's language map: clusters of the words and projects a user writes about, connected by how often they appear together" loading="lazy">
  <br><em style="font-size:0.9em;">The language map: your own words and projects, clustered by how you use them.</em>
</p>

<!-- Add when the repo is public: [GitHub repository](https://github.com/naomishved/ChairPile) -->

Songbird neuron migration analysis
======

**[Transgenic-songbird-neuron-migration](https://github.com/naomishved/Transgenic-songbird-neuron-migration)** (MATLAB)

The code behind [Shvedov et al. 2024, *Cell Reports*](https://doi.org/10.1016/j.celrep.2024.113759): visualizing tracked migratory neurons, measuring collective migration, characterizing superdiffusive movement, and simulating migration on biological timescales.

<p align="center">
  <img src="/images/3dTracks.png" width="360" alt="Tracked migratory neuron routes">
</p>
