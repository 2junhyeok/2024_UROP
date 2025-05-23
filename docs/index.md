---
title: "MimicBlocker: Self-Supervised Adversarial Defense for Voice Conversion"
layout: default
---

# MimicBlocker

Recent advances in one-shot voice conversion (VC) have significantly improved the ability to replicate speaker characteristics using only a single utterance. However, this progress also poses growing risks to speaker privacy. To counter this, **MimicBlocker** introduces a self-supervised adversarial training framework that injects imperceptible perturbations into raw audio, effectively **blocking speaker mimicry** in both black-box and white-box settings.

Our method is evaluated using state-of-the-art VC systems and demonstrates superior defense performance while preserving speaker identity.

---

## White-box Scenario (Cosine Similarity Loss)

> **Tip:** Headphones are recommended for best listening experience.

|   | Protected Input | Original Output | Adversarial Input | Adversarial Output |
|---|----------------|----------------|-------------------|--------------------|
| 0 | ![](samples/whitebox/14_0/ori_input.jpg) | ![](samples/whitebox/14_0/before.jpg) | ![](samples/whitebox/14_0/adv_input.jpg) | ![](samples/whitebox/14_0/after.jpg) |
|   | <audio src="samples/whitebox/14_0/ori_input.wav" controls></audio> | <audio src="samples/whitebox/14_0/before.wav" controls></audio> | <audio src="samples/whitebox/14_0/adv_input.wav" controls></audio> | <audio src="samples/whitebox/14_0/after.wav" controls></audio> |


---

## Black-box Scenario (Cosine Similarity Loss)

|   | Protected Input | Original Output | Adversarial Input | Adversarial Output |
|---|----------------|----------------|-------------------|--------------------|
| 0 | ![](samples/blackbox/1_0/ori_input.jpg) | ![](samples/blackbox/1_0/before.jpg) | ![](samples/blackbox/1_0/adv_input.jpg) | ![](samples/blackbox/1_0/after.jpg) |
|   | <audio src="samples/blackbox/1_0/ori_input.wav" controls></audio> | <audio src="samples/blackbox/1_0/before.wav" controls></audio> | <audio src="samples/blackbox/1_0/adv_input.wav" controls></audio> | <audio src="samples/blackbox/1_0/after.wav" controls></audio> |
