# Lettercress 1.0 TEST
Native Android Easy as ABC (ABC End View). These small boards are original generated layouts. Android 8+ (min 26), target 35. Package com.gg007.lettercress.

## Rules
Easy as ABC (ABC End View). In every row and column of the 4x4 board, put A, B and C exactly once each; the remaining cell stays blank. A letter outside the grid is the first letter seen from that side, ignoring blank cells. Missing edge clues impose no condition. No boxes, diagonals, numerical ordering or height visibility rule. Tap a tile to cycle blank,A,B,C,blank. Twelve original edge-only clue boards, unique among all 576 row/column-valid grids, with twelve distinct completions. Undo/reset/next/levels and saved letter palette/blank marks.

## Download and status
https://mega.co.nz/#!JBFz2LAa!vH9QhTy66PJTy6yCTUxgC9SV9MPbRDB0YPq8fbS7va0
APK SHA256 0c4dc1e401bc12d8b335beb3859b1d35a9a8007a94d7304798f0edecbbcbdf06; 16878 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous download bytes match.

## Checks
Exhausted all 331,776 combinations of four row permutations of blank,A,B,C. Independent frequency-count oracle agrees with production bitsets and recovers all 576 Latin completions. Independent reversed-list blank filtering checks edge clues against production directional index scans. All twelve edge-only boards (5-6 clues each) have one completion and all twelve solutions differ. Also checked 120,000 random/invalid arrays, null and invalid sizes/values, 768 single-cell solution mutations, bounds, full cycle to blank, solved lock and solve/undo/replay/reset. Archived portable generator reproduces levels.json and all-solutions.json; archived Java tests pass. Drawing adapter tests actual cell taps and gap taps, reset/undo/replay/next/levels/menu/settings/privacy and saved palette/blank marks/completion. Six drawing screens inspected, not phone screenshots. Phone runtime, performance and external-browser handoff QA remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Live 803-entry registry and semantic review of all 160 prior studio cards found no Easy as ABC match. Towerveil counts visible height records; Twincedar sums digits between blocks; Copperfield fills rooms with digits and a blank. Lettercress instead combines per-row/column ABC inventory with first-letter edge views ignoring blanks. Known Easy as ABC genre, not a global invention; origin not established. Rules https://wiki.logic-masters.de/index.php/As_easy_as_ABC/en and https://www.gmpuzzles.com/blog/2022/10/easy-as-abc-by-eric-fox/ agree on the general rule; Logic Masters explicitly gives ABC with one blank. No source puzzle copied; original generated clue boards. Recovered repository corpus remains partial.

## Build
JDK 17 and Android SDK 35/build-tools35.0.0. python generate-levels.py reproduces levels.json. Board.java embeds generated edge clues and solutions. javac -d /tmp/abc-test src/com/gg007/lettercress/Board.java BoardTest.java and java -cp /tmp/abc-test com.gg007.lettercress.BoardTest. bash build.sh creates an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private original signing inputs. No credentials in source. Release build settings, signed TEST artifact, not final store release.

## Privacy and branding
Lettercress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Letter palette, blank marks and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 icon byte-equal to original. Menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and websites
Complete source and APK privately preserved at https://files.instinct.com/1u7b5v5u1gfd-lettercress-source-archive, including exact cumulative 161-card studio and published catalog/studio sources/updater. Repository https://github.com/iLanis-agent/lettercress holds README only; full Git source commit pending. Both website publications checked separately. No Pages settings change or Play rollout. November 8, 2026.
