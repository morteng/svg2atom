# SVG to Atom

Browser tool that converts an SVG into an AtomStack Studio `.atom` project for the AtomStack Hurricane 55 W CO₂ laser, with speed, power, passes and air assist set per layer (one layer per stroke colour).

Live: https://morteng.github.io/svg2atom/

- Everything runs in the browser; no upload.
- Supports paths (all commands, arcs), rect, circle, ellipse, line, polyline, polygon, groups, `use`, transforms, mm/cm/in/pt/px units and viewBox.
- Text must be converted to paths first.
- "Cut inner shapes first" puts holes on their own earlier cut layer.
- The `.atom` format was reverse-engineered from AtomStack Studio 2.6 project saves; check layer settings in Studio before cutting.
