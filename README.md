# What is WayStation
<img src="https://waystation.ai/images/logo.svg" width="50" align="left"/> [WayStation](https://waystation.ai) connects Claude Desktop, ChatGPT and any MCP host with the productivity tools you use daily such as Notion, Monday, Airtable, Jira etc. through a no-code, secure integration hub. 

***The original local WayStation MCP server has been deprecated in favor of the new remote MCP server hosted at https://waystation.ai/mcp. Please refer to the new WayStation MCP server documentation here***

## Hosted deployment

A hosted deployment is available on [Fronteir AI](https://fronteir.ai/mcp/waystation-ai-mcp).

## Overview
WayStation MCP server is a universal remote MCP server that seamlessly connects Claude (and other clients) to a broad range of productivity tools, including Notion, Monday, AirTable, etc.

- WayStation MCP supports both Streamable HTTPS and SSE transports
- The default endpoint is https://waystation.ai/mcp. It does transport negotiation and authorization if necessary
- WayStation also provides preauthenticated individual endpoints like https://waystation.ai/mcp/Iddq66dIdkfARDNb3K. Any registered user can get one in their dashboard at https://waystation.ai/dashboard

## Supported providers
- WayStation supports the following productivity apps: [Notion](https://waystation.ai/connect/notion), [Monday](https://waystation.ai/connect/monday), [Asana](https://waystation.ai/connect/asana), [Linear](https://waystation.ai/connect/linear), [Atlassian JIRA/Confluence](https://waystation.ai/connect/atlassian), [Slack](https://waystation.ai/connect/slack), [Teams](https://waystation.ai/connect/teams), [Google Drive](https://waystation.ai/connect/gdrive) (including Docs and Sheets), [Office 365](https://waystation.ai/connect/office), [Airtable](https://waystation.ai/connect/airtable), [Miro](https://waystation.ai/connect/miro), [Intercom](https://waystation.ai/connect/intercom), [PayPal](https://waystation.ai/connect/paypal).
- Users can browse available integrations/providers in the [Integrations Marketplace](https://waystation.ai/marketplace)
- New integrations are added regularly based on customer requests or community contributions. If you have an integration request, please contact us at support@waystation.ai.
- Users can connect their apps in the [dashboard](https://waystation.ai/dashboard). The connection process may vary by app but generally involves OAuth2 authentication flow with some additional steps for certain apps.

## Supported AI apps
- WayStation remote MCP was tested with Claude, Cursor, Cline, WindSurf, and MCP-remote STDIO proxy provider
- For Claude, user should go into their Settings, then Integrations and click "Add Integration". Then enter "WayStation" as the Server Name and unique MCP URL from user's dashboard
- For Cline, user should simply go into the MCP Server screen, switch to the Remote Servers tab, enter "WayStation" as the Server Name and unique MCP URL from user's dashboard
- For Cursor, user should go to the Cursor Settings, MCP tab and click "Add new global MCP server". In mcp.json file user should add the entry for WayStation as following:
```json
"WayStation": {
      "url": "https://waystation.ai/mcp/<user_unique_id>"
}
```

## Use Cases
WayStation supports a variety of productivity and automation use cases listed below:
- [Project Management](https://waystation.ai/ai/project-management)
- [Task Automation](https://waystation.ai/ai/task-automation)
- [Meeting Summaries & Action Items](https://waystation.ai/ai/meeting-summaries)
- [Workflow Automation & Process Optimization](https://waystation.ai/ai/workflow-automation)
- [Resource & Capacity Planning](https://waystation.ai/ai/resource-capacity-planning)
- [Risk & Issue Management](https://waystation.ai/ai/risk-issue-management)
- [Reporting & Insights](https://waystation.ai/ai/reporting-insights)
- [Portfolio Management](https://waystation.ai/ai/portfolio-management)
- [Team Collaboration Assistant](https://waystation.ai/ai/team-collaboration-assistant)
- [Creative Production Management](https://waystation.ai/ai/creative-production-management)
- [Campaign Management](https://waystation.ai/ai/campaign-management)
- [Product Management & Roadmapping](https://waystation.ai/ai/product-management-roadmapping)
- [Product Launch Coordination](https://waystation.ai/ai/product-launch-coordination)
- [Operations Management](https://waystation.ai/ai/operations-management)
- [IT Project Coordination](https://waystation.ai/ai/it-project-coordination)
- [Project Intake & Triage](https://waystation.ai/ai/project-intake-triage)
- [Knowledge Management Integration](https://waystation.ai/ai/knowledge-management-integration)
- [Goal Tracking & OKR Alignment](https://waystation.ai/ai/goal-tracking-okr-alignment)
- [Compliance & Audit Trail Management](https://waystation.ai/ai/compliance-audit-trail)
- [Timeline & Deadline Optimization](https://waystation.ai/ai/timeline-deadline-optimization)
