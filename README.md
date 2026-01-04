# Map APIs TypeScript definitions and Closure Compiler externs

TypeScript type definitions and Closure Compiler externs for map APIs.

## Currently included

### TypeScript definitions (`types/`)
- Baidu Maps API v2.0
- Mapy.cz API v4.11

These definitions are intended for IDE autocomplete and type checking only. No runtime code is included.

### Closure Compiler externs (`closure-externs/`)
- Baidu Maps API v2.0

These files are used by Google Closure Compiler to:
- Prevent renaming of Baidu Map API symbols (`BMap`)
- Preserve calls to the map API during advanced compilation

No runtime code is included.

