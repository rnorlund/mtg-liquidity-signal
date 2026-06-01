# Disclaimer

The contents of this repository are provided **for informational and research
purposes only**. They are **not financial, investment, or trading advice**, and
nothing here should be construed as a recommendation to buy, sell, or hold any
trading card, collectible, or other asset.

## What this is

- A composite index that estimates how easily a Magic: The Gathering card could
  be converted to cash right now, based on public secondary-market prices: the
  dealer bid-ask spread, how many venues list the card, how often its price
  moves, and Commander-format demand.
- The model produces a relative score from 0 to 100, not a guarantee. A high
  score means the card has historically behaved like other cards that were easy
  to sell; it does not promise a buyer at any particular price or time.

## What this is not

- It is **not** a forecast of future card prices.
- It is **not** a measure of what a card is worth.
- It is **not** a substitute for your own judgment or for professional advice.
- It does **not** account for your individual financial situation,
  collection, tax position, or risk tolerance.

## Honest limitations

- This is version 1, a composite proxy index, not a supervised forecast. There
  is no public ground-truth label for "days to sale", so it carries no held-out
  accuracy score.
- It uses no true traded-volume or listing-count data. Spread, price staleness,
  and venue breadth are stand-ins for market depth and trading velocity.
- Buylist (dealer bid) coverage is CardKingdom-only and United States centric.
  Cards without a dealer bid have an imputed spread and are flagged accordingly.
- Collectible markets are genuinely illiquid and can have wide buy/sell spreads;
  transaction costs can be large, which is exactly what this index tries to make
  visible.

## No warranty

Outputs in this repository are provided "as is", without warranty of any
kind, express or implied, including but not limited to warranties of
merchantability, fitness for a particular purpose, accuracy, or
non-infringement. **The authors accept no liability** for losses, missed
gains, or any other damages arising from use of this material.

Cards and game terminology are property of Wizards of the Coast LLC. This
project is not affiliated with, endorsed by, or sponsored by Wizards of the
Coast.

By Cameraderie Cards.
