# Natural Science Learning Design

A Vietnamese-language learning-design review plugin and Custom GPT knowledge package for lower-secondary Natural Science teachers. It supports CBCI, KUD, Structure of Knowledge, IBL, student-centred learning experiences, assessment alignment and differentiation while preserving teacher agency.

## Conversation starters

1. Review My Learning Design
2. KUD & Structure of Knowledge
3. Suggestions Using IBL

## Use in Codex

The Codex plugin manifest is in `.codex-plugin/plugin.json`. The skill entrypoint and reference materials are under `skills/review-khtn-lesson-plan/`.

## Use as a Custom GPT on ChatGPT web

1. Create a GPT named `Natural Science Learning Design`.
2. Paste `custom-gpt/GPT_INSTRUCTIONS.md` into the GPT Instructions field.
3. Upload the Markdown files in `skills/review-khtn-lesson-plan/references/` as Knowledge.
4. Add the three conversation starters shown above.
5. Test with a non-sensitive sample lesson plan before making the GPT public.

The source package does not include the original PDFs used during development. Review copyright, privacy and institutional requirements before uploading additional source documents or lesson plans.
