# Home Lab Trading Platform

This repository contains Kubernetes manifests for the trading platform applications managed by ArgoCD.

## Structure

- **apps/**: Contains the application manifests. ArgoCD is configured to recursively watch this directory.

## Applications

- **Findrai Auto Grow**: A CronJob that triggers the auto-grow script daily at 06:00 AEST.
