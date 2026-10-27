# EGN 325 Computer Architecture: course interactives

Interactive simulations for EGN 325 (Atlantis University). Each week has self-contained HTML pages: an explorer (Interactive A) and a scored challenge (Interactive B). The LMS blocks link to these pages through GitHub Pages.

Live site: https://au-extension.github.io/EGN-325/

## Structure

| Folder | Topic | Interactive A | Interactive B |
|---|---|---|---|
| week1 | Inside a computer: layers, parts, and performance | layers-zoom.html | build-the-right-computer.html |
| week2 | Data representation: how computers store numbers and text | bit-pattern-explorer.html | overflow-challenge.html |
| week3 | Digital logic: gates and combinational circuits | logic-gate-playground.html | circuit-builder-challenge.html |
| week4 | Sequential logic: clocks, memory, and state machines | flip-flop-timing.html | state-machine-challenge.html |
| week5 | The processor: datapath, control, and the instruction cycle | cpu-datapath-animator.html | fetch-decode-execute-challenge.html |
| week6 | Instruction sets and assembly language (RISC-V) | riscv-step-through.html | assembly-puzzle-challenge.html |
| week7 | Memory hierarchy and performance | cache-simulator.html | performance-tuning-challenge.html |
| week8 | Pipelining, parallelism, and modern processors | pipeline-visualizer.html | architecture-matchmaker.html |

`simulator.html`: Bay-4 computer simulator. A 3D Bay-4 computer that runs your program through the fetch-decode-execute cycle, with live registers, memory, and data moving on the buses. Use it in Weeks 5 to 8.

## Publishing

1. Push this folder to the `main` branch of `AU-Extension/EGN-325`.
2. In the repository, open Settings, then Pages, and set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Each page is then live at `https://au-extension.github.io/EGN-325/weekN/<file>.html`.

Every page loads the logo and GSAP and fonts from public CDNs, still works if GSAP fails to load, and needs no build step.
