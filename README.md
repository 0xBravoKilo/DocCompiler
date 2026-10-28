# DocCompiler

**DocCompiler** is a Python-based pipeline designed to transform Godot Engine's Sphinx `.rst` documentation into high-quality, LLM-optimized Markdown. 

By moving beyond simple format conversion, DocCompiler ensures that documentation is perfectly structured for Retrieval-Augmented Generation (RAG) and other AI-driven workflows.

### Features
*   **Multi-Pass Transformation**: A robust pipeline that handles complex RST constructs, including manual table reconstruction, code block conversion, and metadata stripping.
*   **Semantic Chunking**: Automatically splits content at logical header boundaries to ensure that embeddings remain coherent and contextually complete.
*   **Contextual Headers**: Injects the full header hierarchy into every individual chunk, ensuring that an LLM always knows exactly where a specific piece of information sits within the larger documentation tree.
*   **LLM-Ready**: Specifically engineered to minimize "hallucinations" caused by lost context in fragmented documentation.
