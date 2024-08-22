# How to reproduce the issue

issue: https://github.com/biomejs/biome-vscode/issues/304

1. open `default.code-workspace` in VSCode
2. Edit `directoryA/main.ts` and save it (biome works well)
3. Remove `directoryB/biome.json`
4. Edit `directoryA/biome.json` and save it
5. Edit `directoryA/main.ts` and save it (biome breaks)
