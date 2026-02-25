# Phase-Coupled Stability Threshold Law

**ID:** `eq-arp-phase-critical-collapse`  
**Tier:** derived  
**Score:** 77  
**Units:** OK  
**Theory:** PASS-WITH-ASSUMPTIONS  

## Equation

$$
\frac{dG_{ij}}{dt}=\alpha\,|I_{ij}|-\mu\,G_{ij}-\lambda\,G_{ij}\,\sin^2\!\left(\frac{\theta_{R,ij}}{2\pi_a}\right)
$$

## Description

Adds a phase-coupled suppression term to ARP: conductance growth is damped by lifted phase accumulation relative to the local period 2ÃƒÂÃ¢â€šÂ¬ÃƒÂ¢Ã¢â‚¬Å¡Ã‚Â. Predicts a sharp stability/transition-like behavior when ÃƒÅ½Ã‚Â¸_R approaches half-integer multiples of ÃƒÂÃ¢â€šÂ¬ÃƒÂ¢Ã¢â‚¬Å¡Ã‚Â (maximal sinÃƒâ€šÃ‚Â²). Assumptions: ÃƒÅ½Ã‚Â¸_R,ij is a Phase-Lifted (unwrapped) phase-like observable for edge current; ÃƒÂÃ¢â€šÂ¬ÃƒÂ¢Ã¢â‚¬Å¡Ã‚Â sets the relevant phase period; ÃƒÅ½Ã‚Â» has units 1/time.

## Repository Structure

```
images/       # Visualizations, plots, diagrams
derivations/  # Step-by-step derivations and proofs
simulations/  # Computational models and code
data/         # Numerical data, experimental results
notes/        # Research notes and references
```

## Links

- [TopEquations Leaderboard](https://rdm3dc.github.io/TopEquations/leaderboard.html)
- [TopEquations Main Repo](https://github.com/RDM3DC/TopEquations)
- [Certificates](https://rdm3dc.github.io/TopEquations/certificates.html)

---
*Part of the [TopEquations](https://github.com/RDM3DC/TopEquations) project.*

## Contributing

You can add images, derivations, simulations, data, or notes to this repo:

| Folder | What goes here |
|--------|---------------|
| `images/` | Plots, diagrams, phase portraits, animations (.png, .jpg, .mp4, ...) |
| `derivations/` | Step-by-step derivations and proofs (.tex, .md, .pdf) |
| `simulations/` | Computational models and code (.py, .ipynb, .jl, .m) |
| `data/` | Numerical results, experimental measurements (.csv, .hdf5, .npy) |
| `notes/` | Research notes, lit reviews, references (.md, .bib, .txt) |
| `docs/` | Formal documents, validation plans (.md, .pdf) |

**Three ways to contribute:**
1. **GitHub Issue** — click [New Issue](../../issues/new?template=artifact_submission.yml) and attach your file
2. **Pull Request** — fork, add files, open a PR
3. **CLI** — `python tools/push_to_equation_repo.py --equation-id eq-arp-phase-critical-collapse --file <path> --folder <folder>`

All submissions are content-moderated. See the [full contributing guide](https://github.com/RDM3DC/TopEquations/blob/main/CONTRIBUTING.md).
