# BaxBot

Click [here](https://github.com/baxterwells/BaxBot) to go to my **BaxBot** repository.

## Overview
**BaxBot** is a personalized assistant that helps me with tasks. It uses my tone of voice and personality via RAG. **BaxBot** has been developed with the following architectural patterns:
- ReAct Architecture
- Multi-Modal Orchestration
- Dual-Layer Memory Architecture
- Custom and Modular Tool-Calling Protocol
- Retrieval-Augmented Generation (RAG)
- Semantic Context Injection

## BaxBot's Tools
The following are tools that **BaxBot** can independently and modularly call based on inferring the user's intent:
- **Photo Sorter**: Analyze images with *llava* and detect user-specified objects (people, pets, etc.), saving copies to a new directory, separated by object.
- **System Stats**: Provide the statistics of the current state of the local computer.
- **Memory Manager**: Save and refine both short- and long-term memory via *ChromaDB* upserting.
