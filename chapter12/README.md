# cder-webGPU

A small collection of WebGPU demonstrations and starter material focused on **GPU compute** (e.g., array/matrix multiplication) and **GPU rendering** (e.g., basic rendering and graph rendering) in the browser.

---

## What’s in this repo

This repository is organized as a set of self-contained topic folders.

Demo folders:

- `Starting a Project/`
- `Array Multiplication/`
- `Matrix Multiplication/`
- `Basic Rendering/`
- `Graph Rendering/`

---

## Prerequisites

### Browser support
WebGPU is a modern browser API for high-performance graphics and compute on the GPU. Use a recent WebGPU-capable browser (commonly a current Chromium-based browser).

---

## Demos

Each demo folder is intended to be self-contained.
### Starting a Project/
A starter template / scaffolding folder intended to provide:

- Minimal boilerplate for WebGPU initialization
- A recommended project layout

### Array Multiplication/
This module explores the essential components of WebGPU's device model through a simple compute pipeline—multiplying each element of an array by 2.

### Matrix Multiplication/
This module explores how to create an application for GPU-accelerated matrix multiplication.

### Basic Rendering/
This module demonstrates how to create a WebGPU application for GPU rendering of instanced triangles.

### Graph Rendering/
This module demonstrates how to create a WebGPU application that combines GPU compute and rendering to visualize graphs.

---

## Common troubleshooting

### “WebGPU is not available” / `navigator.gpu` is undefined
- Confirm you’re running a WebGPU-capable browser (https://caniuse.com/webgpu).
- Check browser settings/flags for WebGPU availability.

