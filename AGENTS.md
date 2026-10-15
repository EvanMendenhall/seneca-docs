# Documentation project instructions

This is the Mintlify site for the Seneca Research Platform.

- Pages are MDX files with YAML frontmatter.
- Configuration lives in `docs.json`.
- The API reference is generated from `https://seneca-research.fly.dev/v1/openapi.json`. Do not hand-copy request and response schemas.
- The public panels are `wide`, `consensus`, and `seneca`. Do not document Quick Pulse as a product. `quick_pulse_unavailable` is only the error for a retired panel id.
- Document the operational REST API. Also document MCP, which is an operational integration at `https://mcp.seneca.professionalaiagents.com/mcp` over Streamable HTTP. Tool names, the Cursor client configuration, and credit behavior come from the Seneca Developers page. Do not invent tools, and do not publish unverified client setup.
- Do not add pages for interfaces that are not operational. A2A is not available.
- Use active voice and second person. Use sentence case for headings.
- Keep API keys out of examples. Use `$SENECA_API_KEY` or `seneca_sk_...` as a placeholder.
