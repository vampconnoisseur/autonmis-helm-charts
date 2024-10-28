# Autonmis Helm Charts

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/autonmis)](https://artifacthub.io/packages/search?repo=autonmis)

A Helm chart repository for deploying [Autonmis](https://autonmis.com), providing a simple way to manage and scale your deployment.

## Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Installing the Chart](#installing-the-chart)
- [Chart Configuration](#chart-configuration)
- [Upgrading to New Versions](#upgrading-to-new-versions)
- [Available Versions](#available-versions)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This repository hosts Helm charts for the Autonmis application, enabling you to deploy and manage Autonmis in a Kubernetes cluster. The chart includes configurations for deploying Autonmis with all necessary dependencies, scaling options, and customization points.

## Requirements

- **Kubernetes** >= 1.20
- **Helm** >= 3.0

## Installing the Chart

To add the Autonmis Helm repository:

```bash
helm repo add autonmis-helm https://vampconnoisseur.github.io/autonmis-helm-charts
helm repo update