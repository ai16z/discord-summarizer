# 💻-coders 2024-11-07

## Summary
The key technical discussions in the discourse were about building an AI Agent for Twitter posts using Eliza, resolving a model redownload issue with version 1.20.0 of the software, switching to grok API due to cost and accessibility concerns related to OpenAI's services.

## FAQ
- Is it feasible/doable using eliza for an AI Agent that posts on Twitter 1 tweet per hour? What would be the cost of using anthropic claude-3.5-sonnet? Answered by @SotoAlt | WAWE: Possible, roughly $0.05 per tweet. (asked by @Binye)
- Does '--characters=characters/' work for loading character in defaultCharacter.ts and why is Client not recognized now? (asked by @Stanly)
- Is Telegram based on Instagram? Has anyone used it before for anything related to the project? What are your experiences with using Telegram in this context? (asked by [big dookie (02:40)])
- Is running npm install eliza necessary, and does it only seem to install old code for an IRC bot? What is the purpose of this installation in our project? (asked by [coinwitch] [ai16z intern (03:39)])
- Does Gm Legends include replies in the Twitter TypeScript script? (asked by Patabrava.eth)
- Is there a simple way to make posts so that only verified accounts can reply? (asked by Cy)
- How does the agent remember Certificate Authority (CA) details? Is it stored in characterFile or prompted during interaction? (asked by @Tenji)
- What are your thoughts on a semi-3D website design for AI16Z, inspired by Matrix rain visuals and brand identity? (asked by @jin)
- Are you coming to Devcon? Who should I say hi to for jin? (asked by @leonprou | Ensemble)
- What are y'all cooking up in terms of tech projects or features right now? What version is Hermes3 405 currently at, and what improvements have been made since the last update? Who should I reach out to for more information on these developments? (asked by @Ophiuchus)

## Who Helped Who
- @Ophiuchus helped General Discord chat members facing this problem. with Resolving eliza package file deletion and re-downloading issues by providing Ophiuchus provided a solution to the model redownload issue by setting everything to version 1.20.0.
- [big dookie, Binye] helped Node version 23.1.0 issue and .env file location with Technical Tasks by providing [Ophiuchus (03:44)]
- [Ophiuchus] helped ModelProvider in character.json and typos causing fallback to default with Technical Tasks by providing [Dorian (06:24)] & [Gozde (06:35, DorianD)],
- Gozde (06:41) helped Patabrava.eth with Troubleshooting File Paths by providing Gozde helped Patabrava.eth by confirming and clarifying file paths for character files.
- @Ophiuchus helped @jin with Discussing potential features for AI16Z's website. by providing Ophiuchus provided feedback about the idea of creating a semi-3D web design.
- @hiroP | Hiro helped @shaw with UE collaboration by providing @hiroP | Hiro helped @shaw with UE stuff by introducing them to a colleague (& Improbable).
- @Dango🍡 helped eliza setup issue with Setting up Ollama for eliza's model usage. by providing @Ophiuchus provided guidance on setting LOCAL_LLAMA_PROVIDER and updating the character file.
- coinwitch (ai16z intern) helped  with Supabase local server confusion by providing ferric | stakeware.xyz suggested ignoring exhaustive instructions and using GitHub repo QuickStart for setup.
- @ferric helped @hiroP with Troubleshooting Discord Bot Issue by providing @hiroP received help from @ferric to troubleshoot discord bot issue.
- @ATH🥭Hivo,@coinwitch helped @jin with Merging Feature by providing @coinwitch and ATH🥭Hivo confirmed XAI merge with Eliza for @jin's discount bot.

## Action Items

### Technical Tasks
- Use grok API instead of OpenAI due to cost and accessibility issues. (mentioned by Ophiuchus)
- Ensure all users are on Node version 23.1.0 (mentioned by [Ophiuchus (03:44)])
- Create models folder for storing model files (mentioned by Ophiuchus (08:02))
- Investigate how to store CA (Certificate Authority) details for agents. (mentioned by @Tenji)
- Implement on-chain tools for AI agents to operate, perform user actions (mentioned by @leonprou | Ensemble)
- Multi chain support development (mentioned by @jin)
- Set LOCAL_LLAMA_PROVIDER to Ollama (mentioned by @Ophiuchus)
- Create a .dev.vars file for character configuration (mentioned by coinwitch (ai16z intern))
- Implement Discord client classes for handling interactions (mentioned by @Ophiuchus)
- Develop a system to detect OS and use default package manager accordingly. (mentioned by jin)

### Documentation Needs
- Adjust .env file path to correctly resolve in the core package, and parse its content into process.env (mentioned by Ophiuchus (08:04))
- Update character file with ModelProvider.OLLAMA set for eliza's model usage. (mentioned by @Ophiuchus)
- Install SQLite instead of Supabase local server setup. (mentioned by ferric | stakeware.xyz)
- Resolve Discord bot issue by importing Clients from types.ts at top of code. (mentioned by @hiroP)
- Fix Docusaurus static site generation error for locale en. (mentioned by @jin)
- Update typedoc.json to include EventEmitter documentation in doc generation process. (mentioned by @Ophiuchus)

### Feature Requests
- Build an AI Agent for posting on Twitter (mentioned by Binye)
- Explore the possibility of creating a semi-3D website design inspired by AI16Z's brand. (mentioned by @jin)
- Merge XAI with Eliza and ensure main functioning as expected (mentioned by [coinwitch, ATH🥭Hivo])
- Implement auto-fill, debugging features within code editor (mentioned by [SotoAlt | WAWE])