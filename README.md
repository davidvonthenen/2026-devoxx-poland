# Devoxx Poland 2026 - A Practical Guide to Training a Small Language Model: Tokenizers, Training, and Real-World Pitfalls

Welcome to the landing page for the session `A Practical Guide to Training a Small Language Model: Tokenizers, Training, and Real-World Pitfalls` at `Devoxx Poland 2026`.

## What to Expect

This repo intends to provide an introduction to:

- Building a Small Language Model (SLM) From scratch
- Provide a guide for Fine-tuning and Quantization
- Provide a guide for Distillation Training

> **IMPORTANT:** Do not actually use any of these models for production. There are already a **TON** of models that do this exact thing. (Check out HuggingFace) Definitely, use those models over these. 

## Hardware Prerequisites

The SLM training, Fine-tuning, and Distillation projects will require a GPU (and of the H100 or better variety). There is simply no getting around that.

If you don't have access to this kind of hardware, you can at least download the pre-built models for inference.

## Software Prerequisites

- A Linux or Mac-based Developer’s Laptop 
  - Windows Users should use a VM or Cloud Instance
- Python Installed: version 3.12 or higher
- (Recommended) Using a miniconda or venv virtual environment
- Basic familiarity with shell operations

## Participation Options

There are 3 separate demo projects:

- [demo/1_SLM](./demo/1_SLM/README.md)
- [demo/2_FineTune_Quant](./demo/2_FineTune_Quant/README.md)
- [demo/3_MLM](./demo/3_MLM/README.md)

The instructions and purpose for each demo is contained within their respective folders.
