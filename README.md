# How HDR images and videos are captured

A blog post tracing HDR imaging from first principles — how a camera photosite works, why dynamic range is physically bounded, and how three distinct engineering approaches solve the problem.

**Read it:** [`hdr_imaging.md`](hdr_imaging.md)

## What's covered

1. How cameras work — photons, potential wells, aperture, shutter speed
2. Exposure Value (EV) and ISO — the formula that unifies the exposure controls
3. Dynamic range — what limits it and how wide a real scene actually is
4. The low-light problem on mobile — small pixels, shot noise, and why hardware alone can't fix it
5. Debevec's approach — multi-exposure bracketing and why ghosting kills it
6. Google HDR+ — burst photography at constant EV, noise averaging math, and the underexposure strategy
7. Capturing HDR video — ARRI's dual-gain readout and how the ALEXA 35 reaches 17 stops in a single frame
