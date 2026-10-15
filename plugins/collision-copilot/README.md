# Collision CoPilot

Collision repair research for a subscribing shop, inside Claude: BainbridgeAI's collision playbooks (the shop's method for estimating, supplements, insurer disputes, repairs and running the shop), DEG inquiries, NHTSA recalls and complaints, federal law, and the shop's home-state law, every answer with citations the shop can open.

## Use it

Upload this plugin, then open its Connectors tab and connect Collision CoPilot with your CoPilot sign-in email (one click when your CoPilot account page is open in the same browser). The skill loads on upload and tells Claude to check CoPilot before answering a collision question. Ask shop questions inside a private project whose instructions you copy from your CoPilot account page.

## Data

Claude sends each tool call's arguments (a research question, a citation, a vehicle identifier when you ask for a recall check) to https://collision-copilot.bainbridgeai.ai/mcp. The connector returns reference text and citations. It stores usage counts per named user, never conversation text. A paid CoPilot shop subscription and an active named-user seat are required; see https://collisioncopilot.com/.

Collision CoPilot is an independent BainbridgeAI product and is not affiliated with or endorsed by Microsoft.
