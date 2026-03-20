# Machine-Learning

Past machine learning course projects (NTU), organized by homework notebook. Each project focuses on a different stage of modern ML workflows, from retrieval and agents to transformer understanding and training.

## Projects

- `HW1_RAG.ipynb`  
  Built a Retrieval-Augmented Generation pipeline with role-based LLM agents (question extraction, keyword extraction, QA, and fact-checking).  
  Techniques: web retrieval, prompt engineering, agent orchestration, context construction, and RAG-based answer generation.

- `HW2_Ai_Agents.ipynb`  
  Implemented an AI-agent workflow that iteratively proposes, executes, evaluates, and debugs ML code for a tabular prediction task.  
  Techniques: multi-agent prompting, execution-loop feedback, automated error analysis, journaling/memory summaries, and feature selection guidance.

- `HW3_Transformers.ipynb`  
  Explored transformer/LLM behavior using Hugging Face models, with a focus on how chat templates affect generation quality.  
  Techniques: tokenizer/model loading, prompt-format comparison, instruction tuning style prompting, and cross-encoder based response scoring.

- `HW4_Training_Transformers.ipynb`  
  Trained a decoder-only transformer for next-token prediction on tokenized Pokemon image sequences.  
  Techniques: custom dataset/dataloader design, autoregressive language modeling objective, training/validation loops, and sequence-to-image reconstruction analysis.

- `HW5-finetuning.ipynb`  
  Fine-tuned a Llama-based instruction model under HW constraints using parameter-efficient adaptation and a curated subset of conversation data.  
  Techniques: LoRA/PEFT adapters with Unsloth acceleration, dataset filtering/sorting and prompt formatting, supervised fine-tuning (SFTTrainer), and post-training inference generation.
