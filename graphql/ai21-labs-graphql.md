# AI21 Labs GraphQL Schema

This conceptual GraphQL schema maps the AI21 Labs REST API surface — covering the Jamba chat completion, Maestro agentic planning, conversational RAG file library, batch processing, fine-tuning, text improvement, embedding, and segmentation capabilities — to a strongly typed GraphQL model.

## Source API

- **Provider:** AI21 Labs
- **Base URL:** `https://api.ai21.com/studio/v1`
- **Reference:** https://docs.ai21.com/reference
- **GitHub:** https://github.com/AI21Labs

## Coverage

| Domain | Types |
|--------|-------|
| Models & Capabilities | Model, ModelDetails, JambaInstruct, ModelCapabilities, ContextWindow |
| Chat Completions | CompletionRequest, CompletionResult, Prompt, Completion, TextSegment, FinishReason, TokenCount, LogProb, TokenData, TokenTopK, ChatMessage, SystemPrompt, UserMessage, AssistantMessage, ChatCompletion, ChatChoice, ChatUsage |
| Summarization | Summarize, SummarizeRequest, SummarizeResult, TaskType, SourceType, SummaryLength, Summary |
| Paraphrase | Paraphrase, ParaphraseRequest, ParaphraseOptions, ParaphraseStyle, ParaphraseResult |
| Grammar & Improvements | GrammarCorrection, GrammarRequest, GrammarResult, Improvement, TextImprovements |
| Embeddings | Embedding, EmbeddingRequest, EmbeddingResult, EmbeddingData |
| Segmentation | TextSegmentations, Segmentation, SegmentationType |
| Tool Calling | Tool, ToolCall, ToolResult, FunctionDef, JSONSchemaObject |
| RAG & Documents | RAGEngine, Document, DocumentResult |
| Platform | APIKey, UsageStat |
| Batch | BatchJob, BatchRequest, BatchResult, BatchStatus |
| Fine-Tuning | FineTuneJob, FineTuneStatus, FineTuneDataset, FineTuneStrategy |
| Maestro | MaestroRun, MaestroRunStatus, MaestroConfig, MaestroTool |

## Schema File

See [ai21-labs-schema.graphql](ai21-labs-schema.graphql) for the full type definitions.

## Authentication

All operations require a Bearer token in the `Authorization` header. In a real GraphQL gateway this would be supplied via context rather than per-field arguments.

## Notes

AI21 Labs does not publish a native GraphQL endpoint. This schema is a conceptual representation of the REST API for integration planning, code generation, and developer tooling purposes.
