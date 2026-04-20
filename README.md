# OllamaDetails

powershell to install Ollama

irm https://ollama.com/install.ps1 | iex

cmd command for claude code to install gpt for claude

curl -fsSL https://claude.ai/install.cmd -o install.cmd && install.cmd && del install.cmd
ollama launch claude --model gpt-oss:20b
