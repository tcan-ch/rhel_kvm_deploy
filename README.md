<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/tcan-ch/kvm_deployment/">
    <img src="http://tcan.ch/tcan.ch_logo.png" alt="Logo">
  </a>

  <h3 align="center">KVM Deployment</h3>

  <p align="center">
    Deploy KVM with Ansible for a virtualized LAB running with VIRSH.
    <br />
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
  </ol>
</details>

## Notes
- Templates hochladen für virsh
- Scripttemplate von Mel
- Backup Script von Chris
- ansible-galaxy collection install community.libvirt
- dnf install python3-lxml

<!-- ABOUT THE PROJECT -->
## About The Project
This Project was created to autodeploy a virtual and easy to handle LAB based on Linux. The deployment is managed by ansible and will do the following tasks:
- Install Virsh

STEPS TO INSTALL:

- Install NANO
- Install VIRSH
- Configure Network

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites
- RHEL 8.3 Installation
- Registered and Subscribed to RHEL Dev Program
- Installed all updates
  ```sh
  dnf update -y
  ```
- Ansible installed
  ```sh
  dnf install ansible -y
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```


