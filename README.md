# eSim 2.5 Port for Ubuntu 25.04 (Plucky Puffin)

**FOSSEE Internship Spring 2026 - Task 4 Submission**
* **Ported by:** Juned Mahetab Pinjari
* **Status:** ✅ Stable / Verified
* **Architecture:** x86_64

## 📌 Project Overview
This repository contains the patched installation scripts required to run **eSim 2.5** on **Ubuntu 25.04**. The official installer supports up to Ubuntu 22.04/24.04. This port resolves critical architectural incompatibilities introduced by **GCC 14**, **LLVM 20**, and **Python 3.13**.

## 🚀 Installation Guide

### Prerequisites
* **OS:** Ubuntu 25.04 (Plucky Puffin)
* **RAM:** Minimum **4GB** (Required for Mixed-Signal compilation)
* **Internet:** Active connection required for downloading dependencies.

### Quick Start
Run the following commands in your terminal:

```bash
# 1. Clone this repository
git clone [https://github.com/Md-Juned-45/eSim.git](https://github.com/Md-Juned-45/eSim.git)
cd eSim

# 2. Checkout to the installer branch
git checkout installer

# 3. Make the script executable
chmod +x install-eSim.sh install-eSim-scripts/install-eSim-25.04.sh

# 4. Run the installer
./install-eSim.sh --install
