### The Zen of Claude Code

1. Use the CLAUDE.md to set claude into default 'tutor mode'
   
    a. Use claude in tutor mode first; have constructive back and forth on the understanding and planning of the work
   
    b. If implementing with claude, explicitely instruct claude to implement only after discussing with claude in tutor mode
   
2. If implementing with claude, ensure the feature has existing example(s) in the codebase

    a. If something is new inside the codebase (architecture/feature), ensure you implement it manually first; don't rely on an agent to drive the direction (see 2b)
   
    b. To automate something, it must first be done manually; This applies to agent code generation as well
   
3. Don't be overly reliant on claude

    a. Always write the first line(s) of code yourself; even if claude finishes the work, it provides critical guidance to the agent

    b. Your skill will degrade if you don't keep writing code (see 1a, 2a, 3a)
  
    c. Aim to automate (with claude) the boring or tedious parts of coding, not the novel (to you) or creative parts (see artists)

