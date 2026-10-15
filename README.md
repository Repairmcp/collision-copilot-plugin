# Collision CoPilot for Claude

The Claude plugin for Collision CoPilot, BainbridgeAI's collision repair research connector: the BainbridgeAI collision playbooks, DEG inquiries, NHTSA recalls and complaints, federal law and the shop's home-state law, every answer with citations the shop can open. The plugin is free to install. Using it requires a paid Collision CoPilot shop subscription and a named-user seat: https://collisioncopilot.com/

## Install in Claude

1. In claude.ai or the Claude desktop app, open Customize > Plugins.
2. Find Collision CoPilot under Discover, or choose Add > Add marketplace, enter `Repairmcp/collision-copilot-plugin`, and add Collision CoPilot from the list.
3. Open the plugin's Connectors tab, add Collision CoPilot and connect it with your CoPilot sign-in email. It is one click when your CoPilot account page is open in the same browser.
4. Follow the setup path on your account page for the project and the test question: https://collision-copilot.bainbridgeai.ai/account

Claude Code: `claude plugin marketplace add Repairmcp/collision-copilot-plugin`, then `claude plugin install collision-copilot@bainbridgeai`.

## What is in this repository

- `plugins/collision-copilot/`: the plugin. Its manifest, the connector address, the skill that tells Claude how to use CoPilot, a README and the license.
- `.claude-plugin/marketplace.json`: the catalog that lets Claude add this repository as a marketplace.

These files are generated from the Collision CoPilot server build and published here unchanged, so a shop that uploads the plugin from its account page and a shop that installs it from here get the same plugin. Changes are made in the server repository, not here.

## Data

Claude sends each tool call's arguments (a research question, a citation, a vehicle identifier when you ask for a recall check) to the Collision CoPilot server. The connector returns reference text and citations and stores usage counts per named user, never conversation text. Privacy policy: https://collision-copilot.bainbridgeai.ai/privacy. Terms: https://collision-copilot.bainbridgeai.ai/terms.

## Support

Email support@bainbridgeai.ai. Account, billing and setup questions are answered from your account page at https://collision-copilot.bainbridgeai.ai/account.

## License

Proprietary. See LICENSE. Collision CoPilot is an independent BainbridgeAI product and is not affiliated with or endorsed by Microsoft.
