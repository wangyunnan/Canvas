### <div align="center"> Canvas: Compositional Generation for Art Painting with Seamless Subject-Driven Infusion<div> 
<div align="center">
<div style="text-align: center;">
  <a href="https://huggingface.co/wangyunnan/Canvas"><img src="https://img.shields.io/static/v1?label=%F0%9F%A4%97%20Model&message=HuggingFace&color=yellow"></a> &ensp;
  <a href="https://huggingface.co/datasets/wangyunnan/Canvas"><img src="https://img.shields.io/static/v1?label=%F0%9F%A4%97%20Dataset&message=HuggingFace&color=yellow"></a> &ensp;
</div>
</div> 
</div>


## 📣 Update Log
- [2025.4.01] 🎉 We release the pre-trained Canvas and dataset at HuggingFace ([Model](https://huggingface.co/wangyunnan/Canvas)&[Dataset](https://huggingface.co/datasets/wangyunnan/Canvas)). 
- [2025.3.15] 🎉 Here comes Canvas, we release the code and dataset of Canvas. 


## 🪄✨ Abstract
<b>TL; DR: <font color="red">Canvas</font> is an automatic artistic image generation framework, which leverages manually collected and finely annotated CeaCulture datasets.</b>

<details><summary>CLICK for the full abstract</summary>
While diffusion-based art image synthesis has witnessed great success in terms of quality, there are still deficiencies in integrating artist-specified subjects with artistic style. In this paper, we propose Canvas, a framework that leverages the capabilities of text-guided latent diffusion models (LDMs) for flexible art image composition driven by diverse customized subject concepts. Specifically, we start by collecting art images manually drawn by proficient artists and annotating the corresponding subject concepts, forming the CreaCulture dataset. Based on this dataset, we build our Canvas with two generation stages. Firstly, a stable diffusion-based stylistic LDM is fine-tuned on the original CreaCulture dataset, aiming to generate an art-style background with annotated subject concepts. To alleviate the limited scope of tagged subject concepts, we propose nature-to-art (N2A) transition to expand the CreaCulture using the natural/art concepts from pre-trained/stylistic LDM, facilitating the fine-tuning of the tailor-made concept-derived LDM. Additionally, the Subject-Infused Attention (SIA) is integrated into the concept-derived LDM, which seamlessly composites the user-specified natural foreground with the pre-generated art background image in a training-free manner. Extensive experiments demonstrate that Canvas outperforms state-of-the-art alternatives under the setting of art image synthesis.
</details>


## License
This repository is released under the MiT license as found in the [LICENSE](LICENSE) file.