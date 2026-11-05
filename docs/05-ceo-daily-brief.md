# 5) CEO - Executive Daily Brief

## Scenario

Creates a concise morning brief from the CEO's own email, Teams, and meetings: decisions needed, escalations, meeting prep, follow-ups, and notable external updates.

## Configuration

- **Name:** `CEO Daily Brief`
- **Response mode:** Auto
- **Knowledge:** Email, Teams chats/meetings, People, ExCo/Strategy SharePoint, scoped web search
- **Capabilities:** Code interpreter + web search
- **Skills:** `daily-brief-format`, `meeting-prep-pack`, `exec-reply-drafter`

## Describe prompt

Use an executive-focused brief with source citations and daily prioritization by urgency and sender seniority.

## Instruction highlights

1. Output sections: Decisions, Escalations, Key Meetings, Follow-ups, News.
2. Max five items per section.
3. Every item must cite source (mail/chat/meeting).
4. Reply drafts: <=120 words, never auto-send.
5. Use local timezone with explicit dates.
6. Never invent details; protect private/confidential items.

## Starter prompts

- Give me my daily brief for today.
- Prepare me for my next meeting with a one-page note.
- Which direct reports are waiting on a decision from me?
- Summarize key decisions from this week's ExCo meetings.

## Test checklist

- Every bullet has a real source citation.
- Private items are handled discreetly.
- No auto-send behavior.

Back to [Index](INDEX.md)
