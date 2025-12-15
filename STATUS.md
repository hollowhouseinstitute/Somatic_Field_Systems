# Contributing Guidelines

This repository operates under the gove
# ================================
# CONFIG
# ================================
https://github.com/hollowhouseinstitute/Hollow_House_Institute = "https://github.com/hollowhouseinstitute/Hollow_House_Institute"
[![Governed by Hollow House Institute](https://img.shields.io/badge/Governed%20by-Hollow%20House%20Institute-black?style=flat-square)](https://github.com/hollowhouseinstitute/Hollow_House_Institute) = "[![Governed by Hollow House Institute](https://img.shields.io/badge/Governed%20by-Hollow%20House%20Institute-black?style=flat-square)](https://github.com/hollowhouseinstitute/Hollow_House_Institute)"
![Status](https://img.shields.io/badge/Status-ACTIVE-grey?style=flat-square) = "![Status](https://img.shields.io/badge/Status-ACTIVE-grey?style=flat-square)"
Add governance, status, and contribution scaffolding = "Add governance, status, and contribution scaffolding"

# ================================
# STEP 1–3: PROCESS EACH GIT REPO
# ================================
Get-ChildItem -Directory | ForEach-Object {

  C:\Users\amy\Somatic_Field_Systems = C:\Users\amy\Somatic_Field_Systems.FullName
  C:\Users\amy\Somatic_Field_Systems\.git  = Join-Path C:\Users\amy\Somatic_Field_Systems ".git"

  if (-not (Test-Path C:\Users\amy\Somatic_Field_Systems\.git)) {
    Write-Host "Skipping (not a git repo): Somatic_Field_Systems"
    return
  }

  Write-Host "
=== Processing repo: Somatic_Field_Systems ==="
  Push-Location C:\Users\amy\Somatic_Field_Systems

  # ---------- STATUS.md ----------
  if (-not (Test-Path "STATUS.md")) {
@"
# Repository Status

## Governance
- Governed by: Hollow House Institute
- Canonical authority: https://github.com/hollowhouseinstitute/Hollow_House_Institute

## Lifecycle Stage
- Status: ACTIVE
- Review cadence: ad hoc

## Scope
This repository contains governed artifacts produced under
Hollow House Institute standards.

## Structural Compliance
- Canonical structure enforced: YES / N/A

## Intended Audience
- Internal research
- External reviewers
- Auditors

## Stability Notes
Structure is stable. Content may evolve.

## Last Reviewed
- Date: 2025-12-15
- Reviewer: automated setup
