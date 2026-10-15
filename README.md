# YouTube Workbench: free CapCut caption import evaluation

[Download Windows x64 evaluation](https://github.com/Results-First/youtube-workbench-evaluation/releases/tag/v0.1.0-eval.1)

Preview captions from supported local CapCut project folders, load them into the Workbench editor, or export SRT plus a source record. No paid account, Python, CapCut installation, AI model or cloud service is needed for caption import.

1. Download the Windows ZIP from Releases and extract the entire folder.
2. Run YouTubeWorkbench-Evaluation.exe beside its _internal folder.
3. Click **Import CapCut captions** and select a copied project folder. Keep its Timelines subfolder intact.
4. Review the preview. Load captions into the editor or export into an empty folder.

The ZIP includes public sample projects, source for inspection, pinned dependencies, third-party notices and a repeatable full-app check. See EVALUATION-README.txt inside.

## Evaluation scope

Plaintext text tracks only. Active timeline selection avoids stale root captions. Missing timestamps block import rather than being guessed. Repeated, numeric and multiline captions are preserved.

Qualified samples: CapCut 8.7 active timeline imports one caption. A public tool-generated/app-opened JianYing 9.0 sample correctly blocks because a cue lacks a start time. This is not a general compatibility guarantee or a claim that we ran CapCut itself.

Encrypted-only projects, compounds and templates are unsupported. Video/audio are not imported. Captions are not added to the searchable library. The import-dialog export preserves original captions, not subsequent editor edits. Other Workbench AI/TTS/YouTube features have separate requirements and are outside this evaluation.

## Verification

114 regression tests and 15 full-app acceptance checks passed locally. Native Windows folder selection, export, import confirmation and Save were exercised. The exact public ZIP also passed all 15 checks and all 1,195 file hashes on [hosted Windows Server 2022](https://github.com/Results-First/youtube-workbench-evaluation/actions/runs/38669223001) and after a separate anonymous public download. Independent consumer-device acceptance remains unverified.

This build is unsigned. Do not disable Windows security protections.

## Free evaluation and feedback

No payment, activation or expiry. Personal and business evaluation are allowed. This is not an open-source licence. See [evaluation grant](FREE-EVALUATION-LICENSE.txt).

Report your CapCut version, Windows version, expected captions and actual result in Issues. Share only redacted project copies you are authorized to publish. Do not upload private media or account credentials.

Not affiliated with or endorsed by CapCut.
