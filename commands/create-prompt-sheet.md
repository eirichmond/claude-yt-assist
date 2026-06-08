# Create Prompt Sheet {script-path}

## Parameters

| Parameter | Required | Default | Description                  |
|-----------|----------|---------|------------------------------|
| $1        | Yes      | none    | path to the script markdown  |

If $1 is missing, ask for it before doing anything else.

## Steps

1. Use the `bullet-point-teleprompter-architect` skill to convert the script at $1 into a Talking Point Sheet.
2. Save it alongside the original, with the original filename plus `-talking-point-sheet`.
3. Strip the written fluff and keep only the skeleton beats.
4. Keep each line short enough to read at a glance, without scanning left to right.

## Example

Original script line:

> "So, today I really want to talk to you guys about why it's super important to stay hydrated during long filming sessions because your voice can actually get really raspy and it makes editing a total nightmare later on."

Talking Point Sheet output:

    💧 IMPORTANCE OF WATER

    • Prevent "raspy voice"

    • Save hours in editing

    • Keep energy high
