# Create Idea {the-title} {keyword-one} {keyword-two} {narrative}

## Parameters

| Parameter   | Required | Default | Description   |
|-------------|----------|---------|---------------|
| $TOPIC      | Yes      | none    | the title     |
| $KEYWORD1   | Yes      | none    | keyword one   |
| $KEYWORD2   | Yes      | none    | keyword two   |
| $NARRATIVE  | Yes      | none    | the narrative |

If any of $TOPIC, $KEYWORD1, $KEYWORD2 or $NARRATIVE are missing, ask for them before doing anything else.

## Steps

1. Slugify $TOPIC: lowercase, spaces to hyphens, strip anything that isn't slug friendly.
2. Create a folder named with that slug.
3. Inside it, create a markdown file named with the same slug.
4. Use the `story-driven-youtube-seo-writer` skill (see `../skills/story-driven-youtube-seo-writer/PROFILE.md`) to write a concise script from $NARRATIVE, in the voice and tone of `../ELLIOTTRICHMOND.md`.
5. Using $KEYWORD1 and $KEYWORD2, produce a list of 5 optimised titles drawn from the Top 10 Queries in Google Trends (use `../skills/story-driven-youtube-seo-writer/reference.md` as the source). Include this list in the script.

Before writing, always use the AskUserQuestion tool to define:

- What do viewers want to know?
- What do viewers need to know?
- What do viewers not need to know?

## Outro

Append the outro from `../partials/outro.md` to the end of the script, verbatim.
