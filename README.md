### Hi, I'm Shrut 👋

I implement generative AI papers from scratch and document what breaks.

Machine Learning Engineer working on applied ML problems in MedTech, mostly navigating ambiguity and vague ideas. Outside of that I rebuild the models behind modern generative AI, from VAEs and discrete latents to CLIP, GPT-style LLMs, and autoregressive text-to-image, so I understand the mechanism instead of the API. Currently moving into speech and talking avatars.

Learn - Build - Feedback - Iterate

<p align="left">
<a href="https://x.com/detachedsl" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="detachedsl" height="30" width="40" /></a>
<a href="https://www.linkedin.com/in/shrut-dalwadi/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="shrut-dalwadi" height="30" width="40" /></a>
</p>

#### What I'm building

- [**generative-ai-from-scratch**](https://github.com/shrut2702/autoencoder_to_multimodal-genai) - VAE, VQ-VAE, VQ-VAE-2, CLIP, and DALL·E-1-style autoregressive text-to-image, each implemented by hand and pushed through ablations. Perceptual loss took VQ-VAE-2 from 0.44 to 0.097 LPIPS. The text-to-image write-up tracks a generation bug through two wrong hypotheses before pinning it on data scale.

- [**attention_to_llm**](https://github.com/shrut2702/attention_to_llm) - A GPT-2 style LLM built from tokenizer to DPO. Also holds architecture experiments with plots: pre-norm vs post-norm gradient stress test, RoPE vs absolute position embeddings across context lengths the model never saw, and MoE routing with and without a load balancing loss.

- [**microscaling-formats**](https://github.com/shrut2702/microscaling-formats) - Benchmark of per-tensor, block-32, and microscaling (MX) INT quantization at 8, 4, and 2 bits across 7 vision-language models on VQAv2 and TextVQA. INT8 is essentially free, per-tensor INT4 collapses every model to near zero accuracy because one scale per tensor rounds ~90% of weights to zero, and block-INT4 beats MXINT4 by 3 to 9%. [Blog post](https://medium.com/@shroot2702hd/its-not-the-bits-it-s-the-scale-in-vision-language-model-quantization-153f595606fd)

- [**upasak**](https://github.com/shrut2702/upasak) - A flexible, mindful to privacy, no-code/low-code framework for fine-tuning large language models, built around [Hugging Face Transformers](https://huggingface.co/docs/transformers/en/index). Streamlit interface, multi-format dataset support, built-in PII sanitization. [Tutorial](https://youtu.be/vccPQimdXUc)

- [**text_recognition**](https://github.com/shrut2702/text_recognition) - End-to-end OCR pipeline with CRAFT for detection and CRNN for recognition, trained from scratch on ~45,000 images and tracked with CometML.

- [**retail_vision**](https://github.com/shrut2702/Retail_Product_Detection) - Detects and groups products on retail shelves using YOLO, served through Flask microservices.

#### About me

I am a firm believer of figuring out as we go.

I started my career in 2024 and went deeper into AI to stop treating it as a black box. The further in I got, the more I fell for the fundamental mechanisms and principles behind deep learning architectures.

I'm broadly interested in maths, finance, tech, and ways to stop self-sabotaging. Aiming for generalist status, but my comfort zone has me in a death grip. Don't believe in fluff projects, either you learn something or you solve a problem.

Permanently buried under a backlog of papers to read.

<h3 align="left">Languages and Tools:</h3>
<p align="left">

<!-- Python -->
<a href="https://www.python.org" target="_blank" rel="noreferrer">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg"
       alt="python" width="40" height="40"/>
</a>
<!-- PyTorch -->
<a href="https://pytorch.org" target="_blank" rel="noreferrer">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg"
       alt="pytorch" width="40" height="40"/>
</a>
<!-- Hugging Face -->
<a href="https://huggingface.co" target="_blank" rel="noreferrer">
  <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg"
       alt="huggingface" width="40" height="40"/>
</a>
<!-- OpenCV -->
<a href="https://opencv.org" target="_blank" rel="noreferrer">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg"
       alt="opencv" width="40" height="40"/>
</a>
<!-- Docker -->
<a href="https://www.docker.com" target="_blank" rel="noreferrer">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg"
       alt="docker" width="40" height="40"/>
</a>
<!-- Git -->
<a href="https://git-scm.com" target="_blank" rel="noreferrer">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg"
       alt="git" width="40" height="40"/>
</a>

</p>
