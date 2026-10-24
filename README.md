# Pond — A Navigable Body of Data

**An experimental browser-based interface for exploring text and images as sediment within a virtual pond.**

Rather than searching a database or selecting cards, visitors move through a three-dimensional space. Text fragments occupy fixed locations, appearing, receding and becoming increasingly scrambled with depth. A dense layer of typographic sediment accumulates at the bottom of the pond. Images uploaded by the visitor become atmospheric backgrounds, changing through spatially triggered crossfades as they move.

The project develops ideas explored through the *Cryptogamic Oracle*, investigating how attention, proximity and movement might offer alternative ways of encountering an archive.

## Features

- **Navigable data volume:** a virtual pond measuring approximately 200 × 500 × 100 cm.
- **Spatial text fragments:** prompts appear larger and clearer nearby and fade into the distance.
- **Adjustable fog:** reduces visual clutter and limits the number of distant elements drawn.
- **Depth-dependent glitch:** text becomes increasingly scrambled as the viewer descends.
- **Sediment layer:** the bottom 10 cm contains a denser accumulation of prompts, text fragments and moving ASCII characters.
- **Motile characters:** small typographic particles drift and occasionally dart through the water.
- **Local image upload:** select multiple images from your computer; they are automatically assigned to regions of the pond.
- **Movement-triggered image crossfades:** images fill the background behind the text and change as you enter different spatial regions.

## Run the project

### Standalone version

Open **`pond_iteration_03_images.html`** in a modern desktop browser. The JavaScript is embedded in the HTML file, so this version requires **no installation, server or internet connection**.

Click **Upload images** (or press **U**) to choose several JPG, PNG or other browser-supported image files. The images are read locally in the browser; they are not uploaded to a server. Reopening the page resets the selection.

### p5.js version

Copy the contents of **`sketch_images.js`** into the `sketch.js` editor at [editor.p5js.org](https://editor.p5js.org/) and run it. This version uses the p5.js environment; the standalone HTML uses a lightweight Canvas adapter.

## Controls

| Key | Action |
| --- | --- |
| ↑ / ↓ | Move forwards / backwards |
| ← / → | Move left / right |
| Q / E | Rise / descend |
| Shift | Move faster |
| U | Open image upload |
| I | Toggle background images |
| F | Toggle fog |
| [ / ] | Decrease / increase fog visibility distance |
| T | Toggle text scrambling |
| N | Toggle sediment layer |
| G | Toggle grid |
| H | Toggle interface |
| R | Reset viewpoint |

## How the images work

Uploaded images are distributed across spatial zones in the virtual pond. The visitor's position determines which image region is active. Moving from one region to another triggers a background crossfade; the image remains behind the rendered text and sediment.

This is a **spatially triggered slideshow**, not yet a true simultaneous multi-image composite. Text and image placement can be developed further in later iterations.

## Project status

**Experimental prototype — Iteration 03.** The text prompts currently included are placeholders rather than a complete *Cryptogamic Oracle* archive. The work is intended for continued testing and development.

## AI-generated code and development process

**The code for this prototype was generated with the assistance of OpenAI's ChatGPT through an iterative process of prompting, testing, feedback and revision.** The artistic concept, research direction, interaction requirements and design decisions were developed and directed by the project creator. The code is shared as an experimental, AI-assisted creative coding study, rather than as a finished software product.

## License

No license has been specified. Add a `LICENSE` file if you want to define how others may use or adapt the code.
