https://huggingface.co/docs/hub/en/gguf

GGUF is a new format introduced by the llama.cpp team on August 21st 2023. It is a replacement for GGML, which is no longer supported by llama.cpp.

Here is an incomplate list of clients and libraries that are known to support GGUF:

llama.cpp. The source project for GGUF. Offers a CLI and a server option. (https://github.com/ggerganov/llama.cpp)
text-generation-webui, the most widely used web UI, with many features and powerful extensions. Supports GPU acceleration. (https://github.com/oobabooga/text-generation-webui)
KoboldCpp, a fully featured web UI, with GPU accel across all platforms and GPU architectures. Especially good for story telling. (https://github.com/LostRuins/koboldcpp)
LM Studio, an easy-to-use and powerful local GUI for Windows and macOS (Silicon), with GPU acceleration. (https://lmstudio.ai/, https://github.com/lmstudio-ai/lms)
LoLLMS Web UI, a great web UI with many interesting and unique features, including a full model library for easy model selection. (https://github.com/ParisNeo/lollms-webui)
Faraday.dev, an attractive and easy to use character-based chat GUI for Windows and macOS (both Silicon and Intel), with GPU acceleration. (https://faraday.dev/)
ctransformers, a Python library with GPU accel, LangChain support, and OpenAI-compatible AI server. (https://github.com/marella/ctransformers)
llama-cpp-python, a Python library with GPU accel, LangChain support, and OpenAI-compatible API server. (https://github.com/abetlen/llama-cpp-python)
candle, a Rust ML framework with a focus on performance, including GPU support, and ease of use. (https://github.com/huggingface/candle)
