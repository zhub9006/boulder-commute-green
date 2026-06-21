# Contributing

We welcome contributions to make this a better resource for Boulder's sustainable commuters!

## How to Contribute

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## Running a Commute Analysis

If you want to analyze your own commute:

1. Geocode your home and work addresses using the OSM Tools MCP
2. Use `osm-mcp-server_analyze_commute` with modes ["foot", "bike"]
3. Use `osm-mcp-server_get_route_directions` for both foot and bike modes
4. Add your results to the `commutes/` directory

## Community Guidelines

- Be respectful and inclusive
- Share only verified information
- Tag routes with relevant difficulty/accessibility notes
- Update data if routes change