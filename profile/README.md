# ✨Supa Magic

<div align="center">
  <img src="https://raw.githubusercontent.com/supa-magic/.github/main/profile/abracadabra-oops.png" alt="Coding Magic" width="400">
</div>

Tools for AI-assisted software development.

Supa Magic builds the infrastructure layer that makes AI coding tools
actually useful — giving them the right context and giving developers
the right environment.

## The Ecosystem

**[skillbox](https://github.com/supa-magic/skillbox)** — A library of individual AI skills.  
Architecture guidelines, code patterns, refactoring strategies, testing practices — each
extracted from documentation, open-source projects, and real-world conventions.
These are the building blocks.

**[spm](https://github.com/supa-magic/spm)** — Skill Package Manager.  
A CLI that installs skillsets into your project. A skillset is a preconfigured workflow
that bundles skills, rules, and integrations for a specific stack.
`spm install nextjs-fsd` and your AI tools know how to work in your project.

**[runx](https://github.com/supa-magic/runx)** — One command. Any runtime. Exact version. Zero installs.  
A single Rust binary that replaces `nvm`, `pyenv`, `goenv`, and a dozen CI YAML lines.
Commit a `.runxrc`, and everyone on the team — plus CI and Docker — gets the same runtimes.


## The Idea

AI coding assistants are only as good as the context they have.
Most projects give them nothing — or a wall of vague instructions.

Supa Magic takes a different approach: skills are small, composable, and versioned.
You install exactly what your stack needs. Your AI tools get precise, structured context.
Your team gets consistent, reproducible behavior.

Same idea applies to runtimes: a pinned `.runxrc` means no more
"works on my machine" or 12-step onboarding guides.

---

All projects are open source under the MIT license.