# YouTube Workbench: free CapCut caption import evaluation

[Download Windows x64 evaluation](https://github.com/Results-First/youtube-workbench-evaluation/releases/tag/v0.1.1-eval.1)

**Full CapCut 9.5 compatibility remains unverified.** This update blocks import/export when root metadata identifies CapCut 9.5 and the root and selected nested drafts disagree. It does not guess which copy is authoritative or repair projects. The guard is tested with synthetic cases, not native 9.5 projects. Matching copies do not establish compatibility. Missing or unknown version metadata remains unqualified.

Preview captions from supported local CapCut project folders, load them into the Workbench editor, or export SRT plus a source record. No paid account, Python, CapCut installation, AI model or cloud service is needed for caption import.

1. Download the Windows ZIP from Releases and extract the entire folder.
2. Run YouTubeWorkbench-Evaluation.exe beside its _internal folder.
3. Click **Import CapCut captions** and select a copied project folder. Keep its Timelines subfolder intact.
4. Review the preview. Load captions into the editor or export into an empty folder.

The ZIP includes public sample projects, source for inspection, pinned dependencies, third-party notices and a repeatable full-app check. See EVALUATION-README.txt inside.

## Evaluation scope

Plaintext text tracks only. Active timeline selection is verified on the included 8.7 sample. Missing timestamps block import rather than being guessed. Repeated, numeric and multiline captions are preserved.

Qualified samples: CapCut 8.7 active timeline imports one caption. A public tool-generated/app-opened JianYing 9.0 sample correctly blocks because a cue lacks a start time. This is not a general compatibility guarantee or a claim that we ran CapCut itself.

Encrypted-only projects, compounds and templates are unsupported. Video/audio are not imported. Captions are not added to the searchable library. The import-dialog export preserves original captions, not subsequent editor edits. Other Workbench AI/TTS/YouTube features have separate requirements and are outside this evaluation.

## Verification

The conflict-guard update passes 15 focused importer tests and 19 source full-app acceptance checks. Four acceptance checks exercise synthetic 9.5 matching/conflicting copies, disabled actions, unchanged editor content and unchanged source files. Release verification results are recorded in the release notes and Actions. Automated checks substitute dialog responses. Prior native Windows picker testing applies to v0.1.0-eval.1, not a new manual test of this update. Independent consumer-device acceptance remains unverified.

This build is unsigned. Do not disable Windows security protections.

## Free evaluation and feedback

No payment, activation or expiry. Personal and business evaluation are allowed. This is not an open-source licence. See [evaluation grant](FREE-EVALUATION-LICENSE.txt).

Report your CapCut version, Windows version, expected captions and actual result in Issues. Share only redacted project copies you are authorized to publish. Do not upload private media or account credentials.

Not affiliated with or endorsed by CapCut.
