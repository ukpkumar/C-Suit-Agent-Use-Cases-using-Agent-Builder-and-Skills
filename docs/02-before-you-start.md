# 2) Before You Start

## 2.1 Licensing and data access

Agent Builder is available in Microsoft 365 Copilot app (Work and Web), `microsoft365.com/chat`, and Teams desktop/web (not mobile).

| Capability / knowledge | Copilot Chat (no usage billing) | Copilot Chat (usage billing) | Microsoft 365 Copilot license |
|---|---|---|---|
| Instructions, code interpreter, image generator, web search | Yes | Yes | Yes |
| SharePoint, OneDrive, embedded files, connectors, Dataverse | No | Yes | Yes |
| Email, People, Teams messages, Teams meetings | No | No | Yes |
| Skills in Agent Builder | No | Pay-as-you-go | Yes |

All agents in this guide assume executives have a **Microsoft 365 Copilot license**.

## 2.2 Limits to design around

| Item | Agent Builder limit |
|---|---|
| Agent name | 30 characters |
| Description | 1,000 characters |
| Instructions | 8,000 characters |
| Public website URLs | 4 |
| SharePoint files/folders/sites | 100 files |
| SharePoint lists | 1 list |
| OneDrive files | 50 files |
| Teams chats and meetings | 5 chats and 5 meetings |
| Uploaded files | 20 files |
| Skills per agent | 8 |
| Skill package size | `.zip` up to 50 MB |
| SKILL.md instructions | < 20,000 characters |
| External actions | Author in Copilot Studio (not Agent Builder) |

## 2.3 Preparation checklist

1. Confirm executive licensing and Agent Builder access.
2. Confirm tenant enablement for skills, connectors, Dataverse.
3. Prepare SharePoint libraries/lists and validate permissions/sensitivity labels.
4. Assign builders (Chief of Staff/EA/analyst) and executive testers.
5. Define pilot group and success metrics.

Back to [Index](INDEX.md)
