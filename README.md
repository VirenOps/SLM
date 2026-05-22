🚀 Algorithmic Reasoning via QLoRA
Lightweight fine-tuning of microsoft/phi-2 for advanced algorithmic reasoning and competitive programming using QLoRA + LoRA adapters.

⚙️ Tech Stack
Python · Transformers · PEFT (LoRA) · BitsAndBytes · Accelerate · Matplotlib

🧠 Model Config
ParameterValueBase Modelmicrosoft/phi-2Fine-TuningQLoRAQuantization4-bitPrecisionFP16Optimizerpaged_adamw_8bit

📂 Project Structure
├── dataset/          # Training data
├── results/          # Logs & outputs
├── trained-model/    # Saved fine-tuned model
├── train.py          # Training pipeline
└── README.md

📁 Dataset
Instruction-response pairs covering:

Algorithmic explanations & implementation reasoning
Debugging scenarios & edge-case discussions

Example:
Instruction: Explain the intuition behind lazy propagation
Output: Lazy propagation defers updates in segment trees to avoid
        unnecessary recomputation and improve update efficiency.

🚀 Quickstart
bash# Install dependencies
pip install transformers datasets peft accelerate bitsandbytes matplotlib

# Run training
python train.py

💡 Example Prompts

Explain the intuition behind tree balancing
Why does this implementation fail on edge cases?
Explain lazy propagation step-by-step


🔮 Future Work

Larger instruction datasets
RAG integration
FastAPI deployment
Benchmark-based evaluation


🙌 Acknowledgements
Microsoft Phi-2 · Hugging Face · PEFT · BitsAndBytes

Key changes made: merged redundant sections (Features + Overview → intro), replaced bullet-heavy sections with a config table, trimmed boilerplate prose, and collapsed the install/run steps into a single Quickstart block.
