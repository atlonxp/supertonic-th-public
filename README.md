# Supertonic 3 for Thai 🇹🇭

**Lightning-fast, on-device, multilingual TTS — 32 languages, now including Thai, running natively via ONNX.**

_Created by **Watthanasak Jeamwatthanachai**, PhD · EMBA · C\|CISO_

We added **Thai** as the **32nd language** to [Supertone's Supertonic 3](https://huggingface.co/Supertone/supertonic-3) — joining its 31 existing languages **without degrading any of them**. The samples below showcase seamless **Thai ⇄ English code-switching** in a single utterance, on-device via ONNX.

This repository is a **showcase**: listen to the samples below. An interactive demo is coming soon.

> ### 🔊 [**▶ Play the samples inline on the showcase page →**](https://atlonxp.github.io/supertonic-th-public/)
> Best experience with built-in audio players. The links below also work (each opens GitHub's player on the file page).

---

## 🎧 Listen

Every clip below speaks the **same mixed Thai + English line**:

> สวัสดีครับ ผมชื่อสมชาย และผมชอบเรียนภาษาไทย — *A gentle breeze moved through the open window while everyone listened to the story.*

| Voice | 🇹🇭 Thai-native (`th`) | 🇬🇧 English-native (`en`) | 🌐 Neutral bilingual (`na`) |
|---|---|---|---|
| **F1** (female) | [▶ play](samples/th_F1.wav) | [▶ play](samples/en_F1.wav) | [▶ play](samples/na_F1.wav) |
| **M1** (male)   | [▶ play](samples/th_M1.wav) | [▶ play](samples/en_M1.wav) | [▶ play](samples/na_M1.wav) |
| **F3** (female) | [▶ play](samples/th_F3.wav) | [▶ play](samples/en_F3.wav) | [▶ play](samples/na_F3.wav) |

_For inline players, open the **[showcase page](https://atlonxp.github.io/supertonic-th-public/)**._

---

## 🗣️ Language modes

The same model speaks the same text three ways — pick whichever sounds most natural for your use case:

- **`th`** — Thai-native speaker. Thai is flawless; English carries a light Thai accent.
- **`en`** — English-native bilingual. English is flawless; Thai carries a light English accent.
- **`na`** — neutral bilingual. Cleanest "professional bilingual" delivery across both languages.

---

## ✨ What works

- ✅ **32 languages** — all 31 of Supertonic 3's original languages preserved, with Thai added as the 32nd.
- ✅ **Adding Thai degraded none** of the original languages — they remain at native quality.
- ✅ **Thai + English in a single utterance** — natural code-switching, no stitching.
- ✅ **Multiple voices** — male and female, with voice identity preserved across languages.
- ✅ **On-device** — runs natively via ONNX, no cloud required.
- ✅ **44.1 kHz** output.

---

## 🚀 Interactive demo

Coming soon — a live, in-browser demo where you can type your own Thai/English text and hear it. _(This section will be updated once the demo is hosted.)_

---

## 📄 About & license

Created by **Watthanasak Jeamwatthanachai**, PhD · EMBA · C\|CISO.

Built on top of [Supertonic 3](https://huggingface.co/Supertone/supertonic-3) by [Supertone Inc.](https://supertone.ai) The base model is released under **OpenRAIL-M**. The audio in this repository consists of outputs from our Thai-adapted model and is provided for demonstration under the terms in [`LICENSE`](LICENSE).
