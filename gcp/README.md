# 🟨 GCP Free Tier VM - Terraform

This module provisions a **f1-micro Ubuntu VM** using Terraform on Google Cloud Platform (GCP), eligible under Free Tier.

---

## 🔧 Pre-requisites

- GCP account with billing enabled
- Enabled Compute Engine API
- Google Cloud CLI (`gcloud`) installed
- SSH key pair available

---

## 📦 Setup

### 1. Authenticate with Google Cloud

```bash
gcloud auth application-default login

Changed Zone from "us-west1-b" to "us-west1-a" since f1-micro VM instance is currently unavailable in the us-west1-b zone.

variable "zone" {
  description = "GCP zone"
  default     = "us-west1-a"
