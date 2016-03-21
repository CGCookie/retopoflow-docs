---
layout: page
title: Getting Started
permalink: /getting-started/
---

# Basic Workflow

<img align='right' src='{{ site.baseurl }}/assets/img/rf_toolbar_object.png'>
To get started with RetopoFlow you need just one thing, an original object which you wish to retopologize into a new object. This original object is known as the **Source** object in RetopoFlow, while the new object you'll be creating is the **Target** object.  

The source object is typically a high-resolution mesh, such as a dynamic topology sculpt, but any mesh object will work.

With RetopoFlow activated, select the source object (your original mesh) in Object Mode and then activate one of the RetopoFlow tools from the **Retopology** tab of the **3D View Toolbar (T)**. Or press **CTRL+SHIFT+V** to call a menu.

Upon calling either *Contours*, *Polystrips*, or *Polypen* you will be placed into a modal operator (a session), during which you can use the tool to retopologize a portion or all of the source object. Once you're happy with the results press **Enter / Return** to generate the mesh, or **ESC** to cancel.


<img align='right' src='{{ site.baseurl }}/assets/img/rf_viewport_help.png'>
With all tools there is an onscreen help box for the active tool, giving you quick access to hotkeys, actions, and tips. Click to show the help, click again to hide it.

*Learn how to use each of the tools specifically on the [Tools page]({{ site.baseurl }}/tools).*

## Source Object
The object you wish to retopologize. All RetopoFlow tools use this object as the snap surface, such that all generated, or modified geometry, conforms to this original surface.

### Specifying a source object

There are three ways to specify the Source object:

 1. Click into field and choose object from dropdown
 2. Activate Eyedropper and click in the viewport onto the desired source object
 3. Leave field blank, select desired source object, activate any RetopoFlow tool. Source will be auto-detected.

## Target Object
If set this is the object you'll be adding new geometry data to. If left blank RetopoFlow will create a new object.

### Specifying a target object

There are three ways to specify the Target object:

 1. Click into field and choose object from dropdown
 2. Activate Eyedropper and click in the viewport onto the desired target object
 3. Leave Blank; activating any RetopoFlow tool while a Source is set, or while an object is selected, will auto-set the Target to a new object.
 - *Note: in Edit Mode the Target object is **always** the active object.*
