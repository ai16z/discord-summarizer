# 💻-coders 2024-10-30

## Summary
Discussion focused primarily on the deployment and usage statistics for Eliza. Users sought to identify active deployments across Twitter, Telegram platforms with LevelsDennis providing insights into a few instances including Gcr ai's bot. Additionally, big dookie reported an issue aligning text transcripts from video content intended for LLM use in tweets.

## FAQ
- How many users are using Eliza? Any examples of deployed bots on Twitter or Telegram? (00:54) - 2 responses by whobody and LevelsDennis (asked by [infinite — ai/16z])
- What changed with the video transcript issue for LLM usage in tweets? (asked by [whobody])
- Where does the 'trust score' live that the bot draws its information from? Is it a users SOL address, Discord ID, TG handle etc. and how is that stored and accessed by the bot? (asked by [Dave | Eco](01:30))
- Does anyone got the same problem or am I the only one? (referring to character file import issue in eliza agents using Twitter archive dataset.) (asked by [SotoAlt | WAWE](02:30))
- When I'm trying to run this (not matter if relative path or absolute via /home/etc) I get the following error: 'node --loader ts-node/esm src/index.ts --characters= (asked by [naturevrm])
- related to what? Is there anything else that needs installation? (asked by [naturevrm])
- Try building first and add a types file. (asked by loaf)
- How did you train the character? Did you use Claude and your Twitter history? (asked by @mattyryze (03:19))
- What is morphing visual style into something more human technique used for in training process? (asked by [N/A])
- Can you share a link to the character's Instagram page? (asked by @big dookie (03:24))

## Who Helped Who
- [LevelsDennis, big dookie] helped [infinite — ai/16z] with Identify examples of deployed bots. by providing Provided information on Eliza bot deployments.
- Provided a link for 'trust score' feature implementation helped [Dave | Eco] with Understanding the bot trust system. by providing [dunks41g](02:39)
- Suggested running yarn commands for character file import helped [naturevrm] with Importing a Twitter archive dataset into eliza agents. by providing [dunks41g](02:39)
- [loaf] helped [naturevrm] with Resolving node error when executing script. by providing Loaf suggested trying build before running the command, adding a type file.
- [N/A] helped @naturevrm with Providing information on the project by providing @mattyryze (03:19) asked about training process and @big dookie (03:24) shared a link to character's Instagram page.
- [hiroP] (03:57) helped  with Discussing the possibility of running Discord/Twitter agents asynchronously to handle missed messages when not active by providing [big dookie](04:16)
- @SotoAlt | WAWE helped @hiroP with Setting up a server for independent agent by providing @naturevrm provided a guide to setting up local instance of agents (https://hackmd.io/@reneil1337/homelab) at 04:26
- @SotoAlt | WAWE helped Jb (04:57) with Successful by providing Add Twitter client to character.ts or defaultCharacter.ts
- @big dookie helped @jb with Technical Tasks by providing Resolving Twitter API login error and implementing video upload functionality.
- @leonprou | Ensemble helped @naturevrm with Eliza project by providing Reviewing Based Agents code and offering collaboration on AI agents accessing blockchain tools.

## Action Items

### Technical Tasks
- Investigate Eliza bot deployments on Twitter, Telegram. (mentioned by [infinite — ai/16z])
- Implement 'trust score' feature for bot (mentioned by [Dave | Eco](01:30))
- Resolve character file import issue in eliza agents using Twitter archive dataset. (mentioned by [naturevrm](2:20-2:34))
- Check package.json for yarn commands (mentioned by [dunks411, big dookie])
- Resolve ONNX Runtime version mismatch error (mentioned by [naturevrm](03:14))
- Spin up a Discord bot for Afrika Burn event (mentioned by [naturevrm](03:27))
- Debug the current version of the bot to improve efficiency before launching it for Afrika Burn event (mentioned by [naturevrm](03:28))
- Implement asynchronous communication in Discord/Twitter agents to handle missed messages when not active (mentioned by [hiroP](04:01))
- Run a local instance of an independent agent using Docker with Nvidia support (mentioned by @naturevrm)
- Set X server URL, API keys for Twitter client (mentioned by Jb (04:57))
- Resolve Twitter API login error (mentioned by @jb)

### Documentation Needs
- Update documentation to include character file import instructions for eliza agents (mentioned by [big dookie](2:36))
- Include information about checking YARN COMMANDS in the documentation. (mentioned by big dookie)
- Update documentation to include new character training process and visual style morphing technique. (mentioned by [N/A])
- Consider funding for running Discord bots with GPU support through DAO resources, if feasible (mentioned by [SotoAlt | WAWE](04:08))
- Resolve error in base.ts file at line 199 (mentioned by @SotoAlt | WAWE)

### Feature Requests
- Resolve text transcript alignment issue with video for LLM usage in tweets (mentioned by [big dookie])
- Explore training and improving Hugging Face models for Discord bots (mentioned by [big dookie](04:16))
- Consider implementing Ollama API endpoint in the environment for Eliza docker container without needing nVidia GPU. (mentioned by @naturevrm)
- Implement video upload functionality for agent-twitter client. (mentioned by @big dookie)