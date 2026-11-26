# dinsesh-builds

Small tools that run on your machine. No signup, no upload.

The ASL reader is the one I would try first. It reads 36 fingerspelling signs from a webcam, in the browser: https://dinsesh-builds.github.io/asl-sign-language/

While training it I got two things wrong. I mirrored the camera feed on one path and not the other, so K and P came out backwards. I also augmented the data before splitting, which put near copies of the same frame on both sides. SplitGuard found 416 test rows out of 2155 with a near duplicate in train. Both bugs are fixed and written up in the repo.

HandGate came out of the same project. It smooths landmarks before the classifier sees them, and has its own page: https://dinsesh-builds.github.io/handgate/

Tools:

- [SplitGuard](https://github.com/dinsesh-builds/splitguard) checks a train/test split for near duplicates.
- [PrivacyLint](https://github.com/dinsesh-builds/privacylint) scans a folder for secrets and old commit emails. It reports locations, never the values.
- [RepoHealth](https://github.com/dinsesh-builds/repohealth) checks a public repo against fourteen boring but useful items. All six of my repos now score full marks.
- [HandGate](https://github.com/dinsesh-builds/handgate) does the landmark smoothing mentioned above.

Older projects:

- [asl-sign-language](https://github.com/dinsesh-builds/asl-sign-language), the one with the bugs.
- [exam-reminder-ai](https://github.com/dinsesh-builds/exam-reminder-ai), turns notes into practice questions and shows the source sentence under each one.
- [RegainPlus](https://github.com/dinsesh-builds/RegainPlus), an offline Android focus app. Still being built, so expect rough edges.

If you find a bug, open an issue on that repo. I read them there.

I keep this under a handle. No name, no email, no linked accounts.
