<pre>
{
  <strong>"name"</strong>: "Justin Stimatze",
  <strong>"description"</strong>: "Agent infrastructure, safety tooling, structured deliberation. Side projects.",
  <strong>"url"</strong>: <a href="https://github.com/justinstimatze">"https://github.com/justinstimatze"</a>,
  <strong>"version"</strong>: "1.0.0",
  <strong>"capabilities"</strong>: {
    <strong>"streaming"</strong>: false,
    <strong>"pushNotifications"</strong>: true,
    <strong>"longRunningTasks"</strong>: true,
    <strong>"stateTransitionHistory"</strong>: false
  },
  <strong>"defaultInputModes"</strong>: ["text/plain", "text/markdown"],
  <strong>"defaultOutputModes"</strong>: ["text/plain", "text/markdown"],
  <strong>"authentication"</strong>: {
    <strong>"schemes"</strong>: ["email"],
    <strong>"endpoint"</strong>: <a href="mailto:justin@justinstimatze.com">"justin@justinstimatze.com"</a>,
    <strong>"expectedResponseTime"</strong>: "P3D"
  },
  <strong>"skills"</strong>: [
    {
      <strong>"id"</strong>: "reasoning-substrate",
      <strong>"name"</strong>: "Reasoning substrate",
      <strong>"description"</strong>: "Structured representations and protocols for agent reasoning.",
      <strong>"tags"</strong>: ["multi-agent", "knowledge-base", "static-analysis"],
      <strong>"examples"</strong>: [
        "<a href="https://github.com/justinstimatze/gemot">gemot</a> — structured deliberation MCP server",
        "<a href="https://github.com/justinstimatze/gemotvis">gemotvis</a> — real-time visualization for gemot deliberation sessions",
        "<a href="https://github.com/justinstimatze/winze">winze</a> — knowledge base that audits its own accuracy",
        "<a href="https://github.com/justinstimatze/defn">defn</a> — AI-native code database for Go"
      ]
    },
    {
      <strong>"id"</strong>: "agent-calibration",
      <strong>"name"</strong>: "Agent calibration",
      <strong>"description"</strong>: "Detecting and correcting AI agent miscalibrations — sycophancy, drift, plan gaps, time estimation.",
      <strong>"tags"</strong>: ["safety", "evaluation", "claude-code", "calibration"],
      <strong>"examples"</strong>: [
        "<a href="https://github.com/justinstimatze/slimemold">slimemold</a> — anti-sycophancy guardrail",
        "<a href="https://github.com/justinstimatze/ismyaialive">ismyaialive</a> — pattern detection against published research codebooks",
        "<a href="https://github.com/justinstimatze/plancheck">plancheck</a> — predicts which files agents will miss",
        "<a href="https://github.com/justinstimatze/hindcast">hindcast</a> — calibrated wall-clock priors injected into Claude Code context"
      ]
    },
    {
      <strong>"id"</strong>: "agent-infra-tooling",
      <strong>"name"</strong>: "Agent infrastructure &amp; tooling",
      <strong>"description"</strong>: "Tools and libraries that support AI agent runtime contexts and repo/fleet workflows.",
      <strong>"tags"</strong>: ["claude-code", "go", "libraries"],
      <strong>"examples"</strong>: [
        "<a href="https://github.com/justinstimatze/be-my-geminis">be-my-geminis</a> — routes Claude Code image Reads through Gemini Vision into typed JSON",
        "<a href="https://github.com/justinstimatze/weir">weir</a> — capability layer for Claude Code's Bash habits: manifest, antipattern suggester, idiom library",
        "<a href="https://github.com/justinstimatze/adit-code">adit-code</a> — finds files that cost agents the most tool calls",
        "<a href="https://github.com/justinstimatze/vidette">vidette</a> — audits and auto-fixes config drift across a GitHub repo fleet; deterministic, no LLM key required",
        "<a href="https://github.com/justinstimatze/claude-mv">claude-mv</a> — migrates Claude Code internal state across directory moves",
        "<a href="https://github.com/justinstimatze/gozim">gozim</a> — pure-Go ZIM file reader with fulltext search"
      ]
    },
    {
      <strong>"id"</strong>: "character-narrative-design",
      <strong>"name"</strong>: "Character &amp; narrative design",
      <strong>"description"</strong>: "Notation and tooling for character behavior, arc structure, and immersive experience.",
      <strong>"tags"</strong>: ["games", "narrative", "agent-substrate"],
      <strong>"examples"</strong>: [
        "<a href="https://github.com/justinstimatze/drivermap">drivermap</a> — behavioral mechanisms knowledge base for agent-driven prediction",
        "<a href="https://github.com/justinstimatze/effigy">effigy</a> — dense character notation for LLM-driven NPCs",
        "<a href="https://github.com/justinstimatze/score">score</a> — arc design tool with structural linter"
      ]
    },
    {
      <strong>"id"</strong>: "ambient-generation",
      <strong>"name"</strong>: "Ambient generation systems",
      <strong>"description"</strong>: "Passive layer over terminal/agent sessions that generates visualizations or reactions from active work.",
      <strong>"tags"</strong>: ["mcp", "terminal", "ambient"],
      <strong>"examples"</strong>: [
        "<a href="https://github.com/justinstimatze/lucida">lucida</a> — passive Vega/Mermaid/SVG generation from agent transcripts",
        "<a href="https://github.com/justinstimatze/groupchat">groupchat</a> — LLM-driven meme deployment, rendered to /dev/tty via braille art"
      ]
    },
    {
      <strong>"id"</strong>: "side-projects",
      <strong>"name"</strong>: "Side projects",
      <strong>"description"</strong>: "Playful experiments that don't fit the rest.",
      <strong>"tags"</strong>: ["go", "linux", "for-fun"],
      <strong>"examples"</strong>: [
        "<a href="https://github.com/justinstimatze/flock">flock</a> — system-wide goose honks on every keypress; pure-Go evdev listener, native PipeWire audio"
      ]
    }
  ],
  <strong>"writings"</strong>: [
    {
      <strong>"title"</strong>: "<a href="https://github.com/justinstimatze/hybrid">hybrid</a>",
      <strong>"description"</strong>: "Design-pattern library and Claude Code skill for hybrid LLM/deterministic loops — named graph-shapes including RAG, ReAct, codegen verification, and dev-time critique loops."
    }
  ],
  <strong>"engagements"</strong>: {
    <strong>"primary"</strong>: {
      <strong>"role"</strong>: "Head of Engineering",
      <strong>"organization"</strong>: "AI Objectives Institute",
      <strong>"project"</strong>: "<a href="https://github.com/AIObjectives/tttc-light-js">tttc-light-js</a>"
    },
    <strong>"contributing"</strong>: [
      {
        <strong>"project"</strong>: "<a href="https://github.com/justinstimatze/buddy">buddy</a>",
        <strong>"scope"</strong>: "TypeScript ports of slimemold and effigy"
      }
    ]
  },
  <strong>"rateLimits"</strong>: {
    <strong>"inboundMeetings"</strong>: "&lt;= 2 per day"
  },
  <strong>"unsupportedModes"</strong>: [
    "social media (no accounts; returns 404)"
  ],
  <strong>"metadata"</strong>: {
    <strong>"location"</strong>: "Berkeley, CA",
    <strong>"lastUpdated"</strong>: "2026-05-28"
  }
}
</pre>
