# IZIOS Precious Metals Price Widgets

Free, embeddable precious metals price widgets powered by LBMA (London Bullion Market Association) data.

## Features

- Real-time gold, silver, platinum, and palladium prices
- Historical price charts with multiple time periods (1M to All-Time)
- Light and dark themes
- Multiple units (oz, gram, kg)
- Mobile responsive
- No API key required

## Quick Start

### Historical Price Chart

```html
<div 
  data-widget="izios-metals-history" 
  data-metal="XAU" 
  data-period="1Y" 
  data-theme="light"
  data-unit="oz">
</div>
<script src="https://izios.com/widgets/metals-history.js"></script>
```

### Price Badge

```html
<div 
  data-widget="izios-metals-badge" 
  data-metal="XAU" 
  data-size="standard" 
  data-theme="light">
</div>
<script src="https://izios.com/widgets/metals.js"></script>
```

### Live Ticker

```html
<div id="izios-metals-widget" data-type="ticker" data-theme="light"></div>
<script src="https://izios.com/widgets/metals.js"></script>
```

## Configuration Options

### Metals
| Code | Metal |
|------|-------|
| `XAU` | Gold |
| `XAG` | Silver |
| `XPT` | Platinum |
| `XPD` | Palladium |

### Periods (Historical Chart)
`1M`, `3M`, `6M`, `1Y`, `2Y`, `5Y`, `10Y`, `ALL`

### Themes
`light`, `dark`

### Units
`oz` (troy ounce), `gram`, `kg`

### Badge Sizes
`compact`, `standard`, `showcase`, `wide`, `banner`

## Examples

See the `examples/` folder for complete HTML examples.

## Data Source

All price data is sourced from the [London Bullion Market Association (LBMA)](https://www.lbma.org.uk/), the global authority for precious metals pricing.

## Attribution

These widgets include "Powered by IZIOS" attribution which must remain visible per our terms of use.

## License

MIT License - Free for personal and commercial use.

## Links

- [Widget Builder](https://izios.com/developers/metals-widgets) - Interactive widget configurator
- [IZIOS](https://izios.com) - Lab-grown diamond marketplace
- [LBMA](https://www.lbma.org.uk/) - Data source
