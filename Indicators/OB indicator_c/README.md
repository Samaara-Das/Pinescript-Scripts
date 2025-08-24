## Order Block Indicator
Detects institutional supply/demand zones using price gaps (FVGs) and liquidity sweeps on TradingView. Tracks OBs (max 500, clears reversed after 50 bars) through active, tested, breaker, and reversed states. Toggles for bullish/bearish OBs/FVGs, extensions, and debug options.

**OBs**: Bullish (demand: blue/purple, tested: yellow, breaker: red, reversed: black); Bearish (supply: red/maroon, tested: green, breaker: blue, reversed: black). Borderless rectangles.
**FVGs**: Bullish (lime, above OB); Bearish (orange, below OB); Filled (gray, optional, labeled "Filled bullish/bearish FVG" if price fills x%—default 50%). Borderless, with optional dashed fill-level line.
**Logic**: OBs/FVGs identified on bar[2]/bar[3] via gap + sweep (bullish: upward gap below validation low + low sweep; bearish: downward gap above validation high + high sweep). FVGs filled if prior bar wicks x% into gap.
