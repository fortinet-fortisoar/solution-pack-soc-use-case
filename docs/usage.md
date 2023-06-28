| [Home](../README.md) |
|----------------------|
# Usage

To experience FortiSOAR&trade; with the **SOC Experience** solution pack, automate scenarios, and explore its capabilities effortlessly you need to setup a demo environment and, when required, reset it.

## Setup Demo SOC Environment

This section explains how to setup an environment for a demo:

1. Open the **Alerts** module
2. Click **Execute** > **Setup Demo SOC Environment** playbook.

This playbook executes all available scenarios in FortiSOAR&trade; and generates example records for each solution pack installed with *SOC Experience* solution pack.

It also ingests data for MITRE ATT&CK, creating latest records for all MITRE-related modules.

![Setup Demo Env](./res/setup_demo_env.png)

## Reset Demo SOC Environment

This section explains how to reset an environment after a demo:

1. Open the **Alerts** module
2. Click **Execute** > **Reset Demo SOC Environment** playbook.

    ![Reset Demo Env](./res/reset_demo_env.png)

This playbook removes all example records created by scenarios and deletes the records created by the scenario.

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Contents](./contents.md) |
|-----------------------------------------|-------------------------------------------|---------------------------|