# HighRateMOS
HighRateMOS is the first non-intrusive MOS prediction model that explicitly models sampling rates, achieving first place in five out of eight metrics in AudioMOS Challenge 2025 Track3.
[![Paper](https://img.shields.io/badge/Paper-arXiv:2506.21951-B31B1B.svg)](https://arxiv.org/abs/2506.21951)

## Overview

Most speech quality assessment models are trained and evaluated at a fixed sampling rate (e.g., 16 kHz). In practice, however, speech signals use a range of sampling rates—16 kHz, 24 kHz, 48 kHz, which can affect perceived quality.

This project first addresses this mismatch by adding sampling-rate-aware components to an SSL-based MOS prediction framework, supporting robust quality estimation across diverse real-world conditions regardless of sampling rate.

