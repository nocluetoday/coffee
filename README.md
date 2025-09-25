# Coffee TDS & Extraction Yield Calculator

A single-page calculator for coffee enthusiasts who use handheld refractometers. It converts between Brix and TDS, tracks extraction yield, and provides quick reference tables and dial-in planning aids – all offline.

## Features
- **Brix ⇄ TDS converter** with editable conversion factor and presets.
- **Extraction yield calculator** that highlights target bands.
- **Quick lookup tables** for brewed coffee and espresso strength ranges.
- **Dial-in grid** to plan beverage ratios and visualize extraction outcomes.
- Responsive, works without external dependencies, and keeps all calculations client-side.

## Usage
1. Open `coffee.html` in any modern browser.
2. Adjust the Brix↔TDS factor to match your calibration (defaults to 0.85).
3. Enter your refractometer readings, beverage mass, and dose to view live updates of TDS and extraction yield.
4. Explore the quick tables or dial-in grid to compare different brew ratios and targets.

## Development
No build tooling required – edit `coffee.html` directly. The JavaScript is embedded at the bottom of the file and updates the UI by listening to input events.

## License
MIT
