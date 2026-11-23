# Model licenses

Luminara does not include any voice model or audio tool. Each one is downloaded from Hugging Face
when you install it, under its own license. This folder keeps a copy of each license as it was on
2026-11-23, with notes where the conversion Luminara downloads and the original model differ.
The license on the model's Hugging Face page is the one that applies.

This is not legal advice. Read the license before you use a model's audio for anything beyond
personal listening.

## Voice models

| Model | License | Kind | Details |
|---|---|---|---|
| Kokoro | Apache-2.0 | Permissive | [kokoro.md](kokoro.md) |
| Soprano | Apache-2.0 | Permissive | [soprano.md](soprano.md) |
| Spark | CC-BY-NC-SA-4.0 | Non-commercial | [spark.md](spark.md) |
| Chatterbox | Apache-2.0 | Permissive | [chatterbox.md](chatterbox.md) |
| Marvis | Apache-2.0 | Permissive | [marvis.md](marvis.md) |
| OuteTTS | CC-BY-NC-SA-4.0 + Llama 3.2 | Non-commercial | [outetts.md](outetts.md) |
| CSM | Apache-2.0 | Permissive | [csm.md](csm.md) |
| Dia | Apache-2.0 | Permissive | [dia.md](dia.md) |
| Ming-3.0 | MIT | Permissive | [ming-3.md](ming-3.md) |
| Qwen3-TTS | Apache-2.0 | Permissive | [qwen3-tts.md](qwen3-tts.md) |
| Orpheus | Apache-2.0 + Llama 3.2 | Permissive, with Llama terms | [orpheus.md](orpheus.md) |
| Maya | Apache-2.0 | Permissive | [maya.md](maya.md) |
| Breeze TTS 2 | BreezeBlue Research and Non-Commercial | Non-commercial | [breeze-tts-2.md](breeze-tts-2.md) |
| Drama 3 (4-bit) | Fish Audio Community License | Non-commercial; commercial only under USD 500,000 annual revenue | [drama-3-4bit.md](drama-3-4bit.md) |
| Drama 3 | Fish Audio Community License | Non-commercial; commercial only under USD 500,000 annual revenue | [drama-3.md](drama-3.md) |

## Audio tools

| Tool | License | Kind | Details |
|---|---|---|---|
| Qwen3 voice copying | Apache-2.0 | Permissive | [qwen3-voice-copying.md](qwen3-voice-copying.md) |
| Whisper Large V3 Turbo | MIT | Permissive | [whisper.md](whisper.md) |
| Parakeet TDT | CC-BY-4.0 | Permissive, with attribution | [parakeet.md](parakeet.md) |
| Qwen3-ASR | Apache-2.0 | Permissive | [qwen3-asr.md](qwen3-asr.md) |
| VibeVoice-ASR | MIT | Permissive | [vibevoice-asr.md](vibevoice-asr.md) |
| Qwen3 Forced Aligner | Apache-2.0 | Permissive | [qwen3-forced-aligner.md](qwen3-forced-aligner.md) |
| MossFormer2 SE | Apache-2.0 | Permissive | [mossformer2.md](mossformer2.md) |
| SAM-Audio Large | Meta SAM License | Royalty-free, with use restrictions | [sam-audio.md](sam-audio.md) |

## Extra files some voice models download

Some voice models download parts of other repositories with them: an audio codec, or a
tokenizer. These are their licenses. OuteTTS also downloads tokenizer files from its original
model, and Maya from Orpheus; those are covered by [outetts.md](outetts.md) and
[orpheus.md](orpheus.md).

| Download | Used by | License | Kind | Details |
|---|---|---|---|---|
| S3TokenizerV2 | Chatterbox | Apache-2.0 | Permissive | [extra-s3tokenizer-v2.md](extra-s3tokenizer-v2.md) |
| Moshi audio codec (Mimi) | Marvis, CSM | CC-BY-4.0 | Permissive, with attribution | [extra-moshiko.md](extra-moshiko.md) |
| DAC speech codec | OuteTTS | CDLA-Permissive-2.0 | Permissive | [extra-dac-speech.md](extra-dac-speech.md) |
| Llama 3.2 1B tokenizer | CSM | Llama 3.2 Community License | Free to use, with Meta's terms | [extra-llama-3.2-1b.md](extra-llama-3.2-1b.md) |
| Descript audio codec (44 kHz) | Dia | MIT | Permissive | [extra-descript-audio-codec.md](extra-descript-audio-codec.md) |
| SNAC audio codec (24 kHz) | Orpheus, Maya | MIT | Permissive | [extra-snac.md](extra-snac.md) |

## Language models

Luminara does not download a language model. With LM Studio or Ollama you download and load
the model yourself, and its own license applies. If you have one of these in LM Studio,
Luminara chooses it ahead of the others, in this order:

| Model | License | Kind | Details |
|---|---|---|---|
| Qwen3 14B | Apache-2.0 | Permissive | [qwen3-14b.md](qwen3-14b.md) |
| QwQ 32B | Apache-2.0 | Permissive | [qwq-32b.md](qwq-32b.md) |
| Llama 3.3 70B | Llama 3.3 Community License | Free to use, with Meta's terms | [llama-3.3-70b.md](llama-3.3-70b.md) |

A cloud provider's models are not licensed to you; they are a service, used under the terms
of your account with that provider:

| Provider | Terms |
|---|---|
| Anthropic | [Commercial Terms of Service](https://www.anthropic.com/legal/commercial-terms) |
| OpenAI | [Services Agreement](https://openai.com/policies/services-agreement/) |
| MiniMax | [Terms of Service](https://www.minimax.io/platform/protocol/terms-of-service) |
| Z.AI | [Terms of Use](https://docs.z.ai/legal-agreement/terms-of-use) |
