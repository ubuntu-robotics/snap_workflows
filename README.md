# snap_workflows

Repository storing [reusable workflows](https://docs.github.com/en/actions/using-workflows/reusing-workflows) for snaps.

These workflows are intended to be re-used in github actions building snaps.

Having reusable workflows improves efficiency and helps with the execution of scheduled workflows. As outlined in the documentation, scheduled workflows operate exclusively on the main branch. However, integrating reusable workflows simplifies the process of configuring scheduled actions for the main branch within a specific repository. A working example on how to use a workflow can be found [here](https://github.com/ubuntu-robotics/ros2-humble-talker-listener-snap/blob/main/.github/workflows/snap.yaml).
