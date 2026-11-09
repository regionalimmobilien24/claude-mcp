# heyRegio – Regionalimmobilien24

heyRegio connects Claude to the real estate platform [regionalimmobilien24.de](https://www.regionalimmobilien24.de/).
It uses one remote MCP server, `https://mcp.regionalimmobilien24.de/mcp`, which needs no login.

## What you can do

- Search current listings for rent or sale by location, price, rooms, property type and features.
- Open a listing and read its key facts, costs, areas and the responsible agent.
- Find schools, supermarkets, doctors or public transport near a property (Google Places).
- Calculate a home-loan financing for a property and adjust price, loan amount and fixed-rate period.
- Get personalised, non-binding financing proposals based on income, employment and equity.
- Check free appointments of a financing advisor and book a consultation.
- Send a contact request about a listing to the agent.

## What data leaves your conversation

The plugin only sends data you have given and asked to be used. Depending on the action, this goes to:

- **regionalimmobilien24.de** (listing data, financing calculation, contact requests, session notes),
- **Europace**, the financing platform, via regionalimmobilien24.de (financing proposals and customer details such as date of birth, income and equity),
- **Calendly**, to read free appointments and to book the one you confirm (name, email, optional phone number),
- **Google Places**, to look up places near an address.

Financing proposals are calculated in a test mode: they are non-binding and create no live financing case.

## Example prompts

- "Show me 3-room apartments for rent in Zwickau up to 800 euros."
- "Find a house to buy in Plauen and calculate the financing with a 10 year fixed rate."
- "Which appointments does a financing advisor have next week?"

## Support

Regionalimmobilien24 GmbH – info@regionalimmobilien24.de – [Impressum](https://www.regionalimmobilien24.de/impressum/) – [Datenschutz](https://www.regionalimmobilien24.de/datenschutz/)
