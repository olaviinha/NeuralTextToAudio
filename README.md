# Colab notebooks for text-to-audio generators

User-friendly Colab notebooks for various text prompt steered synthetic audio generators.

**Available notebooks:**

- [AudioLDM](https://colab.research.google.com/github/olaviinha/NeuralTextToAudio/blob/main/AudioLDM_pub.ipynb) – _text-to-audio_
- [TorToiSe TTS](https://colab.research.google.com/github/olaviinha/NeuralTextToAudio/blob/main/tortoise_tts_pub.ipynb) – _text-to-speech_
- [MubertAI Text-to-Music](https://colab.research.google.com/github/olaviinha/NeuralTextToMusic/blob/main/mubert_txt2music.ipynb) – _text-to-music_
- [TTS Voice Cloning](https://colab.research.google.com/github/olaviinha/NeuralTextToAudio/blob/main/TTS_voice_cloning_pub.ipynb) – _text-to-speech_

---

## AudioLDM: Text-to-Audio Generation with Latent Diffusion Models
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToAudio/blob/main/AudioLDM_pub.ipynb)

Paper: [Text-to-Audio Generation with Latent Diffusion Models](https://arxiv.org/abs/2301.12503)

Colab for [AudioLDM](https://github.com/haoheliu/AudioLDM). Generates audio based on text description. This is probably the beginning of _"Stable Diffusion of audio"_. Currently capable of producing 16 kHz audio only.

---

## TorToiSe: Text-to-speech
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToAudio/blob/main/tortoise_tts_pub.ipynb)

Paper: [TorToiSe - Spending Compute for High Quality TTS](https://docs.google.com/document/d/13O_eyY65i6AkNrN_LdPhpUjGhyTNKYHvDrIvHnHe1GA)

Colab for [TorToiSe](https://github.com/neonbjb/tortoise-tts) text-to-speech. This notebook takes a text string and an audio file (or files) of a speaker's voice, and attempt to synthesize the text using the given voice. Currently works with English text only.

---

## MubertAI Text-to-Music

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToMusic/blob/main/mubert_txt2music.ipynb)

Colab for [MubertAI Text-to-Music](https://github.com/MubertAI/Mubert-Text-to-Music). Generates music using predefined blocks created by the community (afaik) based on text description. See the [source repository](https://github.com/MubertAI/Mubert-Text-to-Music) for information, such as licensing.

---

## TTS Voice Cloning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralTextToAudio/blob/main/TTS_voice_cloning_pub.ipynb)

Paper: [Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis](https://arxiv.org/pdf/1806.04558.pdf)

Colab for [Real-Time-Voice-Cloning](https://github.com/CorentinJ/Real-Time-Voice-Cloning) text-to-speech. This notebook takes a text string and an audio file of a speaker's voice, and attempt to synthesize the text using the given voice. Fair warning: results are not great.
