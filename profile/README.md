# Pedagogical Agents

This is a place to share agents that have a pedagogical purpose and live inside GitHub repositories. The ambition is to make it easy to browse available agents by subject area and contribute your own agents.

## Why?

Agents are very easy to make. Just plaintext in a file. Anyone with a pedagogical vision can leverage AI wihtout requiring technical skills. The important part is making sure they can operate where the students do their work. 

## Where?

For programmers, this is trivial as our main entry-level tools, like Microsoft's VS Code or GitHub's Codespaces, already have agent harnesses built into them that can bring your ideas to life directly where the student is solving their assignment. Eventually, other tools will embrace this design approach and implement harnesses themselves. The harder parts we still have to figure out, such as is learning with agents effective?

## How?

First, check out an example, like [MiLLy](https://github.com/Pedagogical-Agents/General-Purpose-Agents/blob/main/.github/agents/milly.md).
Things to note:
- View the raw file to see the parts and formatting
- The file has two parts:
  -  a YAML header with metadata (name, description, LLM model and permitted tools
  -  a MarkDown body that describes the purpose, goals, behaviors etc.
- The location is important: `.github/agents/milly.md`
  - This is where CoPilot expects to find agents
  - It is visible to anyone who has access to the repo
  - It can be changed (there are ways around this...I think) 

## Subject Areas

- [General Purpose Agents](https://github.com/Pedagogical-Agents/General-Purpose-Agents)
