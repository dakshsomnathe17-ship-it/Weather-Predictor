# Weather Predictor

A comprehensive weather prediction workspace combining a full-stack web application with machine learning models and real-time weather data visualization.

## Project Structure

| Directory | Description |
|---|---|
| **Weather-Perdiction/** | Main application — full-stack weather prediction app with React frontend, FastAPI backend, and ML models (git submodule) |
| **Engine/** | Unreal Engine installation (not tracked — too large for Git) |
| **Templates/** | Unreal Engine project templates (not tracked) |
| **FeaturePacks/** | Unreal Engine feature packs (not tracked) |

## Getting Started

### Clone with submodules

```bash
git clone --recurse-submodules https://github.com/dakshsomnathe17-ship-it/Weather-Predictor.git
```

### If you already cloned without submodules

```bash
git submodule update --init --recursive
```

### Main Application

See [Weather-Perdiction/README.md](Weather-Perdiction/README.md) for detailed setup instructions.

## Branches (in Weather-Perdiction submodule)

- `main` — Stable release
- `feat/weather-app-ui` — Latest UI features
- `feat/era5-model-training` — ERA5 climate data ML pipeline
- `feat/cesium-earth` — Cesium-based 3D Earth visualization
- `feat/interactive-earth` — Interactive globe features

## License

MIT
