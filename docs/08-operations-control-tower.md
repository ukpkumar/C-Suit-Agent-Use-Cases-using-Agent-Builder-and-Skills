# 8) COO - Operations Control Tower

## Scenario

Provides a unified COO view across programmes, RAID, and operational KPIs with weekly report outputs and escalation-ready insights.

## Configuration

- **Name:** `Operations Control Tower`
- **Response mode:** Auto
- **Knowledge:** Programme/RAID SharePoint list, PMO status files, operations chat/meeting artifacts, People
- **Capabilities:** Code interpreter
- **Web search:** Off
- **Skills:** `raid-summary`, `weekly-ops-report`, `escalation-note`

## Instruction highlights

1. Group programmes by RAG; explain red/amber movement.
2. Show top risks by score and overdue mitigations.
3. Produce 12-week KPI trend charts against target.
4. Weekly report: headline, attention items, top risks, KPI snapshot, decisions requested.
5. Flag source conflicts instead of resolving silently.

## Starter prompts

- Which programmes are red/amber and why?
- List risks with overdue mitigations.
- Chart last 12 weeks KPI trends.
- Draft this week's operations report.

Back to [Index](INDEX.md)
