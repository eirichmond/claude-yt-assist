# Create Feynman {the-title} {narrative}

## Parameters

| Parameter  | Required | Default | Description   |
|------------|----------|---------|---------------|
| $1         | Yes      | none    | the title     |
| $2         | Yes      | none    | the narrative |

If either $1 or $2 is missing, ask for them before doing anything else.

## Steps

1. Slugify $1: lowercase, spaces to hyphens, strip anything that isn't slug friendly.
2. Create a folder named with that slug.
3. Inside it, create a markdown file named with the same slug.
4. Use the `feynman-technique` skill to write a concise script from $2, in the voice and tone of `../ELLIOTTRICHMOND.md`.
5. Cherry pick keywords from $2 to optimise the titles and content, using `../skills/feynman-technique/reference.md` as the source.

## Outro

Append the outro from `../partials/outro.md` to the end of the script, verbatim.
