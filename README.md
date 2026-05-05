# LLM Wiki
A personal knowledge base maintained by any AI Agent.
Based on Andrej Karpathy's LLM Wiki pattern. It can be used with all types of AI Agents.  
For a nice view you can import this folder as an Obsidian vault. Graph view colors are already configured.

# Folder structure 
- source/ -- source documents (immutable -- never modify these)
- wiki/ -- markdown pages maintained by Claude
- index.md -- table of contents for the entire wiki
- log.md -- append-only record of all operations

# Setup
Simply link the Agent.md file in your Agent's context file (CLAUDE.md, GEMINI.md) in the root directory. Agent.md provides all context needed to execute the wiki workflow. 
Additionally, you could setup custom commands with the provided workflows in `Context/`.
