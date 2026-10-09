# DVIDIA

Open physical-AI skills: from human demonstrations toward installable robot skills.

[Official site](https://dvidia.org/) · [Research notebook](https://research.dvidia.org/) · [Hugging Face](https://huggingface.co/Dvidia)

## DVIDIA Training

![DVIDIA Training — toward installable robot skills. Open source, offline, CPU.](https://raw.githubusercontent.com/Dvidia-Inference/dvidia-training/main/assets/branding/github-header.png)

Train locally from Skillspace footage on your computer or server. The open-source pipeline checks videos, keeps related recordings together, fits small CPU models, and exports inspectable results. Training runs offline after the software and data are installed; this learner requires no GPU.

[Install locally](https://github.com/Dvidia-Inference/dvidia-training/blob/main/docs/installation.md) · [Hardware guide](https://github.com/Dvidia-Inference/dvidia-training/blob/main/docs/hardware.md) · [Recorded demo](https://huggingface.co/spaces/Dvidia/dvidia-training)

[Source code](https://github.com/Dvidia-Inference/dvidia-training) · [Synthetic datasets](https://huggingface.co/datasets/Dvidia/dvidia-training-examples) · [Pilot models](https://huggingface.co/Dvidia/dvidia-training-pilot) · [Frozen benchmark evidence](https://github.com/Dvidia-Inference/dvidia-training/releases/tag/benchmark-2026-10-08)

**Research alpha.** Visual prediction and robot movement are separate claims. Movement training requires aligned numerical actions and a supported simulation adapter. The demo presents the original one-scene recorded pilot; the separate sample-count benchmark tests installed candidates in twelve simulated layouts. Human-video action recovery and physical-arm qualification remain open research tasks.

## Follow the research

We publish methods, reproducible inputs, measured outcomes, controls, and failures in the [research notebook](https://research.dvidia.org/). Start with the [footage-training pipeline and frozen sample-count follow-up](https://research.dvidia.org/papers/skillspace-footage-training/), or inspect the [research source and revisions](https://github.com/Dvidia-Inference/dvidia-research).

To contribute, see the [training contribution guide](https://github.com/Dvidia-Inference/dvidia-training/blob/main/CONTRIBUTING.md) or the [research contribution guide](https://github.com/Dvidia-Inference/dvidia-research/blob/main/CONTRIBUTING.md).

Open-weight inference and hardware research live with our sister product, [OW Terminal](https://owterminal.com/).

[hello@dvidia.org](mailto:hello@dvidia.org) · [X · @iammrriver](https://x.com/iammrriver)
