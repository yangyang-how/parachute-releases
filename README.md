# parachute — releases

Signed, notarized builds of **parachute**, a local-first job-search tool.

This repository holds releases only. There is no source here; it lives
elsewhere and is private. The repository is public so that the app can check
for a new build and download it without carrying any credential.

## Installing

Download the `.dmg` from [the latest release](../../releases/latest), open it,
and drag **parachute** into Applications. Apple silicon Macs.

After that, parachute checks here itself and offers the next build with a
press. It refuses to install anything that is not notarized and signed by
`Developer ID Application: Shuang Wu (Z545Z47M5H)`.

## What it needs

Claude Code, installed and signed in on the same machine. parachute ships no
model and sends nothing anywhere — it asks the Claude you are already signed
in to. Without it the app still finds jobs and still prints documents; the
scores, the wording and the posting analysis are what wait.
