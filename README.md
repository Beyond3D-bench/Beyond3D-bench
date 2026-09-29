<div align="center">

# 👀 BEYOND3D

### Long Time No See: Benchmarking VLMs for Out-of-Sight Spatiotemporal Reasoning in Egocentric Videos

<p>
  <a href="https://arxiv.org/abs/2609.34630">
    <img src="https://img.shields.io/badge/arXiv-2609.34630-b31b1b?logo=arxiv&logoColor=white" alt="arXiv">
  </a>
  <a href="https://beyond3d-bench.github.io/website/">
    <img src="https://img.shields.io/badge/🌐%20Website-BEYOND3D-168ac5" alt="Website">
  </a>
  <a href="https://huggingface.co/datasets/Ffffangzhu/BEYOND3D">
    <img src="https://img.shields.io/badge/🤗%20Benchmark-BEYOND3D-f6b10a" alt="Hugging Face">
  </a>
</p>

<img src="https://raw.githubusercontent.com/Beyond3D-bench/vlm-evaluation/main/docs/assets/teaser_video.gif" width="520" alt="BEYOND3D teaser">

</div>

## About

**BEYOND3D** is a benchmark for evaluating whether vision-language models can reason about objects **after they leave the camera view** in dynamic egocentric videos.

Built on [HD-EPIC](https://hd-epic.github.io/site/), the benchmark follows objects as they are moved through real kitchen environments and asks models to recover their last known spatiotemporal state once they are no longer visible.

BEYOND3D evaluates four complementary capabilities:

**Visual Grounding** · **Temporal Grounding** · **Scene Localization** · **3D Spatial Perception**

The benchmark contains **9,000 questions** spanning eight question types, including when and where an object was last observed, its nearest fixture, and its direction or distance relative to the camera or another object.

## Resources

| | Resource | Description |
|---|---|---|
| 🌐 | **[Project Website](https://beyond3d-bench.github.io/website/)** | Benchmark overview, interactive examples, results, and analysis |
| 🤗 | **[Benchmark](https://huggingface.co/datasets/Ffffangzhu/BEYOND3D)** | BEYOND3D question sets and benchmark annotations |
| 🧪 | **[Evaluation Code](https://github.com/Beyond3D-bench/vlm-evaluation)** | Reproduce our VLM evaluation or evaluate your own model |
| 📄 | **[Paper](https://arxiv.org/abs/2609.34630)** | *Long Time No See: Benchmarking VLMs for Out-of-Sight Spatiotemporal Reasoning in Egocentric Videos* |
| 💻 | **[Website Code](https://github.com/Beyond3D-bench/website)** | Source code for the interactive project website |

## Citation

If you find BEYOND3D useful in your research, please cite:

```bibtex
@misc{ma2026beyond3d,
  title         = {Long Time No See: Benchmarking VLMs for Out-of-Sight Spatiotemporal Reasoning in Egocentric Videos},
  author        = {Fangzhou Ma and Ivo Alexander Ban and Eren Homburg and Gabriele Goletto and Rémi Pautrat and Mahdi Rad and Chiara Plizzari and Marc Pollefeys},
  year          = {2026},
  eprint        = {2609.34630},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CV},
  url           = {https://arxiv.org/abs/2609.34630}
}
```

<div align="center">

**ETH Zürich · Microsoft Spatial AI Lab · Bocconi University**

</div>
