# DelftDashboard Tiling Toolbox

A DelftDashboard toolbox for generating tiled web map data (index tiles and topobathy tiles) from model grids.

## Features

- Generate webmercator index tiles from an SFINCS or HurryWave grid
- Generate webmercator topobathy tiles
- Optional elevation-range masking for HurryWave index tiles
- Configurable maximum zoom level

## Installation

```bash
pip install git+https://github.com/your-org/delftdashboard-tiling-toolbox.git
```

The toolbox is automatically discovered by DelftDashboard via entry points — no configuration changes needed.

## Requirements

- [DelftDashboard](https://github.com/Deltares-research/DelftDashboard)
- [cht_tiling](https://github.com/deltares-research/cht_tiling) (installed automatically)

## License

MIT
