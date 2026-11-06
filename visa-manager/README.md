# Visa Manager

Use Visa Manager in Claude to read public Thailand visa guides, find guidance for a passport country, browse recent Thailand news and open Visa Manager services. This plugin includes a planning skill and a remote connector.

## Connect in Claude

Open Settings → Connectors → Add custom connector, name it Visa Manager, and use https://visamanager.io/api/mcp. This public connector requires no login. Your Claude plan and workspace settings determine whether you can add custom connectors.

## Install in Claude Code

Run these commands in Claude Code:

```
/plugin marketplace add happy-machine/visa-manager-plugins
/plugin install visa-manager@visa-manager-plugins
```

If already installed, update the marketplace and plugin before testing.

## Try it

- Find DTV guides and summarize the application checklist.
- Show the latest Thailand news with publication dates and source links.
- Find Thailand entry guidance for a British passport holder.

## Tools

The connector provides list_visa_guides, get_visa_guide, get_nationality_guide, list_news, read_news_article and get_service_link. All tools read public data. Website links handle applications, stay tracking and optional paid Visa Manager services.

## Privacy

Tool arguments can include a guide topic, country code, article slug, pagination cursor or service selection. They go to visamanager.io. The connector does not request documents, passport numbers, payment details or account credentials. Application code stores no conversation history or user records. Hosting infrastructure may retain operational request logs under the site privacy policy.

Read the [privacy policy](https://visamanager.io/privacy), [terms](https://visamanager.io/terms) and [setup documentation](https://visamanager.io/claude). Contact support@visamanager.io for help.

Visa rules depend on the individual situation and issuing authority. Verify published guidance with the relevant embassy or immigration office before acting.
