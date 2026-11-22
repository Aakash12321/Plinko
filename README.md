# Plinko

A Plinko board physics simulation: coloured balls drop from the top every few seconds and bounce off the pegs into the slots below.

## How to play
- Just watch: a new ball drops automatically.

## Run it locally
Browsers block games that load images and scripts straight from disk, so serve the folder with any small web server:

```bash
git clone https://github.com/Aakash12321/Plinko.git
cd Plinko
python -m http.server 8000
```

Then open <http://localhost:8000> in your browser. (The VS Code **Live Server** extension works too.)

## Built with
- p5.js
- Matter.js
