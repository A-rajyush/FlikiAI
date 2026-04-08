How to use it

Type a task (or click a suggestion chip) in the task input box
Hit Run Agent to watch the full autonomous pipeline execute
The system auto-detects task type and picks the right scenario

What you'll see

Reasoning steps (purple) — the agent's internal chain-of-thought before acting
Action steps (blue) — tool calls with arguments like web_search, code_executor, memory_store
Result steps (green) — outputs returned from tools or sub-agents
Task Graph — live node-by-node progress on the right panel
Working Memory — key-value store the agents write to across steps
Session Metrics — steps, tool calls, tokens, and runtime tracked live

Three built-in scenarios trigger automatically based on your task:

🔬 Research tasks → web search + synthesis pipeline
⚙️ Build tasks → code generation + testing + security review
📊 Data tasks → profiling + cleaning + statistical analysis + pattern detection
