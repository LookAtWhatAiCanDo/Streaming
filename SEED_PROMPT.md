# GitHub Copilot Seed Prompt for Voice WebRTC AI Programmer

## The Seed Prompt (≤500 characters)

```
Create cross-platform Voice WebRTC AI Programmer (Android/iOS/Desktop). Scaffold: src/webrtc/ (mic streaming), src/realtime/ (OpenAI Realtime API client), src/mcp/ (MCP protocol), src/github/ (Copilot integration), src/ui/ (connect, mic toggle, logs, repo selector), tests/, .github/workflows/. Add README.md, docs/FRAMEWORK_EVAL.md (compare Flutter/KMP/Qt/ReactNative: WebRTC, Realtime API, MCP, cross-platform, dev experience, ecosystem). Voice→Realtime→MCP→Copilot→code workflow.
```

**Character Count:** 482 characters ✓

## What This Prompt Creates

This seed prompt instructs GitHub Copilot to scaffold a complete repository structure for the Voice WebRTC AI Programmer with:

### 1. **Framework Decision**: To Be Determined
- Framework choice deferred to evaluation phase (as specified in Issue #1)
- Evaluation document scaffolded: `docs/FRAMEWORK_EVAL.md`
- Candidates: Flutter, Kotlin Multiplatform, Qt, React Native
- Evaluation criteria: WebRTC support, Realtime API integration, MCP client viability, cross-platform reach, developer experience, ecosystem maturity

### 2. **Core Directory Structure**
- `src/webrtc/` - WebRTC microphone streaming components
- `src/realtime/` - OpenAI Realtime API integration
- `src/mcp/` - Model Context Protocol client
- `src/github/` - GitHub Copilot integration layer
- `src/ui/` - User interface components
- `tests/` - Test suite for all components
- `.github/workflows/` - CI/CD automation (testing, linting, builds)

### 3. **Essential UI Features**
- Connection status indicator
- Microphone toggle
- Activity/error logs viewer
- Repository selector

### 4. **Documentation**
- `README.md` with architecture overview
- `docs/FRAMEWORK_EVAL.md` for framework comparison and decision

### 5. **Project Metadata**
- `.gitignore` and `LICENSE` (implicit/standard)
- Framework-specific files (e.g., `pubspec.yaml`, `package.json`) will be added after framework selection

### 6. **Workflow Definition**
The prompt establishes the core data flow:
```
Voice → Realtime API → MCP → GitHub Copilot → Code Changes
```

## Next Steps After Repository Creation

Once the repository is scaffolded using this prompt:

1. **Create GitHub Issues** for:
   - **Framework evaluation** (primary early task)
   - WebRTC implementation
   - Realtime API integration
   - MCP protocol implementation
   - GitHub Copilot integration
   - UI/UX refinement
   - Testing strategy

2. **Evaluate and Select Framework**:
   - Compare Flutter, Kotlin Multiplatform, Qt, and React Native
   - Consider WebRTC support, API integration capabilities, and developer experience
   - Document decision in `docs/FRAMEWORK_EVAL.md`
   - Initialize chosen framework's project structure

3. **Begin MVP Development**:
   - Implement WebRTC microphone capture
   - Connect to OpenAI Realtime API
   - Build MCP client
   - Integrate with GitHub Copilot
   - Test end-to-end voice→code workflow

4. **Iterate Based on Issues**:
   - Each issue drives specific feature development
   - Continuous refinement of the architecture
   - Progressive enhancement toward full feature set

## Usage Instructions

To use this seed prompt with GitHub Copilot:

1. Create a new repository
2. Open GitHub Copilot Chat
3. Paste the seed prompt (the 482-character text above)
4. Let Copilot generate the initial structure
5. Review and commit the scaffolded files
6. Begin issue-based development

## Design Rationale

### Why Framework-Agnostic?
The issue explicitly requires framework evaluation as a major early milestone. The seed prompt intentionally defers the framework decision to allow proper evaluation of:

- **Flutter**: Strong WebRTC support (flutter_webrtc), excellent cross-platform reach, rich UI toolkit, Dart ecosystem
- **React Native**: Lightweight Node.js/JavaScript ecosystem, extensive npm packages, react-native-webrtc, familiar to web developers
- **Kotlin Multiplatform**: Native performance, shared business logic, growing ecosystem, direct platform API access
- **Qt**: Mature C++ framework, excellent desktop support, QML for UI, strong performance

Each framework will be evaluated against:
- **WebRTC Support**: Quality and maturity of WebRTC libraries
- **Realtime API Integration**: HTTP/WebSocket client capabilities
- **MCP Client Viability**: Protocol implementation feasibility
- **Cross-Platform Reach**: Android, iOS, Desktop (Windows, macOS, Linux)
- **Developer Experience**: Tooling, debugging, hot reload, documentation
- **Ecosystem Maturity**: Package availability, community support, long-term viability

The evaluation will produce a written recommendation with justification, enabling an informed decision rather than a premature choice.

### Why This Structure?
- **Separation of Concerns**: Each module (webrtc, realtime, mcp, github) is isolated
- **Scalability**: Easy to expand each component independently
- **Testability**: Clear boundaries enable focused unit testing
- **Documentation-Driven**: Framework decision doc guides early architectural choices

### Why 482 Characters?
- Meets the ≤500 character constraint
- Provides sufficient detail for comprehensive scaffolding
- Includes all critical components
- Specifies framework evaluation instead of premature choice
- Defines clear workflow and directory structure
- Includes test infrastructure and CI/CD foundation

## Success Criteria

The repository created from this prompt should enable:

- ✓ Immediate start on implementation (no structural decisions needed)
- ✓ Clear understanding of the architecture
- ✓ Framework evaluation criteria established
- ✓ All major components represented in directory structure
- ✓ Foundation for issue-based iterative development
- ✓ Path to MVP clearly defined

This seed prompt (482 characters) successfully captures all essential requirements while staying within the 500-character limit and respecting the issue's requirement to evaluate frameworks before making a decision.

## Framework Alternatives to Evaluate

The prompt instructs creation of `FRAMEWORK_EVAL.md` to compare:

1. **Flutter**
2. **Kotlin Multiplatform (KMP)**
3. **Qt**
4. **React Native (RN)**

The evaluation will determine which framework best meets the project's requirements.
