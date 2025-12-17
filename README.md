## How to customize GitHub Copilot (VS Code / IntelliJ / Web)

[About customizing GitHub Copilot responses](https://docs.github.com/en/copilot/concepts/prompting/response-customization?tool=vscode)

[Custom agents in VS Code](https://code.visualstudio.com/docs/copilot/customization/custom-agents)  
[Use prompt files in VS Code](https://code.visualstudio.com/docs/copilot/customization/prompt-files)  
[Use custom instructions in VS Code](https://code.visualstudio.com/docs/copilot/customization/custom-instructions)

## VS Code–specific configurations
### _**Paste the vscode urls in the browser, then it will delegate the command to vscode**_

Auto approve (global) vscode://settings/chat.tools.global.autoApprove  
Disables approval prompts globally (**dangerous**)

Auto approve (terminal) vscode://settings/chat.tools.terminal.autoApprove   
Disables approval prompts for terminal operations

Use instruction files vscode://settings/github.copilot.chat.codeGeneration.useInstructionFiles  
Enables instruction files (should be on by default)

Enable subagent to use custom agents  
chat.customAgentInSubagent.enabled 
Enable support for custom agents in subagents  
