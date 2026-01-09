# Sphere Eversion - Astrolabe Template

[![Astrolabe](https://img.shields.io/badge/Visualize%20with-Astrolabe-purple)](https://github.com/Xinze-Li-Bryan/Astrolabe)
[![Original Project](https://img.shields.io/badge/Original-leanprover--community%2Fsphere--eversion-blue)](https://github.com/leanprover-community/sphere-eversion)

An Astrolabe visualization template for the Sphere Eversion formalization in Lean 4.

## About This Template

This repository is an [Astrolabe](https://github.com/Xinze-Li-Bryan/Astrolabe) template based on the [Sphere Eversion project](https://github.com/leanprover-community/sphere-eversion).

**What's included:**
- Lean 4 source code formalizing the existence of sphere eversions
- Pre-configured `.astrolabe/` directory with canvas layout and node positions

**What's removed:**
- Blueprint LaTeX files
- Documentation build scripts

## Acknowledgments

Thanks to Patrick Massot, Floris van Doorn, Oliver Nash, and Yury Kudryashov for creating and porting this formalization. The proof of the main theorem was completed on November 12th 2022. See the [original repository](https://github.com/leanprover-community/sphere-eversion) and [project website](https://leanprover-community.github.io/sphere-eversion/) for full details.

## Usage with Astrolabe

1. **Get Astrolabe** from [GitHub](https://github.com/Xinze-Li-Bryan/Astrolabe)

2. **Clone this template:**
   ```bash
   git clone https://github.com/Xinze-Li-Bryan/astrolabe-template-sphere-eversion.git
   cd astrolabe-template-sphere-eversion
   ```

3. **Build the Lean project** (requires [Lean 4](https://docs.lean-lang.org/lean4/doc/quickstart.html)):
   ```bash
   lake exe cache get
   lake build
   ```

4. **Open in Astrolabe** - Launch Astrolabe and open this folder

## Project Structure

```
astrolabe-template-sphere-eversion/
├── .astrolabe/           # Astrolabe configuration
│   ├── canvas.json       # Node positions, camera state
│   ├── meta.json         # Node styles, notes
│   └── graph.json        # Parsed dependency cache
├── SphereEversion/       # Lean source files
├── lakefile.toml         # Lake build config
└── lean-toolchain        # Lean version
```

## Feedback

We welcome everyone to explore Lean 4 projects with Astrolabe! If you have any issues or suggestions, please report them to the [Astrolabe main repository](https://github.com/Xinze-Li-Bryan/Astrolabe/issues).

## License

See [LICENSE](LICENSE) file for details.
