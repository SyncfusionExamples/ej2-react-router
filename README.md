# Essential JS2 React sample with router and webpack

Repository Description: A React + webpack sample demonstrating how to compile TSX sources into a single bundle and use routing for a static HTML deployment.

## Project Overview

This sample shows using webpack to compile TSX files (React) and produce a bundled output that can be served from a static HTML page. The project includes routing setup and a minimal dev server for local testing.

## Features

- Webpack-based TSX compilation
- React router integration
- Single-file bundle suitable for static hosting

## Prerequisites

Install Node.js and npm (v6.6.0 or newer). Verify versions with `node -v` and `npm -v`.

Install the referenced webpack version globally if needed:

```bash
npm i -g webpack@2.6.1
```

## Install

```bash
npm install
```

## Run (development)

```bash
npm start
```

Open http://localhost:3000/ in a browser to view the running sample.

## How it works

Webpack compiles the TSX sources into a single bundle referenced from `src/index.html`. The routing setup in the example demonstrates navigating between components while using the compiled bundle in a static page.