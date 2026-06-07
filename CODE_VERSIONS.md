# Code versions

このメモは、同じ `medical-student-study` リポジトリのローカルコピーを区別するための名前付けです。

## Codex公開最新版

- 英語名: `Codex latest publish copy`
- 日本語名: `Codex公開最新版`
- 場所: `/Users/tomohironakajima/My Drive/Python_Lesson/2026_Homepage/medical-student-study`
- 状態: GitHub Pages に push 済みの最新版
- 最新コミット: `55d91c3 Add brain isolation technique page`
- 含まれる追加: `brain_isolation_technique.html`
- 公開URL: `https://ntath-git.github.io/medical-student-study/brain_isolation_technique.html`

## Claude元作業版

- 英語名: `Claude original working copy`
- 日本語名: `Claude元作業版`
- 場所: `/Users/tomohironakajima/My Drive/Python_Lesson/2026_MedicalStudent_Study`
- 状態: Claude が主に作っていた元のローカル作業コピー
- 確認時点の最新コミット: `f9f8ff6 Add AGENTS.md for cross-tool AI editing`
- 注意: `brain_isolation_technique.html` は未反映。`git pull` すると Codex latest publish copy と同じ最新版になります。

## 使い分け

- 公開サイトに反映する作業: `Codex公開最新版`
- 以前のClaude作業履歴・元作業場所の確認: `Claude元作業版`
- 今後は1つに統一するなら、`Claude元作業版` 側で `git pull` して最新版へ揃えるのが安全です。
