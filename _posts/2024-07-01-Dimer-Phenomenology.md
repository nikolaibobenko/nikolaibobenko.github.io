---
layout: post
title: Aztec diamond web app
tags: research dimers
date: 2026-10-27
---

I recently went back to the code I created for the M-Curves papers and reworked it as a web app. Check it out [here](https://www.nikobob.com/spectralPlayground). This is an interactive demo running in the browser via WASM and WebGPU allowing you to observe the phenomenology of the Aztec diamond in real time for arbitrary quasi-periodic weights. Predicted arctic curves are overlaid so you know if your simulation has reached equilibrium or not yet.

For more fancy weights (especially large gas regions), it can be a good idea to simulate simler weights first. Let those converge and then start complicating the weights step by step. This speeds up convergence times significantly.

