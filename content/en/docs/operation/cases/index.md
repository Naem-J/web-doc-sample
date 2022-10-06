---
title: "Cases"
description: "A description of features for navigating and using the system or cart during surgical operation or surgery, including recording the session or ending it."
lead: ""
date: 2022-10-04T08:48:57+00:00
lastmod: 2022-10-04T08:48:57+00:00
draft: false
images: []
menu:
  docs:
    parent: "operation"
weight: 3400
toc: true
---

## Live Cases

In the Home panel, click **Start Case**.

{{< panel status="warning" title="WARNING" >}}Do not connect or disconnect any displays to the system during live surgery. Visualization is interrupted while the system reinitializes the display.{{< /panel >}}

### Procedure Screen Layout

![Procedure Screen Features](sw_procedure_screen_overview.svg)

{{< callout num="1" term="Case timer" desc="Displays the duration of the surgical case." >}}  
{{< callout num="2" term="Record video button" desc="Starts and stops recording video of the screen. A red dot appears next to the case when a case is being recorded." >}}  
{{< callout num="3" term="Snapshot button" desc="Takes a picture of the screen." >}}  
{{< callout num="4" term="Information panel" desc="Displays basic information to identify the current patient and case." >}}  
{{< callout num="5" term="Quick Access Bar" desc="Includes buttons to quickly change various display settings." >}}  
{{< callout num="6" term="Settings button" desc="Opens the System Settings menu. The Image Settings menu also becomes available." >}}  
{{< callout num="7" term="End Case button" desc="Immediately stops a recording and the case." >}}  

{{< panel status="notice" title="NOTE" >}}All buttons are hidden after 5 seconds of cursor inactivity. To unhide them, move the cursor.{{< /panel >}}

### Recordings

Recordings save video from the camera. To save overlay information, enable the applicable DataFusion feature. Overlay information includes patient and case information from the system, or other data from connected systems.

The Quick Access Bar contains specified buttons for display options. Click the buttons to quickly change settings or, if available, click the drop-down menu below buttons to select a specific option.

![Quick Access Bar Features](sw_quick_access_bar.svg)

Use the Quick Access Bar to change the following display modes and settings:  

{{< callout num="1" term="Swap layout" desc="Changes the number of video inputs displayed on the Case screen (1 or 2). " >}}  
{{< callout num="2" term="Input source" desc="Switches the primary and secondary video inputs displayed on the Procedure screen in PiP or split layout." >}}  
{{< callout num="3" term="Camera orientation" desc="Rotates the camera video 180° to adjust for camera installation factors or inverting lens additions." >}}  
{{< callout num="4" term="Imaging mode" desc="Changes the camera orientation and light profile according to common preset settings for anterior, posterior, and macular operations. To manage imaging modes, contact Technical Services. NOTE: If operating with different illumination sources or optical systems that require the use of inverted camera orientation, Alcon recommends creating an imaging mode to accommodate individual surgical workflows." >}}  
{{< callout num="5" term="Light profile" desc="Changes color correction settings for each  illumination source. NOTE: If the correction method is set to White Balance, the drop-down menu contains an option to set the white balance. If the method is set to Temperature, the drop-down menu contains previews of potential temperature adjustments and a slider to set the value." >}}  
{{< callout num="6" term="Color channel" desc="Changes the emphasis of specific color channels according to preset settings. This setting supersedes the color settings in the selected imaging mode." >}}  

## End Case

When the case is complete, click **End Case**. Recordings stop and the following prompts appear:
1. If any imaging mode changes were made during the case, select **Yes** to save the changes or **No** to delete the changes.
2. If desired, save recorded video. To save a copy of the video to an external hard drive, connect one to a [side panel USB connector](../../additional/external_usb).
3. If a patient profile was not selected, enter patient information.
4. If desired, enter keywords for sorting and searching files in TrueMedia. The folder name is the case
start time by default and appears in TrueMedia.
