# ML Visual Lab

**Interactive visualisations that make machine learning maths something you can see and play with.**

Each demo is a single, self-contained HTML page: no install, no build step, nothing to download. Open [`index.html`](index.html) in a browser to start.

| Demo | Concept | What you do |
|---|---|---|
| [Eigenvector Field](eigenvector-explorer.html) | Linear algebra, covariance, PCA | Rotate, stretch and reshape a 2D point cloud and watch the eigenvectors of its covariance matrix track the directions of greatest variance in real time |
| [Understanding Entropy](008_entropy_visualization.html) | Information theory | Drag a probability slider and see why uncertainty, measured in bits, peaks at p = 0.5 and vanishes at the extremes |

## Run it

```bash
git clone https://github.com/cksajil/ml-visual-lab.git
cd ml-visual-lab
python3 -m http.server 8000   # or just open index.html
```

Then open http://localhost:8000.

## Related

- [ML & AI Knowledge Graph](https://cksajil.github.io/ml-knowledge-graph/): an interactive map of ML concepts and how they connect
- [intuitivetutorial.com](https://intuitivetutorial.com): written explanations of ML concepts

## License

See [LICENSE](LICENSE).
