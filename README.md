# HotelVALORA · Gemini CLI extension

Connects [Gemini CLI](https://github.com/google-gemini/gemini-cli) to the HotelVALORA MCP server
(`https://www.hotelvalora.com/api/mcp`): institutional hotel valuations, comp sets and market data for Madrid
and New York, what-if scenarios and goal-seek.

```bash
gemini extensions install https://github.com/HotelVALORA/hotelvalora-mcp
```

Then, inside Gemini CLI, sign in with your HotelVALORA account:

```
/mcp auth hotelvalora
```

Access needs a HotelVALORA Premium plan or above (a demo connector without an account is described on the same page).
The same server works in Claude, ChatGPT and other MCP clients — see https://www.hotelvalora.com/ai.
This repository only holds the extension manifest; the platform itself is not open source.
