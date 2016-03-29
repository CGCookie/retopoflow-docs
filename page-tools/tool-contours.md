---
layout: page-sidebar
title: Contours
permalink: /tool/contours/
tool: true
---

The Contours tool is designed to enable you to quickly retopologize cylinderical forms. Contours works by draw strokes perpendicular to the source object, along the form, which then creates edgeloops that're snapped to the surface. Strokes can be draw one after the other to extrude from one stroke to the next, or they can be drawn on separate areas of the source object to create multiple pieaces.

Works in both Object Mode and Edit Mode. Contours can only create new geometry.

## Basic Usage
Contours is a simple tool; after specifying a source object simply activate Contours on your target object and click+drag with your LMB to draw strokes perpendicular to the form you're wishing to retopologize. The tool will automatically create a circle of evenly spaced verts around the form. Drawing another stroke adjacent to the first will bridge the two loops; as will a third, a forth, and so on. The Contours tool does its best to automatically determine which prior loop it should bridge the new loop to, enabling you to drawing quickly from any direction and in any order.

<img align='right' src='{{ site.baseurl }}/assets/img/rf_contours_strokes_01.gif'>

## Controls

| Action | Hotkey |
| :------ | :------ |
| **Draw stroke** | LMB |
| **Select loop** | Selection mouse |
| **Adjust segment count** | Shift + MouseWheel |
| **Slide loop** | G |
| **Rotate loop** | R |
| **Shift loop** | Left/Right arrow |
| **Delete loop** | X |
| **Toggle Guide mode** | TAB |
| **Generate mesh** | Enter |
| **Cancel** | ESC |

