---
title: "System Settings"
description: "Description of settings that affect the entire console or cart"
lead: ""
date: 2022-10-04T08:48:57+00:00
lastmod: 2022-10-04T08:48:57+00:00
draft: false
images: []
menu:
  docs:
    parent: "settings"
weight: 3510
toc: true
---

System settings apply to all doctor profiles on the system and are primarily related to connecting devices to the system. They also include system information. To access System Setting options, click **System Settings**.

<img src="sw_system_settings.png" width="300px"/>

## DataFusion

The DataFusion settings determine which device is connected to the system. To access DataFusion options, click **DataFusion**. The system can only enable one device at a time.

![DataFusion Dialog Box](sw_system_settings_datafusion.svg)

{{< callout num="1" term="Constellation™ toggle switch" desc="Enables Constellation™ connection." >}}  
{{< callout num="2" term="Centurion™ toggle switch" desc="Enables Centurion™ connection." >}}  
{{< callout num="3" term="Edit button" desc="Opens a dialog box to connect to a specific device." >}}  

To connect to a Centurion&trade;, perform the following:

1. Click **Edit**.

    <img src="sw_system_settings_datafusion_device_list.png" title="Centurion™ Device List" width="175px"/>

2. Press **Scan**.
3. Select the device from the list.
4. If necessary, enter a new name for the device. This name only appears in the system.
5. Click **Confirm**.

## Input Source

The input source controls which port is displayed in the secondary view. To set the secondary input source, click **Input Source**.

{{< panel status="notice" title="NOTE" >}}No other sources are available for systems with a connected ORA SYSTEM&trade;.{{< /panel >}}

![Input Source Dialog Box](sw_system_settings_input_source.png)

In the View 2 panel, select one of the following:

* **HDMI** – Displays the input source from a connected ORA SYSTEM&trade;.
* **Composite** – Displays the input source connected to the front panel composite connector.

## Monitor

The monitor system settings have adjustable settings for displays connected to the system. To access Monitor options, click **Monitor**.

### Basic Monitor Settings

{{< panel status="warning" title="WARNING" >}}Only the provided monitor should be used as the Primary Monitor.{{< /panel >}}

![Monitor Dialog Box (3D Format Locked)](sw_system_settings_monitor_locked.svg)

{{< callout num="1" term="Monitor drop-down menu" desc="Selects a display." >}}  
{{< callout num="2" term="Primary Monitor toggle switch" desc="Sets the selected display to the primary display." >}}  
{{< callout num="3" term="View drop-down menu" desc="Sets the content on the screen. Select Control to display the user interface and system camera image, Surgery to display a limited subset of the user interface and system camera image, or Camera Only to display the system camera image only." >}}  
{{< callout num="4" term="3D Format lock button" desc="Unlocks the 3D format options. To edit 3D formatting, click the Unlock button." >}}  

### 3D Format Settings

![3D Format Options](sw_system_settings_monitor_unlocked.svg)

{{< callout num="1" term="Format drop-down menu" desc="Sets the monitor 3D format. Select Monoscopic for 2D displays, Top-Bottom for LG displays, or Row-Interleaved for 55″ FSN displays." >}}  
{{< callout num="2" term="Swap 3D button" desc="Swaps the stereoscopic polarity of the display. Display information displays on the left side of the screen. The information helps identify the display and evaluate if the display is working properly." >}}

### Add Monitor

The Add Monitor panel displays after connecting a new monitor to the system.

![Add Monitor Dialog Box](sw_system_settings_add_monitor.png)

To add a monitor, perform the following:

1. In the **3D Format** drop-down menu, select a format.
2. In the Polarity panel, select one of the following:
   * **Normal** – Renders left and then right stereoscopic images.
   * **Swap** – Renders right and then left stereoscopic images.

### 3D Polarity

To determine if the 3D monitor has the correct polarity, perform the following:

1. Put on the 3D glasses.
2. Close your right eye.
3. Verify you can only see the “Left” on-screen text.
4. Repeat the process with the other eye and verify that you only see the “Right” on-screen text.
