# Paper Edit {script-path}

## Parameters

| Parameter | Required | Default | Description                  |
|-----------|----------|---------|------------------------------|
| $1        | Yes      | none    | path to the script markdown  |

If $1 is missing, ask for it before doing anything else.

## Steps

1. Use the `video-editor` skill to build a detailed paper edit from the script at $1.
2. Save it as a markdown file in the same folder as the script.
3. Match the spoken content to specific timecodes.
4. Recommend b-roll, motion graphics and visual transitions that support the narrative.
5. Add notes on tone, style and any important visual cues for post-production.

The finished paper edit should read as a clear blueprint for the editor: what appears on screen, and when, based on the pacing and structure of the script.
