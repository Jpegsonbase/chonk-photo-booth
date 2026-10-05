# Chonk Photo Booth

Walk your [Chonks](https://www.chonks.xyz) through 3D locations, pose them together, and snap high-resolution photos.

**Open it:** https://jpegsonbase.github.io/chonk-photo-booth/

## What you can do

- Load any Chonk by token ID, or paste a wallet address to list every Chonk it holds.
- Walk around with WASD or the arrow keys (Shift to run, Space to jump, 1 to wave, 2 to bow). On phones there's an on-screen joystick.
- Explore eleven locations: Castle, Office, Mansion, Art Gallery, The Playground, Sunset Beach, Neon Rooftop, Snowy Pines, Moon Base, Red Canyon and Colour Studio. You can also drop in your own `.glb` scene.
- Clone your Chonk, then load another into your slot to group up to 10 Chonks in one shot.
- Press **P** for photo mode: pick each Chonk's pose, freeze a moment mid-stride, choose a frame shape (1:1, 4:5, 16:9, 9:16) and lens, then snap a PNG up to 2560 px wide.

## How it works

It's one self-contained page (`index.html`) built with three.js. The Chonk rig and animations are ported directly from the official Chonks Playground, so walks and poses match it exactly. Chonk voxel data comes live from the Chonks indexer. Chonks art is CC0.
