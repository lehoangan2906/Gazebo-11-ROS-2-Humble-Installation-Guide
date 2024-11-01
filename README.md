# Gazebo-11-ROS-2-Humble-Installation-Guide

Gazebo 11 is not officially supported on Ubuntu 22.04 (Jammy Jellyfish). However, you can install it alongside ROS 2 Humble by using a community-maintained Personal Package Archive (PPA). Please note that this method may lack official support and updates.

### Step 1: Add the Community PPA

First, add the PPA that provides Gazebo 11 packages for non-amd64 architectures:

```bash
sudo add-apt-repository ppa:openrobotics/gazebo11-gz-cli
```

### Step 2: Update Package Lists

After adding the PPA, update your package lists:

```bash
sudo apt-get update
```

### Step 3: Install Gazebo 11

Now, install Gazebo 11:

```bash
sudo apt-get install gazebo11
```

### Step 4: Verify the Installation

To confirm that Gazebo 11 is installed correctly, run:

```bash
gazebo --version
```

