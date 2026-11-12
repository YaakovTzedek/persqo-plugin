# Persqo for Cursor and Grok Bot

Run AI user-agents on your website or web app. Get findings, screenshots, and a fix prompt for each issue.

This plugin points Cursor at the hosted Persqo MCP server and lets the client run the ordinary OAuth redirect. No API keys belong in this repository.

- Website: https://persqo.com
- Docs: https://persqo.com/docs/mcp
- Privacy: https://persqo.com/privacy
- Terms: https://persqo.com/terms
- Support: hello@persqo.com

## Install (Cursor / Grok Bot)

1. Install this plugin from the Cursor marketplace once it is listed, or add the MCP URL below as a custom remote server.
2. When prompted, sign in with your Persqo account (OAuth 2.1, PKCE). Approve the requested scopes.
3. Ask one of the example prompts in a new chat.

Remote MCP URL (Streamable HTTP): `https://persqo.com/api/mcp`


## Example prompts

- Test the signup flow on https://persqo.com and tell me what breaks.
- List my Persqo projects and show the open findings from the latest run, highest severity first.
- Give me the fix prompt for the top finding.
- Show the report for my last run with the score explained.
- Mark the footer Terms finding as fixed and retest it.

## License

MIT. See LICENSE.

## Maintainer

Yaakov Tzedek. This repository is only the plugin wrapper (manifest + MCP pointer + logo). It does not contain account credentials.
