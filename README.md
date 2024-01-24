# Alfred Warp Integration Workflow

Welcome to the Alfred Warp Integration Workflow repository! This workflow is designed to seamlessly integrate the Warp terminal into your Alfred experience, providing a native-like user interface and enhanced productivity features.

## Overview

The Alfred Warp Integration Workflow facilitates a smoother interaction between Alfred and the Warp terminal. By generating a specific launch configuration file, it enables the execution of terminal commands directly from Alfred, leveraging Warp's capabilities.

## My setup

- Alfred v4.8[1312] with powerpack
- Warp v0.2024.01.16.16.31.stable_01
- macOS Sonoma 14.2.1

## How It Works

Upon activation, this workflow creates a [launch configuration file](https://docs.warp.dev/features/sessions/launch-configurations#commands) named `alfred.yaml` in the `~/.warp/launch_configurations/` directory. This file contains the `exec:` parameter, which holds the input command. The workflow then uses Warp's URL scheme to launch Warp with the `alfred.yaml` configuration, allowing for the execution of the command.

## Installation Guide

1. **Check Keyword Availability**: Ensure the keyword `w` is not already in use by other workflows in Alfred. If necessary, modify the keyword for this workflow.
   
2. **Download and Install**: Download the `warp_launch_config.alfredworkflow` file. Double-clicking the file will prompt Alfred to import the workflow. Follow the on-screen instructions to complete the setup.

## Configuration and Usage

After installation, simply type `w` followed by your command in Alfred. The command will execute in Warp with the specified configuration.

