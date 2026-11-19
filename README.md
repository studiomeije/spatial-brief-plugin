# The Spatial Brief

The Spatial Brief helps developers, analysts, and researchers explore Apple Vision Pro and visionOS. Search a curated archive of released apps, companies, public professional profiles, and news. Compare entries and write research briefs that link to the original sources. The archive covers selected public material, so some relevant apps and stories may be missing.

The plugin includes one remote MCP server at `https://thespatialbrief.com/api/mcp` and the Spatial Brief research skill, which helps your assistant find and cite archive sources.

## Install

- **Claude Code:** run `/plugin marketplace add studiomeije/spatial-brief-plugin`, then `/plugin install spatial-brief@studiomeije`. Open `/mcp`, select The Spatial Brief server, and sign in.
- **Codex:** run `codex plugin marketplace add studiomeije/spatial-brief-plugin`, then `codex plugin add spatial-brief@studiomeije`, and follow the sign-in prompt.

You can also [connect the MCP server directly](https://thespatialbrief.com/mcp) in Claude, Claude Code, ChatGPT, or Codex.

## Permissions and data

A Spatial Brief account is required; you can create one when you sign in. The plugin sends tool requests, such as search terms, filters, and submission details, only to `thespatialbrief.com`. Sign-in goes through The Spatial Brief’s OAuth provider, Supabase. The server uses your account ID to authorize requests and does not read your conversation history.

The consent screen defaults to read-only access. If you allow submissions, the assistant can send public links for curator review and App Store links for native visionOS apps. A submitted app is checked against the App Store; eligible apps are added to the archive automatically and unclear cases go to a curator. The submission tools cannot edit or delete archive entries. The Spatial Brief stores submissions and their review status. You can revoke access or create an MCP key for clients without OAuth in [MCP account settings](https://thespatialbrief.com/account/mcp).

## Documentation and support

- [Setup guide and tool reference](https://thespatialbrief.com/mcp)
- [Privacy Policy](https://thespatialbrief.com/privacy)
- [Terms of Service](https://thespatialbrief.com/terms)
- [Data Policy and corrections](https://thespatialbrief.com/data-policy)
- [Email support](mailto:thespatialbrief+support@studiomeije.com)
- [MIT license](LICENSE) for the plugin files
