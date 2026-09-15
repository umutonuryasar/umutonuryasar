# Hi, I'm Umut

**Applied AI Research Engineer** working on model efficiency, computer vision, and multimodal learning.

My work focuses on building and understanding efficient deep learning systems — from controlled research experiments to practical implementations and deployment. I'm particularly interested in **knowledge distillation, parameter-efficient fine-tuning, vision-language models, and representation learning**.

Currently exploring CLIP-style multimodal learning and efficient vision architectures.

## Selected Work

### **[MicroCLIP](https://github.com/umutonuryasar/microclip)**
**From-scratch CLIP-style vision-language model**

Building and experimentally studying a compact vision-language model, with a focus on contrastive learning objectives, training dynamics, and compute-efficient experimentation.

`PyTorch` · `CLIP` · `Vision Transformers` · `Contrastive Learning`

### **[RT-DETR Knowledge Distillation](https://github.com/umutonuryasar/rt-detr-kd)**
**Knowledge distillation for real-time object detection**

Research project investigating logit-, feature-, and combined-distillation strategies for RT-DETR, with reproducible experiments and deployment-oriented evaluation.

**First-author preprint:** [arXiv:2605.31191](https://arxiv.org/abs/2605.31191)

`Knowledge Distillation` · `RT-DETR` · `Object Detection` · `PyTorch`

### **[detrflow](https://github.com/umutonuryasar/detrflow)**
**Training, evaluation, and serving stack for RT-DETR**

An end-to-end implementation covering training, evaluation, benchmarking, and deployment, including FastAPI/Gradio serving and Docker support.

`Computer Vision` · `FastAPI` · `Docker` · `PyTorch`

## Open Source

I contribute fixes and improvements to ML/AI tooling I use in practice.

- **Hugging Face PEFT — [#3293](https://github.com/huggingface/peft/pull/3293)** · Merged  
  Reduced unnecessary CUDA memory overhead in `prepare_model_for_kbit_training`.

- **Andrew Ng's aisuite — [#319](https://github.com/andrewyng/aisuite/pull/319)** · Merged  
  Fixed Python 3.14 compatibility through dependency and lockfile updates.

## Research Interests

**Model Efficiency** — Knowledge Distillation · PEFT · Memory-Efficient Training  
**Computer Vision** — Vision Transformers · Object Detection · Representation Learning  
**Multimodal Learning** — CLIP · Vision-Language Models · Contrastive Learning

## About

I have a background in Electrical & Electronics Engineering and work independently on applied AI research and open-source projects.

I enjoy problems that sit between **research and engineering**: understanding why a method works, validating it experimentally, and turning it into clean, reproducible software.
