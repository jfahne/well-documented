# Item 0: Story 0: Identify Calendar Format Options

## Stakeholder Context

Maintainers need a list of options to consider for an ADR on how to represent calendar and Gantt charts.

## Technical Context

Any solution chosen must be a plain text format and is ideally well supported by git VCS tools.

## Acceptance Criteria

- [ ] A list of plain text calendar formats or approaches

## Approach

- Search for existing formats
- Consider sleight variations on the format
- Explicitly do not concoct a new format (this is scope for a future ticket)

## Brainstorming

* [calendar.txt](https://www.terokarvinen.com/2021/calendar-txt)
* [mdcal](https://www.github.com/pn11/mdcal)
* Calendar as CSV. Gantt as Mermaid.
* Calendar as MD table. Gantt as Mermaid.
