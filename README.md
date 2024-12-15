
<h2 align="center"> <a href="https://arxiv.org/pdf/*****">Descriptive Caption Enhancement with Visual Specialists for Multimodal Perception </a></h2>
<h5 align="center"> If you like our project, please give us a star ⭐ on GitHub.  </h2>


## 📰 News

* **[2024.06.07]**  🔥🔥 Our data pipeline are available now !

* **[2024.06.07]**  🔥🤗 Our DCE-1M datasets is released, please check out and download in [DCE-1M](https://huggingface.co/datasets/syp115/DCE-1M)!


## 😮 Highlights
The <strong><em>visual perception capabilities</em></strong> of MLLMs directly impact their performance. It is well-known that the main factors influencing MLLMs' visual perception are <strong><em>data</em></strong> and <strong><em>structure</em></strong>.
<strong><em>Arcana</em></strong> aims to enhance the visual perception capabilities of MLLMs by addressing both of these aspects.
- On the <strong><em>data</em></strong> side, there is a scarcity of open-source data, and the available multimodal datasets contain limited visual components, preventing MLLMs from gaining sufficient visual perception capabilities from these sources.  To this end, we have developed a data engine to annotate multimodal data that ensures a diversity of visual factors.
- On the <strong><em>structural</em></strong> side, the language-driven decoder couples visual and language modalities within the same space, disregarding their unique characteristics and potentially causing information confusion or blurring. Furthermore, the frozen visual encoder cannot provide robust visual features, and directly fine-tuning it with a small dataset can affect its generalization capabilities. Toward this end, Arcana introduces MM-LoRA, which constructs a multimodal decoder to preserve the unique characteristics of different modalities. We also propose a Query Ladder adapter (QLadder) for the visual encoder, which retains the pre-trained image encoder's capabilities while introducing a small number of visual tokens to significantly enhance the model's ability to learn and represent visual information.
<!-- Model Image-->
<section class="hero teaser">
  <div class="container is-max-desktop">
    <div class="hero-body">
      <img src="assets/framework.png" alt="MY ALT TEXT"/>
      <img src="assets/mmlora.png" alt="MY ALT TEXT"/>
    </div>
  </div>
</section>
<!-- End Model Image -->



