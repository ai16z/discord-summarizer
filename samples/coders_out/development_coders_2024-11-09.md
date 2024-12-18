# 💻-coders 2024-11-09

## Summary
: In this Discord chat segment, users discussed technical issues related to compiling node_llama_cpp with CUDA. Suggestions were made for improving documentation on HackMD integration (hiroP). Users sought help regarding undefined model errors and the need for GPU/CUDA compatibility when spinning up agents in Eliza.

## FAQ
- How to resolve CUDA-related errors when compiling node_llama_cpp? Is it possible to bypass the need for a GPU or CUDA installation? (asked by [slim, LiveTheLifeTV])
- What is causing an undefined model error and how can we resolve this issue when spinning up agents in Eliza? What are some best practices to follow for building GPT models like gptme? (asked by [LiveTheLifeTV, erb])
- How should one refer to individuals who bring AI/ML agent projects to life, and what might be an appropriate term or title in their bio? What are the roles that support these developers like managers do for pop stars? (asked by [hiroP])
- Is ai16z censorship free? What's the difference between hedgemony and ai16Z code-wise? (asked by @pastd_)
- What are you guys building in Eliza project, any uncensored models running yet? (asked by @arthuryeti)
- Does the swap action need to be added to the actions array in AgentRuntime? Does anyone know if it works for character files (JSON)? (asked by @it's Tenji)
- Why isn’t pnpm run shell finding any shell script? (asked by @yung_algorithm)
- Anyone know how to add a knowledge base folder? Like data ? (asked by slim (08:30))
- Swap action hooked up but not listening. What's wrong? (asked by Tenji (09:50))
- Do I need to edit types.ts or runtime.ts too? (asked by @yung_algorithm)

## Who Helped Who
- [slim] helped (GPU and CUDA compatibility) with Provide guidance on GPU capabilities, installation of the NVIDIA drivers, and usage without requiring a hardware-based solution. by providing [SotoAlt | WAWE]
- @SotoAlt | WAWE & @Tenji helped @pastd_ with AI agent setup by providing Guidance on model selection for AI agents
- @SotoAlt & @Tenji helped How to use the dev command for hot reloading code changes. with Technical assistance by providing @smokyboo
- Ophiuchus (08:37-08:49) helped General Discord chat with Adding knowledge base to the project, fixing undefined error in code for swaps on X. by providing Ophiuchus is working on fixing an undefined error and will push a solution
- @yung_algorithm helped Ophiuchus (10:09) with Technical Tasks by providing Adding import line for Clients
- @Ophiuchus helped yung_algorithm, Tenji (10:37) with Feature Requests by providing Discussed Base_Mint value and undefined handling in agentruntime.
- yung_algorithm helped Tenji with Understanding action hooking by providing yung_algorithm provided Tenji with links to tutorial videos on how to call actions and providers in the platform, which helped him understand better.
- @Tenji helped @Ophiuchus with Swap functionality on the twitter client by providing Tenji offered to help Ophiuchus troubleshoot issues related to swaps through Twitter client.
- [Tenjis username] helped Ophiuchas & ferric | stakeware.xyz with Codebase management by providing Tenji provided advice on manually moving code to avoid breaks and shared experiences about the challenges of keeping up-to-date with main branch changes.
- slim and Bruenu helped Bruenu with Troubleshooting by providing Resolving TypeError during knowledge creation

## Action Items

### Technical Tasks
- Investigate CUDA installation for GPU compatibility (mentioned by [slim, SotoAlt | WAWE])
- Implement a custom action to call an API for info (mentioned by @Bunchu)
- Implement hot reload feature for code changes (mentioned by @smokyboo)
- Specify clients correctly to prevent errors (mentioned by yung_algorithm)
- Add import line for Clients (mentioned by @yung_algorithm)
- Configure actions for generating images, image viewing, video viewing (mentioned by yung_algorithm)
- Resolve SQL parameters issue with getCachedEmbeddings for SQLite (mentioned by @standard)
- Review code changes made by Ophiuchus to ensure stability before production (mentioned by [Ophiuchas username])
- Resolve TypeScript module resolution issues for '@ai16z/eliza' dependencies (mentioned by @Ophiuchus)
- Review and update build system configuration based on provided 'tsconfig.json', specifically focusing on module resolution strategy (mentioned by @Ophiuchus)
- Resolve TypeError: fileChunks not iterable issue during knowledge creation (mentioned by slim)

### Documentation Needs
- Review and update documentation on HackMD integration with Git/Colab for better user experience (mentioned by [hiroP])
- Update the YAML file with new code in Eliza project on latest build. (mentioned by @Tenji)
- Watch tutorial videos on how to call actions and providers in the platform. (mentioned by Tenji, yung_algorithm)
- Consider cutting releases/tags again for better version control and collaboration. (mentioned by [ferric | stakeware.xyz])
- Create a comprehensive document detailing all tools used in the project, as mentioned by @Ophiuchus. (mentioned by @Ophiuchus)
- Review and follow the readme for proper usage of folder2knowledge.js script. (mentioned by coinwitch (ai16z intern))

### Feature Requests
- Add swap action to the actions array on AgentRuntime. (mentioned by @Tenji)
- Determine Base_Mint value or handling undefined in agentruntime. (mentioned by @Ophiuchus)
- Improving Twitter client swap functionality and callback handler to prevent loss of information during trades. (mentioned by @Ophiuchus)