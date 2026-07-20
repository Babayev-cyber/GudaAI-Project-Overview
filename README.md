# -GudaAI-Project-Overview
End-to-end AI-powered inventory and product traceability system with unique barcode tracking, label recognition, a fine-tuned local language model, and voice-enabled database querying.


GudaAI is an AI-powered inventory management and product traceability platform designed to track materials and products throughout their lifecycle within a manufacturing environment.

The system combines barcode generation and scanning, product-label recognition, a structured inventory database, a locally hosted fine-tuned language model, and a natural-language interface. Users can ask operational questions such as:

- What was the most recently scanned product?
- How many units of a specific item are currently in storage?
- Which materials were used during production?
- Which products were recently received or dispatched?

Responses are generated using live inventory records retrieved from the database, allowing the system to provide context-specific and operationally relevant information.

## Product Traceability Workflow

When a product or material arrives at the company, it is registered in the system and assigned a unique barcode. The barcode-generation workflow enforces uniqueness and prevents duplicate identifiers from being assigned to different inventory records.

The barcode is subsequently scanned whenever the item is used during internal production processes, creating a traceable record of inventory movement and material consumption. When a finished product is prepared for dispatch, a new unique barcode is generated and associated with the outgoing product.

This workflow provides end-to-end traceability across three primary stages:

1. Receipt and registration of incoming materials
2. Internal usage during production
3. Dispatch of finished products

## AI and Voice Interface

GudaAI uses a locally hosted language model that I fine-tuned for the application's inventory and operational use cases. The model allows users to interact with the inventory system through natural-language queries while grounding its responses in database records.

I also evaluated and integrated a production-grade text-to-speech solution, enabling the system to deliver inventory information through a professional voice interface in addition to text-based responses.

## What is my Contribution?

I designed and developed GudaAI from the ground up and was responsible for the complete implementation lifecycle. My work included:

- Designing the overall system architecture
- Developing the frontend and backend application
- Designing the inventory database structure
- Implementing barcode generation and scanning workflows
- Building product registration, usage, and dispatch processes
- Integrating product-label recognition
- Fine-tuning and deploying a locally hosted language model
- Connecting the AI interface to inventory records
- Selecting and integrating a production-grade text-to-speech system
- Implementing validation mechanisms to preserve barcode and inventory-data integrity

The project required combining full-stack development, database design, AI integration, and operational workflow engineering into a single production-oriented system.

## Relevance to AI Alignment and Reliability

Although GudaAI was developed as an inventory and traceability platform rather than an alignment research project, it involved several challenges relevant to reliable AI systems.

The AI assistant needed to ground its responses in trusted external data rather than relying solely on the model's internal knowledge. The system also required careful handling of incomplete, ambiguous, or unavailable records to reduce unsupported responses.

This work gave me practical experience with grounded model behavior, controlled access to external tools and data, failure-mode analysis, data integrity, and the design of AI systems whose outputs can be verified against an authoritative source.

## Technology Stack

The repository is primarily implemented in TypeScript, with additional components written in JavaScript, Kotlin, PowerShell, Python, CSS, and Java.

### Repository Language Composition

- TypeScript — 89.9%
- JavaScript — 4.2%
- Kotlin — 2.9%
- PowerShell — 1.3%
- Python — 1.0%
- CSS — 0.6%
- Java — 0.1%

## Project Availability

The source code is maintained in a private repository because it contains proprietary implementation details. This public repository provides a technical overview of the system, its architecture, and my contributions.

