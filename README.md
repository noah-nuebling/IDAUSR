# IDAUSR

This repo is a backup of my IDA Pro user directory which is found at `~/.idapro` on macOS.

The most interesting thing here is the IDAPython code which contains powerful tools for debugging and runtime-introspecting Objective-C and Swift code with IDA. [Jun 5 2025]
    
Update: [Aug 2025] 

I think this could be useful for others trying to reverse engineer Swift and Objective-C code, or understanding how their runtime works, so I'm publishing it, now. I hope it helps someone! 

The tools here are useful and powerful, but for most smaller reverse engineering tasks I found myself preferring to step into the Framework assembly with Xcode and have an LLM translate it to pseudocode. (Claude is really good at assembly.) (Maybe this is because I'm not super proficient at IDA Pro, yet.)

Also see:
- Igor's TOTW – user directory: https://hex-rays.com/blog/igors-tip-of-the-week-33-idas-user-directory-idausr
- `Notes dir > Reverse Engineering [Apr 2025].md`

Notes:
- [Jun 5 2025] ! Make sure not to leak anything sensitive ! (In case we publish this repo)
    - [Aug 13 2025] Publishing this now. Nothing sensitive. See `.gitignore`.
- [Apr 19 2025] When I first installed IDA Pro 9.1 earlier today, there was documentation at Help > Help but now it's gone!
