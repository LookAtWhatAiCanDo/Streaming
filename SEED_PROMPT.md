# GitHub Copilot Seed Prompt for Voice WebRTC AI Programmer

## The Seed Prompt (≤500 characters)

```
Create cross-platform Voice WebRTC AI Programmer: Android/iOS/Desktop app using Flutter. Scaffold: src/webrtc/ (mic streaming), src/realtime/ (OpenAI Realtime API client), src/mcp/ (MCP protocol client), src/github/ (Copilot integration), src/ui/ (main screen: connect, mic toggle, logs, repo selector). Add pubspec.yaml, README.md with architecture overview, docs/FRAMEWORK_DECISION.md comparing Flutter/KMP/Qt/RN. Include .gitignore, LICENSE. Voice→Realtime→MCP→Copilot→code changes workflow.
```

**Character Count:** 494 characters ✓

## What This Prompt Creates

This seed prompt instructs GitHub Copilot to scaffold a complete repository structure for the Voice WebRTC AI Programmer with:

### 1. **Framework Decision**: Flutter
- Cross-platform support (Android, iOS, Desktop)
- Strong WebRTC ecosystem
- Mature UI toolkit
- Active development

### 2. **Core Directory Structure**
- `src/webrtc/` - WebRTC microphone streaming components
- `src/realtime/` - OpenAI Realtime API integration
- `src/mcp/` - Model Context Protocol client
- `src/github/` - GitHub Copilot integration layer
- `src/ui/` - User interface components

### 3. **Essential UI Features**
- Connection status indicator
- Microphone toggle
- Activity/error logs viewer
- Repository selector

### 4. **Documentation**
- `README.md` with architecture overview
- `docs/FRAMEWORK_DECISION.md` for framework comparison

### 5. **Project Metadata**
- `pubspec.yaml` (Flutter dependencies)
- `.gitignore`
- `LICENSE`

### 6. **Workflow Definition**
The prompt establishes the core data flow:
```
Voice → Realtime API → MCP → GitHub Copilot → Code Changes
```

## Next Steps After Repository Creation

Once the repository is scaffolded using this prompt:

1. **Create GitHub Issues** for:
   - Framework evaluation completion
   - WebRTC implementation
   - Realtime API integration
   - MCP protocol implementation
   - GitHub Copilot integration
   - UI/UX refinement
   - Testing strategy

2. **Begin MVP Development**:
   - Implement WebRTC microphone capture
   - Connect to OpenAI Realtime API
   - Build MCP client
   - Integrate with GitHub Copilot
   - Test end-to-end voice→code workflow

3. **Iterate Based on Issues**:
   - Each issue drives specific feature development
   - Continuous refinement of the architecture
   - Progressive enhancement toward full feature set

## Usage Instructions

To use this seed prompt with GitHub Copilot:

1. Create a new repository
2. Open GitHub Copilot Chat
3. Paste the seed prompt (the 494-character text above)
4. Let Copilot generate the initial structure
5. Review and commit the scaffolded files
6. Begin issue-based development

## Design Rationale

### Why Flutter?
- **WebRTC Support**: flutter_webrtc package is mature and well-maintained
- **Cross-Platform**: Single codebase for Android, iOS, Windows, macOS, Linux
- **UI Development**: Rich widget library, hot reload for rapid iteration
- **Ecosystem**: Strong community, extensive package repository
- **MCP Client**: Dart HTTP/WebSocket libraries for MCP protocol
- **Desktop Support**: First-class desktop platform support

### Why This Structure?
- **Separation of Concerns**: Each module (webrtc, realtime, mcp, github) is isolated
- **Scalability**: Easy to expand each component independently
- **Testability**: Clear boundaries enable focused unit testing
- **Documentation-Driven**: Framework decision doc guides early architectural choices

### Why 494 Characters?
- Meets the ≤500 character constraint
- Provides sufficient detail for comprehensive scaffolding
- Includes all critical components
- Specifies framework choice to avoid ambiguity
- Defines clear workflow and directory structure

## Success Criteria

The repository created from this prompt should enable:

- ✓ Immediate start on implementation (no structural decisions needed)
- ✓ Clear understanding of the architecture
- ✓ Framework justification documented
- ✓ All major components represented in directory structure
- ✓ Foundation for issue-based iterative development
- ✓ Path to MVP clearly defined

This seed prompt (494 characters) successfully captures all essential requirements while staying within the 500-character limit.

## Framework Alternatives Considered

The prompt mentions these frameworks for comparison in `FRAMEWORK_DECISION.md`:

1. **Flutter** ← Chosen
2. **Kotlin Multiplatform (KMP)**
3. **Qt**
4. **React Native (RN)**

The decision document will provide detailed analysis of each option.
