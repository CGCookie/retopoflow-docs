---
layout: page-sidebar
title: Polypen
permalink: /tool/polypen/
tool: true
---

The Polypen is useful for those scenarios where you need absolute control on a vertex by vertex basis. It enables you to insert, extrude, and fill vertices, edges, and faces one at a time with precision and flexiblity.

It works to both create new geometry and to modify existing geometry.

Works in both Object Mode and Edit Mode.

## Basic Usage
After activating Polypen use CTRL+LMB to insert an initial vertex, CTRL+LMB a second time to extrude the vertex, then CTRL+LMB a third time to create a triangle. A forth click with create a quad. 

With each click Polypen with insert new geometry and select the newly created edge, enabling you to instantly add faces at will, exactly where you wish. 


## Controls

| Action | Hotkey |
| :------ | :------ |
| **Insert** | CTRL+LMB |
| **Select** | Selection mouse | 
| **(de)Select** | A |
| **Dissolve Edge** | CTRL+D |
| **Delete Seleciton** | X |
| **Commit Changes** | Enter |
| **Cancel Changes** | ESC |
| **Undo** | CTRL+Z | 
|

## Selection > Action Map
The result of each action click (CTRL+LMB) in Polypen is dependent on your selection and what you click onto. The table below illustrates what happens for each combination. The top row is your starting selection, while the left column is the element being clicked onto.

| Selection: | Nothing      | Vert                 | Edge       | Triangle     | Quad+  |
| : --- :    |
| **Src:**   | create vert  | extrude vert         | create tri | vert > edge  | ---    |
| **Vert:**  | select vert  | connect verts        | bridge     | vert to face | bridge |
| **Edge:**  | insert vert  | bridge               | bridge     | bridge       | bridge |
| **Face:**  | vert >  edge | connect vert >  edge | bridge     | bridge       | bridge |
|


## Use Cases
The best use cases for Polypen are those where you need complete control over the final geometry, including the distribution of triangles and quads. It's particularly good for game artists working on real-time assets, but it's also ideal for models with lots of detail and complex mesh flow, such as character faces.