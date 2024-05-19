# RAG-Slim

- SLIM models: Structured Language Instruction Models from LLMWare
- Designed for AI agents and function calling tasks
- Generate structured outputs for complex automation workflows
- Multi-step, multi-process, and multi-model LLM-based
- Consists of 10 models: addition, arithmetic, comparison, concatenation, division, function-calling, multiplication, subtraction, sentiment-tool, variable assignment
- Slim-sentiment-tool: A notable example, a 4_K_M quantized GGUF version of slim-sentiment
- Specialized decoder-based LLMs, fine-tuned for function calling
- Fast and efficient inference
- Parallelizable for multi-model concurrent deployment on CPUs


## Getting Started

1. Clone the repository using:
   ```bash
   https://github.com/atul171223/RAG-Slim.git
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit application and interact with it via the user-friendly web interface using the command:
   ```bash
   streamlit run app.py
   ```