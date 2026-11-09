# Projects

A portfolio of projects spanning C++ systems programming, graphics, concurrency, data processing, and AI-powered automation.

## [ASCII Drawings](https://github.com/JeniaShishkin/ascii-drawings)
- Built a C++ terminal-canvas demo that renders geometric shapes and illustrations using ASCII characters.
- Implemented line and circle drawing with coordinate-based placement on a grid.
- Added colored canvas support to customize foreground and background colors in terminal output.
- Demonstrated multiple canvases and rendered scenes in a timed display loop.

## [C++ Linked List Practice](https://github.com/JeniaShishkin/cpp-Linked-list-practice)
- Implemented a singly linked list in C++ with explicit node, head, and tail management.
- Supports inserting at the front or back, removing the first node, and checking for an empty list.
- Includes an iterator with dereference, increment, and comparison operations for traversing elements.
- Exercises core data-structure concepts including ownership, copying, and linked-node traversal.

## [Drone Simulator](https://github.com/JeniaShishkin/Drone-Simulator)
- Developed a modular C++ drone simulator with a grid-based world, navigation, and command-driven movement.
- Models different terrain tiles and provides interchangeable sensors with distinct obstacle-detection ranges.
- Tracks finite energy consumption for commands and supports remote interaction through a TCP networking layer.
- Organizes behavior around abstractions and the Command pattern, with an emphasis on SOLID principles and extensibility.

## [E-Commerce Product Deduplication](https://github.com/JeniaShishkin/e-commerce-product-deduplication)
- Created a Python tool that consolidates product catalog entries by SKU and retains the lowest-priced option for each product.
- Processes CSV input and output, including catalogs with product names in different languages.
- Makes deduplication independent of input order and reports catalog reduction statistics.
- Includes sample data and error handling for common input-format issues.

## [Memory Allocator](https://github.com/JeniaShishkin/Memory-Allocator)
- Implemented a learning-focused C++ allocator that manages allocations inside a contiguous memory buffer.
- Uses a first-fit strategy and block metadata in headers and footers to track allocation state.
- Splits larger free blocks to satisfy smaller requests and coalesces neighboring free blocks after deallocation.
- Synchronizes allocator operations with a mutex and returns `nullptr` when a request cannot be satisfied.

## [MyString](https://github.com/JeniaShishkin/MyString)
- Implemented a custom C++ string type that manages its own dynamically allocated character buffer.
- Provides copy and move construction, assignment, and swap-based resource management.
- Supports indexing with bounds checking, equality and ordering comparisons, concatenation, and stream output.
- Exposes utility operations for checking whether the string is empty and retrieving its size.

## [RAG-Based Movie Script Q&A System](https://github.com/JeniaShishkin/RAG-Based-Movie-Script-QA-System)
- Built a question-answering application that grounds responses in retrieved excerpts from movie scripts.
- Loads script text from web pages, splits it into overlapping chunks, and creates embeddings for retrieval.
- Uses Qdrant as a vector store and retrieves relevant passages to provide context to the language model.
- Prompts the model to answer from the supplied script context and to say when the database lacks an answer.

## [Random Number Generator Pipeline](https://github.com/JeniaShishkin/Random-number-generator-pipeline)
- Built a multithreaded C++ pipeline that generates random numbers, removes duplicates, filters prime values, and prints results.
- Connects processing stages with blocking cyclic queues so workers can exchange data concurrently.
- Uses thread pools for generation and prime filtering, with separate threads for uniqueness filtering and output.
- Demonstrates producer-consumer coordination and staged parallel processing.

## [Research AI Agent](https://github.com/JeniaShishkin/research-AI-Agent)
- Created a Python research assistant that takes a user query and coordinates an LLM with search, Wikipedia, and save tools.
- Structures the result as a topic, summary, sources, and a record of tools used.
- Uses a prompt template and schema-based parsing to guide the model toward consistent, machine-readable output.
- Demonstrates tool-calling agent patterns for automating research workflows.

## [Simple Ray Tracer](https://github.com/JeniaShishkin/SimpleRayTracer)
- Developed a C++ graphics project that renders a scene into an image and displays it in an SDL window.
- Separates application lifecycle, scene rendering, and image display into distinct components.
- Uses Eigen for vector and matrix operations in the rendering code.
- Includes a Makefile-based build setup for the application.

## LinkedIn Job Discovery & Relevance Automation (n8n)
- Designed an n8n workflow to identify LinkedIn job listings relevant to a user's criteria using configurable filtering logic.
- Uses API calls to Google Sheets, Google Docs, and Google Drive to work with job data and related documents.
- Integrates ChatGPT through an API key to evaluate job relevance and support the filtering process.
- Uses workflow loops to process requests and handle API overload conditions more reliably.
- Runs locally in a Docker container.
