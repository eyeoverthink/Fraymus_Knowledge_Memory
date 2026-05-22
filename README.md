# Fraymus Knowledge & Memory

Knowledge ingestion and memory management applications.

## Applications

- **KnowledgeIngestor** - Knowledge Ingestor - PDF Digestion into Holographic Memory
- **AkashicRecord** - Akashic Record - Universal Memory
- **LibraryAbsorber** - Library Absorber - Universal Integration
- **UniversalAbsorber** - Universal Absorber - The Web Eater
- **BlackHoleProtocol** - Black Hole Protocol - Eater of Worlds
- **Portal** - Portal - Universal Intake Valve

## Dependencies

- LWJGL 3.3.3 (OpenGL, GLFW, STB)
- ImGui Java 1.86.11
- JOML 1.10.5
- MongoDB Driver 4.11.1
- Apache PDFBox 3.0.3
- Jackson/Gson JSON processing

## Build

```bash
cd Asset-Manager
./gradlew build
```

## Run Knowledge & Memory Apps

```bash
./gradlew runKnowledgeGut      # Run Knowledge Ingestor
./gradlew runAkashicRecord    # Run Akashic Record
./gradlew runAbsorber         # Run Library Absorber
./gradlew runAkashicRecord    # Run Akashic Record
./gradlew runBlackHoleProtocol # Run Black Hole Protocol
./gradlew runPortal           # Run Portal
./gradlew runWebEater         # Run Universal Absorber
./gradlew runInject           # Inject knowledge based on Ollama recommendations
```

## Requirements

- Java 21
- Gradle 9.2+
- MongoDB (for persistence)
