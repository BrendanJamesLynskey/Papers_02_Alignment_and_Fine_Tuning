# Papers 02 — Alignment & Fine-Tuning

A single-page presentation deck indexing the five publications that turned base language models into aligned, instruction-following assistants — and made fine-tuning them affordable. It covers **InstructGPT** (Ouyang et al., 2022) and its canonical three-stage RLHF recipe (SFT → reward model → PPO with a KL penalty), Anthropic's **Constitutional AI** (Bai et al., 2022) and its move from human to AI feedback (RLAIF) guided by a written constitution, **LoRA** (Hu et al., 2021) and the low-rank weight update ΔW = B·A that cut trainable parameters by orders of magnitude with no inference penalty, **QLoRA** (Dettmers et al., 2023) with 4-bit NF4 quantisation that fine-tunes a 65B model on a single 48GB GPU, and **DPO** (Rafailov et al., 2023), which collapses the whole RLHF loop into one stable classification-style loss on preference pairs. Each paper gets the problem, the contribution, an engineer's-eye view of why it matters, a tailored diagram or code snippet, and a callout on the gotchas.

**Live site:** https://brendanjameslynskey.github.io/Papers_02_Alignment_and_Fine_Tuning/

Part of the [Key LLM Publications sub-hub](https://github.com/BrendanJamesLynskey/LLM_Hub_Key_Publications)
