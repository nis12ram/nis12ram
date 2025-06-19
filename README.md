# Hi there, I'm nishant! 👋

🎓 **Student | Aspiring NLP Engineer**

I’m currently a student immersed in the world of Natural Language Processing and Artificial Intelligence, with a special interest in:

- **Small, multilingual, domain-specific LLMs**  
- Building **powerful Indic-based, task-specific language models**

🔬 **What I'm Learning & Using**
- **Python**: My primary programming language
- **Hugging Face Transformers**: For cutting-edge NLP
- **PyTorch**: The backbone of my deep learning experiments

🌱 **Current Focus**
I’m passionate about understanding how to create efficient, compact LLMs tailored for specific domains and Indic languages. My goal is to empower regional and specialized applications through AI.

🚀 **Projects**
- **Inshorts-experiments**: A compact summarization pipeline designed for Inshorts-style news. This project explores how to prune a capable teacher model and regain its performance using distillation (behavior cloning) and supervised fine-tuning (SFT). Starting with a base model fine-tuned on Inshorts (Qwen2.5-0.5B-Instruct), applied hybrid pruning (width + depth) to reduce the model size significantly—down to 11 layers and ~277M parameters. 

  Despite a steep drop in raw performance (LLM-based eval score ~1.0/5), recovered capabilities step-by-step:
  
  - 📉 **Pruned model** — minimal summarization ability
  - 🔁 **Distilled model** — recovers up to ~3.15/5 eval score using behavior cloning
  - 📈 **Distilled + SFT model** — reaches ~3.80/5, outperforming the original teacher on the test set
  
  This project demonstrates that extreme model compression paired with smart recovery strategies can still yield high-quality, domain-specific summarization.

  🔗 **Links**:  
  [GitHub Repository](https://github.com/nis12ram/Inshorts-experiments)  
  [qwen2.5-0.5B-Instruct-Inshort](https://huggingface.co/nis12ram/qwen2.5-0.5B-Instruct-Inshort)  
  [qwen2.5-0.5B-Instruct-pruned-Inshort](https://huggingface.co/nis12ram/qwen2.5-0.5B-Instruct-pruned-Inshort)  
  [qwen2.5-0.5B-Instruct-pruned-distill-Inshort](https://huggingface.co/nis12ram/qwen2.5-0.5B-Instruct-pruned-distill-Inshort)  
  [qwen2.5-0.5B-Instruct-pruned-distill-sft-Inshort](https://huggingface.co/nis12ram/qwen2.5-0.5B-Instruct-pruned-distill-sft-Inshort)

---

*Thanks for visiting my profile! Feel free to connect or check back soon for more updates on my work in AI and NLP.*