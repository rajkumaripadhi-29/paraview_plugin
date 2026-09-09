# ScalarDepthTracker – ParaView Plugin

A custom ParaView plugin developed for **spatio-temporal analysis of scalar fields in ocean data using vertical transect slicing**.

The plugin allows users to analyze oceanographic variables such as **salinity, temperature, horizontal velocity, and vertical velocity** across depth and time. It is implemented using Python and `VTKPythonAlgorithmBase` and is designed to work with structured NetCDF datasets in ParaView.

## Features

- Vertical transect-based scalar field analysis
- Time-depth visualization
- User-defined latitude and longitude
- User-defined depth range
- Dynamic scalar variable selection
- Supports salinity (`so`)
- Supports temperature (`thetao`)
- Supports horizontal velocity (`uo`)
- Supports vertical velocity (`vo`)
- Generates multiple outputs for visualization

## Macro

The repository also contains a **ParaView Python macro** that automatically creates a dual-view layout for the plugin output.
This makes the output easier to visualize and analyze within ParaView.

## Technologies

- Python
- ParaView
- VTK
- NumPy
- NetCDF

## Project

**Project Title:** Spatio-Temporal Analysis of Scalar Fields in the Ocean Using Vertical Transect Slicing

**Plugin:** ScalarDepthTracker

**Platform:** ParaView

This work was developed as part of a research project at the **Indian Institute of Science (IISc)**.
