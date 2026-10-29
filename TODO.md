# TODO

- [ ] Consider adding discussion board items (for example, threaded responses to the readings) as graded participation.  Supporting them means updating the course tooling and its associated skills (`ursinus_canvas.py`, `ursinus_canvas_inline_changes.py`, `ursinus_canvas_update_schedule_inplace.py`, `canvas_sync_rubrics.py`, and the Ursinus Canvas deploy and course-generation skills) so that discussion topics can be created automatically from the syllabus, filed in the day's module, and graded against a rubric.

- [ ] Simplify the language across the course so each page is concise and easy to scan:
  - **Syllabus table:** shorten the wording in the schedule table (titles, reading entries, and deliverable descriptions) to the minimum a student needs; move any longer explanation to the linked page instead of the table.
  - **Assignments:** tighten the assignment pages' wording. Where an assignment has multiple parts or multiple options (for example, a choice of tracks, topics, or deliverables), give each part or option its own page and link to it from the parent assignment page, so no single page has to carry all of them.
  - **Lecture decks:** simplify the language in the LiaScript decks (shorter sentences, fewer asides per slide), and split any deck that covers several distinct topics into focused decks that the syllabus links to individually.
  - When splitting pages, keep the syllabus `dlink` / `rlink` entries, the Canvas deploy (`ursinus_canvas.py` and the inline-change script), and the rubric `rubricpath` references pointing at the right pages, and update the Canvas shell with a dry-run-first inline change if titles or links move.

- [ ] Instructional design pass on the notes and LiaScript templating: restructure the notes pages for learning (objectives up front, worked examples, short checks for understanding, consistent layout) and improve the LiaScript templates (shared macros and reusable components, consistent deck structure) so new and existing decks stay consistent. (added 2026-10-29)
