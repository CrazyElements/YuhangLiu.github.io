# 📝 Featured Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='../../images/Bi-LoRA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Bi-LoRA: Efficient Sharpness-Aware Minimization for Fine-Tuning Large-Scale Models](https://openreview.net/forum?id=zoYPlgX1bH)

**Yuhang Liu**<sup>\*</sup>, Tao Li<sup>\*</sup>, Zhehao Huang, Zuopeng Yang, Xiaolin Huang

[**Code**](https://github.com/CrazyElements/Bi-LoRA)

This paper identifies a key gap in parameter-efficient fine-tuning: LoRA is memory-efficient but can generalize poorly, while a naive LoRA+SAM incurs two-step overhead with perturbations confined to a low-rank subspace, and introduces **Bi-LoRA**, a dual-adapter design that decouples perturbation modeling from task optimization to enable single-backward sharpness-aware training via bi-directional updates with no extra inference cost.

</div>
</div>
