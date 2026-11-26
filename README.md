# dinsesh-builds

Local first tools for study, accessibility and focus. Everything here runs on your machine. No account, no upload, no API key.

## Try something live

- [ASL fingerspelling reader](https://dinsesh-builds.github.io/asl-sign-language/) reads 36 signs from a webcam in the browser.
- [HandGate demo](https://dinsesh-builds.github.io/handgate/) smooths hand landmarks with a confidence gate.

Both use your camera locally. Frames never leave the device.

## Tools

| Tool | What it does |
| --- | --- |
| [SplitGuard](https://github.com/dinsesh-builds/splitguard) | Finds near duplicates crossing a train/test split. Found 416 of 2155 rows in my ASL data. |
| [PrivacyLint](https://github.com/dinsesh-builds/privacylint) | Scans a folder for secrets, open CORS and old commit emails without printing the values. |
| [RepoHealth](https://github.com/dinsesh-builds/repohealth) | Checks a public repo against fourteen discovery and community items. |
| [HandGate](https://github.com/dinsesh-builds/handgate) | One Euro smoothing and confidence gating for MediaPipe landmarks. |

## Projects

| Project | What it does |
| --- | --- |
| [asl-sign-language](https://github.com/dinsesh-builds/asl-sign-language) | 36 ASL fingerspelling signs with MediaPipe, an SVM and ONNX. Python and browser. |
| [exam-reminder-ai](https://github.com/dinsesh-builds/exam-reminder-ai) | Turns notes and PDFs into practice questions with the source sentence shown under each one. |
| [RegainPlus](https://github.com/dinsesh-builds/RegainPlus) | Offline Android focus and study app. Still in development. |

## How I work

- Local first. Data stays on the device unless you export it.
- Honest limits in every README. The sign reader is practice, not an interpreter. The question tool makes drafts, not answers.
- A tool repo for every hard lesson. SplitGuard and HandGate came out of real bugs in the ASL project.
- Small dependencies and tests that fail for a real reason.

## Working with me

Open an issue on the repo you are using. Both finished projects and all four tools have issue forms, changelogs and contributing guides.

This account is kept under a handle on purpose. No personal details are published here.
