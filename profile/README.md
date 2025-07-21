# DriftKit Framework

**The only Java AI framework with a complete prompt lifecycle (Dev → Test → Prod), built for creating complex agent systems and voice processing.**

DriftKit is not just another library for calling LLMs. It's a full-fledged, production-ready platform that solves the real-world problems of integrating AI into business processes: prompt versioning, A/B testing, production monitoring, and building complex, manageable AI agents.

## 🚀 Key Features

- **Complete Prompt Lifecycle**: The only platform on Java that provides tools for developing, testing, versioning, A/B testing, and monitoring prompts in production.
- **Visual Prompt IDE**: A built-in web interface for prompt engineering and testing, available out-of-the-box.
- **Advanced Agent Orchestration**: Build complex agent systems using Loop, Sequential, Workflows-based, and Hierarchical patterns for iterative result refinement.
- **Type-Safe AI Integration**: Work directly with Java objects without manual JSON parsing. The framework handles all the heavy lifting of serialization and deserialization.
- **Hot-Swappable Models**: Switch AI models (e.g., GPT-4o to Claude 3) via configuration, without changing code or recompiling your application.
- **Built-in Audio Processing**: Ready-to-use components for voice processing, including VAD (Voice Activity Detection), streaming transcription, and workflow integration.

## 🧩 Framework Modules

DriftKit has a modular architecture. You can include the entire framework or add specific components to solve particular tasks.

| **Module** | **Description** | **Details** |
| --- | --- | --- |
| **`driftkit-common`** | Core utilities for chat, documents, and templates. | [README.md](https://www.google.com/search?q=driftkit-common/README.md) |
| **`driftkit-clients`** | A unified interface for working with various AI providers (OpenAI, Anthropic, etc.). | [README.md](https://www.google.com/search?q=driftkit-clients/README.md) |
| **`driftkit-embedding`** | Services for creating text embeddings with support for different models. | [README.md](https://www.google.com/search?q=driftkit-embedding/README.md) |
| **`driftkit-vector`** | Vector storage and search with support for in-memory, file-based, and cloud databases. | [README.md](https://www.google.com/search?q=driftkit-vector/README.md) |
| **`driftkit-workflows`** | A powerful engine for orchestrating AI processes based on annotations. | [README.md](https://www.google.com/search?q=driftkit-workflows/README.md) |
| **`driftkit-context-engineering`** | A platform for managing the prompt lifecycle with a web interface. | [README.md](https://www.google.com/search?q=driftkit-context-engineering/README.md) |
| **`driftkit-audio`** | Components for processing audio streams and voice commands. | [README.md](https://www.google.com/search?q=driftkit-audio/README.md) |
| **`driftkit-chat-assistant-framework`** | A framework for creating multi-step conversational assistants. | [README.md](https://www.google.com/search?q=driftkit-chat-assistant-framework/README.md) |

## 💼 Business Solutions

With DriftKit, you can build complex enterprise solutions, from customer support automation and financial document processing to recommendation engines and HR automation. You can find detailed examples and architectural patterns in the [**`driftkit-workflows-examples`**](https://www.google.com/search?q=driftkit-workflows-examples/README.md) module.

## 🤝 Contributing

We welcome all contributions to the project! If you'd like to suggest a feature, report a bug, or improve the documentation, please read our [Contributing Guidelines](https://www.google.com/search?q=CONTRIBUTING.md).

Join our community on [Discord](https://www.google.com/search?q=https://discord.gg/your-invite-link) to discuss ideas and get help.

## 📄 License

This project is licensed under the **Apache License 2.0**. See the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.

This license allows you to freely use DriftKit in your commercial and non-commercial products.
