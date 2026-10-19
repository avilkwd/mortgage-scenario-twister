# Mortgage Scenario Twister

A four-reel mortgage scenario generator that combines one random result from each category:

- People type
- Wage type
- Property type
- Underwriting hiccup

## Run

Open [index.html](./index.html) from the repository after cloning/downloading. For reliable browser loading of the `data/*.txt` files, serve the project locally, for example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

Alternatively, enable **GitHub Pages** in repository **Settings → Pages → Deploy from a branch → main / (root)** to play directly in the browser.

## Mechanics

Pull the lever to animate all four reels. They stop left-to-right, 250 ms apart. Results are drawn independently with cryptographic browser randomness and unbiased integer selection. The interface includes history, copy-to-clipboard, and optional local imports of replacement TXT lists.

## Data

The four editable lists are under `data/`: `people.txt`, `wages.txt`, `properties.txt`, and `hiccups.txt`. Each list uses numbered entries.
