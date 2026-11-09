# HotelVALORA

HotelVALORA is a hotel intelligence and valuation platform. The `hotelvalora` MCP server gives you the same
institutional engine as the web report and Valeria, the platform's analyst: valuation (Hotel Market Value =
EBITDA after Replacement / Dynamic Cap Rate), 12-month and 5-year P&L, competitive set and market data.
Coverage today: Madrid and New York.

Sign in once with `/mcp auth hotelvalora` (OAuth with your HotelVALORA account). The MCP server is part of the
Premium plan and above; a demo connector without an account is described at https://www.hotelvalora.com/ai.

## Tools
- `search_assets` — find a hotel by name or address.
- `get_asset` — the hotel's profile (class, keys, submarket, amenities).
- `get_report` — the valuation report (value, range, P&L, returns).
- `get_compset` — the hotel's competitive set.
- `get_market` — market and submarket figures (ADR, occupancy, RevPAR, transactions).
- `adjust_scenario` — what-if: change purchase price, ADR, occupancy, CAPEX, debt, P&L ratios… and get the new value.
- `goal_seek` — solve for the price or ADR that hits a target IRR, MOIC or DSCR.
- `export_report` — PDF of the report.
- `list_own_usage` — your plan's usage.

## Good questions
- "Value the Hotel Urban in Madrid and show its comp set."
- "What if the purchase price is €55M and ADR rises 8%?"
- "What price gives a 12% levered IRR?"
- "Compare ADR and occupancy of upper upscale hotels in Midtown Manhattan."

Figures are estimates from the platform's engine, not a certified appraisal. Madrid in euros, New York in dollars.
More: https://www.hotelvalora.com/ai · https://www.hotelvalora.com/llms.txt
