# Create Text only for teleprompter {script-path}

## Parameters

| Parameter | Required | Default | Description                  |
|-----------|----------|---------|------------------------------|
| $1        | Yes      | none    | path to the script markdown  |

If $1 is missing, ask for it before doing anything else.

## Steps

1. Take the script at $1 and pull out only the spoken script text.
2. Strip every visual cue, on-screen text reference and direction. Spoken words only.
3. Save it alongside the original, with the original filename plus `-script`.
