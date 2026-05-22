# 🚀 Advanced Algorithmic Reasoning using QLoRA

Lightweight fine-tuning of Phi-2 on advanced algorithmic reasoning and implementation-focused competitive programming concepts using QLoRA and LoRA adapters.

# 📌 Overview

• Fine-tuned a compact language model for advanced algorithmic reasoning tasks.

• Focused on implementation-heavy data structures and competitive programming concepts.

• Explored parameter-efficient fine-tuning using QLoRA and LoRA.

• Used 4-bit quantization for memory-efficient training on limited hardware.

# ⚙️ Tech Stack

• Python

• Hugging Face Transformers

• PEFT (LoRA)

• BitsAndBytes

• Accelerate

• Matplotlib

# 🧠 Model Configuration

• Base Model: microsoft/phi-2

• Fine-Tuning Method: QLoRA

• Quantization: 4-bit

• Precision: FP16

• Optimizer: paged_adamw_8bit

# 📂 Project Structure

• SLM.py → complete fine-tuning and inference pipeline

• dsa.json → instruction-response training dataset

• results/ → training logs and outputs

• README.md → project documentation

# 📁 Dataset

• Instruction-response style dataset.

• Focused on:

algorithmic explanations
implementation reasoning
debugging scenarios
edge-case discussions
Example Dataset Entry:

Instruction: Explain the intuition behind lazy propagation

Output: Lazy propagation helps defer updates in segment trees to avoid unnecessary recomputation and improve update efficiency.

# 🚀 Training

Install Dependencies:

• transformers

• datasets

• peft

• accelerate

• bitsandbytes

• matplotlib

# Run Training:

• Execute the training script to begin fine-tuning.

• Training uses LoRA adapters with 4-bit quantization for efficient optimization.

# 💡 Example Prompts

• Explain the intuition behind tree balancing

• Why does this implementation fail on edge cases?

• Explain lazy propagation step-by-step

# 📉 Features

• QLoRA-based fine-tuning

• LoRA parameter-efficient adaptation

• 4-bit quantized training

• Training loss visualization

• Lightweight training setup

• Algorithmic explanation generation

• Competitive programming reasoning support

# 🔬 Project Focus

• Parameter-efficient fine-tuning

• Low-resource LLM training

• Algorithmic reasoning enhancement

• Domain adaptation for technical problem-solving

# 📦 Model Saving

• Fine-tuned model weights are saved locally after training.

• Tokenizer configuration is exported for inference usage.

# 🔮 Future Improvements

• Larger instruction datasets

• Retrieval-Augmented Generation (RAG)

• FastAPI deployment

• Benchmark-based evaluation

• Interactive coding assistance

# 🙌 Acknowledgements

• Microsoft for Phi-2

• Hugging Face

• PEFT Library

• BitsAndBytes
