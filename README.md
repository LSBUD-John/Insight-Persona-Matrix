# LSBUD Insight Linked Library - fixed paths

This build links completed PDF files from the Library and from persona recommendations.

Fixes:

- Fetches root `personas.json` and `library.json` first, with `/data` fallback.
- Adds Download PDF buttons to library cards and detail panels.
- Adds PDF links inside persona and engine recommendations.

Required PDF filenames in repo root:

- `LSBUD_Insight_Safe_Digging_Essentials.pdf`
- `LSBUD_Insight_Do_I_Need_a_Utility_Search.pdf`
