<!--
  INTENTIONAL HTML: the <pre> wrapper, <strong> keys, and <a href> repo
  links are a design choice. Linters/formatters: DO NOT strip the HTML.
  Without it the JSON-like layout collapses and the repo links go dead.
-->
<pre>
{
  <strong>"name"</strong>: "Justin Stimatze",
  <strong>"description"</strong>: "Agent infra, safety tooling, structured deliberation.",
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
      <strong>"description"</strong>: "Representations and protocols for agent reasoning.",
      <strong>"tags"</strong>: ["multi-agent", "knowledge-base", "static-analysis"],
      <strong>"examples"</strong>: [
        "<a href="https://github.com/justinstimatze/gemot">gemot</a> — structured deliberation MCP server",
        "<a href="https://github.com/justinstimatze/gemotvis">gemotvis</a> — real-time viz for gemot sessions",
        "<a href="https://github.com/justinstimatze/winze">winze</a> — knowledge base that audits its own accuracy",
        "<a href="https://github.com/justinstimatze/calque">calque</a> — finds concepts defined in N places that silently diverged",
        "<a href="https://github.com/justinstimatze/defn">defn</a> — AI-native code database for Go"
      ]
    },
    {
      <strong>"id"</strong>: "agent-calibration",
      <strong>"name"</strong>: "Agent calibration",
      <strong>"description"</strong>: "AI agent miscalibrations: drift, sycophancy, plan gaps.",
      <strong>"tags"</strong>: ["safety", "evaluation", "claude-code", "calibration"],
      <strong>"examples"</strong>: [
        "<a href="https://github.com/justinstimatze/slimemold">slimemold</a> — anti-sycophancy guardrail",
        "<a href="https://github.com/justinstimatze/ismyaialive">ismyaialive</a> — pattern detection against research codebooks",
        "<a href="https://github.com/justinstimatze/plancheck">plancheck</a> — predicts which files agents will miss",
        "<a href="https://github.com/justinstimatze/hindcast">hindcast</a> — calibrated wall-clock priors for Claude Code",
        "<a href="https://github.com/justinstimatze/basanite">basanite</a> — vocab-tic detector for Claude Code output"
      ]
    },
    {
      <strong>"id"</strong>: "agent-infra-tooling",
      <strong>"name"</strong>: "Agent infrastructure &amp; tooling",
      <strong>"description"</strong>: "Tools and libraries for agent runtimes and repo fleets.",
      <strong>"tags"</strong>: ["claude-code", "go", "libraries"],
      <strong>"examples"</strong>: [
        "<a href="https://github.com/justinstimatze/be-my-geminis">be-my-geminis</a> — routes Claude Code image Reads through Gemini Vision",
        "<a href="https://github.com/justinstimatze/saturday">saturday</a> — voice layer; speaks into your tmux pane (experimental)",
        "<a href="https://github.com/justinstimatze/weir">weir</a> — capability layer for Claude Code's Bash habits",
        "<a href="https://github.com/justinstimatze/mcp-dispatch">mcp-dispatch</a> — local inter-agent messaging rail for MCP clients",
        "<a href="https://github.com/justinstimatze/ettle">ettle</a> — surfaces team collisions pre-meeting (experimental)",
        "<a href="https://github.com/justinstimatze/crystal">crystal</a> — routes mechanical work off the frontier LLM (experimental)",
        "<a href="https://github.com/justinstimatze/stull">stull</a> — Claude Code hooks as guarded state machines",
        "<a href="https://github.com/justinstimatze/adit-code">adit-code</a> — finds files that cost agents the most tool calls",
        "<a href="https://github.com/justinstimatze/vidette">vidette</a> — audits and auto-fixes config drift across a repo fleet",
        "<a href="https://github.com/justinstimatze/claude-mv">claude-mv</a> — migrates Claude Code state across directory moves",
        "<a href="https://github.com/justinstimatze/gozim">gozim</a> — pure-Go ZIM file reader with fulltext search"
      ]
    },
    {
      <strong>"id"</strong>: "character-narrative-design",
      <strong>"name"</strong>: "Character &amp; narrative design",
      <strong>"description"</strong>: "Notation and tooling for character behavior, arc design.",
      <strong>"tags"</strong>: ["games", "narrative", "agent-substrate"],
      <strong>"examples"</strong>: [
        "<a href="https://github.com/justinstimatze/drivermap">drivermap</a> — behavioral mechanisms KB for agent-driven prediction",
        "<a href="https://github.com/justinstimatze/effigy">effigy</a> — dense character notation for LLM-driven NPCs",
        "<a href="https://github.com/justinstimatze/score">score</a> — arc design tool with structural linter",
        "<a href="https://github.com/justinstimatze/cupel">cupel</a> — story wish-engines and the grifts that wear their faces"
      ]
    },
    {
      <strong>"id"</strong>: "ambient-generation",
      <strong>"name"</strong>: "Ambient generation systems",
      <strong>"description"</strong>: "Visualizations and reactions from active agent work.",
      <strong>"tags"</strong>: ["mcp", "terminal", "ambient"],
      <strong>"examples"</strong>: [
        "<a href="https://github.com/justinstimatze/lucida">lucida</a> — passive Vega/Mermaid/SVG generation from transcripts",
        "<a href="https://github.com/justinstimatze/groupchat">groupchat</a> — LLM-driven meme deployment as braille art"
      ]
    },
    {
      <strong>"id"</strong>: "side-projects",
      <strong>"name"</strong>: "Side projects",
      <strong>"description"</strong>: "Playful experiments that don't fit the rest.",
      <strong>"tags"</strong>: ["go", "linux", "for-fun"],
      <strong>"examples"</strong>: [
        "<a href="https://github.com/justinstimatze/flock">flock</a> — system-wide goose honks on every keypress (pure-Go evdev)"
      ]
    }
  ],
  <strong>"writings"</strong>: [
    {
      <strong>"title"</strong>: "<a href="https://github.com/justinstimatze/hybrid">hybrid</a>",
      <strong>"description"</strong>: "Design patterns for hybrid LLM/deterministic loops."
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
        <strong>"role"</strong>: "Public AI Research Engineer",
        <strong>"organization"</strong>: "Metagov × Current AI",
        <strong>"project"</strong>: "<a href="https://publicai.co">publicai.co</a>"
      },
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
    <strong>"lastUpdated"</strong>: "2026-06-19"
  }
}
</pre>
