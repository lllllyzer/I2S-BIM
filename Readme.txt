# P2BIM: Semantic Point Cloud to IFC BIM Model

This repository provides a software tool, `P2BIM.exe`, which is a packaged solution for converting semantic point clouds into IFC-format as-is BIM models. The tool processes point cloud data after semantic reconstruction and generates the corresponding BIM model.

## Table of Contents

- [Data Processing Workflow](#data-processing-workflow)

## Overview

This tool is designed to convert semantic point cloud data into a BIM model in IFC format. The process involves:
1. Extracting and converting the data into a structured format.
2. Using `P2BIM.exe` to generate an IFC file, which can then be used for further analysis or visualization.

## Environment Setup

To use `P2BIM.exe`, please ensure the following:

1. **Clone the repository (if applicable):**

   ```bash
   git clone https://github.com/yourusername/P2BIM.git
   cd P2BIM
**Test Data for IFC Model Reconstruction**

In this project, we provide the processed data in the [n ox oy oz xsize ysize zsize 0] format for testing the feasibility of automatic IFC-format BIM model reconstruction. We also provide the resulting `.IFC` file after reconstruction.

You can view the generated IFC files using **BIMVision**. BIMVision is a lightweight IFC model viewer that allows you to open and inspect the IFC files generated in this project. Simply load the `.ifc` file in BIMVision for visual inspection and analysis.
