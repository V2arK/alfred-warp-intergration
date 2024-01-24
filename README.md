# Alfred Warp Intergration

This repository contains a Workflow aim to mimic the native-like experience of the intergration of Terminal.

## How it works

This workflow works by create a [launch configuration file](https://docs.warp.dev/features/sessions/launch-configurations#commands) under the default configuration directory `~/.warp/launch_configurations/` called `alfred.yaml` with the `exec: ` parameter containing the input, and uses `URL scheme` to launch the Warp with `alfred.yaml` configuration file.

## How to install

1. Firstly, make sure non of your workflow uses keyword `w`, or you can choose to change the keyword of this workflow.

2. Just double click the file `warp_launch_config.alfredworkflow`, you should be prompted by alfred to import this workflow.
