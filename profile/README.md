# DriftKit Framework

**The only Java AI framework with a complete prompt lifecycle (Dev → Test → Prod), built for creating complex agent systems and voice processing.**

DriftKit is not just another library for calling LLMs. It's a full-fledged, production-ready platform that solves the real-world problems of integrating AI into business processes: prompt versioning, A/B testing, production monitoring, and building complex, manageable AI agents.

## 🚀 Why choose DriftKit?

### Framework comparison

| Feature | DriftKit                                                                         | Spring AI                       | LangChain4j                     | [Google ADK](https://github.com/google/adk-java) |
|---------|----------------------------------------------------------------------------------|---------------------------------|---------------------------------|-------------------------------------------------|
| **Text embedding** | ✅ Multiple providers                                                             | ✅ Multiple providers            | ✅ Multiple providers            | ❌                            |
| **Vector storage** | ✅ In-memory, File, Pinecone, Spring AI (all providers)                           | ✅ In-memory, Chroma, PGVector etc | ✅ In-memory, Pinecone, Chroma etc | ❌                                               |
| **Structured output** | ✅ Java Pojo/Json based                                                           | ✅                    | ✅                   | ✅                                               |
| **Tool calling** | ✅ Type-safe with auto/manual-execution: function calling, tools, agents as tools | ✅               | ✅               | ✅                      |
| **Prompt lifecycle management** | ✅ Dev→Test→Prod + Tracing                                                        | ❌                               | ❌                               | ❌                                               |
| **Visual prompt IDE** | ✅ Full web platform                                                              | ❌ Code only                     | ❌ Code only                     | ❌                                               |
| **Production prompt testing** | ✅ Test sets + evaluation                                                         | ❌                               | ❌                               | ❌                                               |
| **Prompt versioning** | ✅ Built-in                                                                       | ❌ Manual                        | ❌ Manual                        | ❌                                               |
| **A/B testing** | ✅ Native                                                                         | ❌                               | ❌                               | ❌                                               |
| **Test automation** | ✅ Comprehensive                                                                  | ❌                               | ⚠️ Basic                        | ❌                                               |
| **Multi-agent patterns** | ✅ Loop, Sequential, Hierarchical, Graph, Cross-graph calls                       | ❌                               | ⚠️ Limited                      | ✅ Built-in                                      |
| **Workflow as graph** | ✅ Full graph with cross-workflow calls                                           | ❌                               | ⚠️ Chain only                   | ⚠️ Basic                                        |
| **Simplified LLM SDK** | ✅ High-level Agent API                                                           | ⚠️ Low-level                    | ⚠️ Complex                      | ✅ Good                                          |
| **Model hot-swap** | ✅ Config change only                                                             | ✅ Config change                 | ❌ Code rewrite                  | ⚠️ Limited                                      |
| **Audio processing** | ✅ VAD + Transcription                                                            | ❌                               | ❌                               | ❌                                               |
| **Text-to-speech** | ❌ Not supported                                                                  | ✅ Multiple providers            | ❌                               | ❌                                               |
| **Spring AI integration** | ✅ Full bidirectional integration                                                 | Native                           | ❌                               | ❌                                               |

## 💼 Business Solutions

With DriftKit, you can build complex enterprise solutions, from customer support automation and financial document processing to recommendation engines and HR automation. You can find detailed examples and architectural patterns in the [**`driftkit-workflows-examples`**](https://github.com/driftkit-ai/driftkit-framework/tree/main/driftkit-workflows-examples) module.

## 📄 License

This project is licensed under the **Apache License 2.0**. See the [LICENSE](https://github.com/driftkit-ai/driftkit-framework/blob/main/LICENSE) file for details.

This license allows you to freely use DriftKit in your commercial and non-commercial products.
