# ChatGPT に渡すプロンプト（背景キービジュアル用）

## 添付するもの
- 館内写真（マシンが並んでいる写真）1枚だけ
- ロゴ・外観写真は添付しない（あとでClaudeが正確な位置に載せる）

## プロンプト（コピペ用）

```
Edit the attached gym photo into a vertical poster background (portrait, 2:3, highest quality).

Purpose: a print poster for a real gym, posted at a school. Text will be added later by another tool, so:
- ABSOLUTELY NO text, letters, numbers, logos, watermarks or signs added anywhere.

Keep it real:
- Keep the gym interior, machines, dumbbells and benches exactly as in the photo. Do not add, remove or change any equipment. Do not add people.

Look & effects:
- Cinematic, high-contrast, premium sports-brand advertising style (think Nike / Under Armour key visual).
- Dark, moody grading with deep blacks; keep the red seats of the machines vivid.
- Accent color red (#E50213): add dynamic diagonal red light streaks / light beams sweeping across the image, subtle lens flare, light haze in the air, fine film grain, slight motion energy.
- Strong depth: foreground slightly darker, mid-ground machines lit by dramatic rim light.

Composition (important, leave space for text):
- Gym photo occupies the upper ~55% of the canvas.
- Top ~12%: darker area (logo will go there).
- Lower ~45%: smoothly fades into near-black (#0B0B0D) with only faint red light streaks, keeping it clean and calm so large text can sit on top.
```

## うまくいかない時の追加指示
- 文字が入ってしまった → 「文字・記号を完全に消して、それ以外は変えないで」
- マシンの形が変わった → 「元の写真の機材の形と配置を変えずに、色調と光の演出だけにして」
- 派手すぎ／地味すぎ → 「赤い光の筋を半分の強さに」／「赤い光の筋をもっと太く、斜めに2〜3本」

## 受け取ったら
生成画像（PNG）をそのままこのチャットに貼ってください。Claudeが文字・価格・外観写真・QR・許可印欄を載せてA3の印刷用PDFに仕上げます。
