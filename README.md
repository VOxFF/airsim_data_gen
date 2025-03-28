 
# AirSim Data Generation

This repo contains Python scripts for controlling vehicles in AirSim, capturing stereo images, depth maps, and ground-truth poses for training models.

---

## Setup

### 1. Clone and Build Unreal Engine

> ⚠️ Requires ~130 GB of disk space.

```bash
git clone git@github.com:EpicGames/UnrealEngine.git
cd UnrealEngine
./Setup.sh 
./GenerateProjectFiles.sh
make
```

### 1. Clone and Build AirSim Plugin

```bash
git clone https://github.com/microsoft/AirSim.git
cd AirSim
./setup.sh
./build.sh
```
