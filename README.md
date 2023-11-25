# VS-Code-SetUp
Configuration of VS code for c++ C python 



{
    "breadcrumbs.enabled": false,
    "C_Cpp.clang_format_path": "/usr/bin/clang-format",
    "C_Cpp.default.cppStandard": "c++17",
    "C_Cpp.default.cStandard": "c11",
    "C_Cpp.default.intelliSenseMode": "clang-x64",
    "C_Cpp.intelliSenseCacheSize": 0,
    "C_Cpp.updateChannel": "Insiders",
    "code-runner.customCommand": "cd $dir && cf-test $fileName",
    "code-runner.executorMap": {
        "c": "cd $dir && gcc -g -static -std=gnu11 -lm -Wfatal-errors $fileName -o $fileNameWithoutExt && ./$fileNameWithoutExt",
        "cpp": "cd $dir && g++ -static -Wall -Wextra -Wno-unknown-pragmas -pedantic -O2 -Wshadow -Wformat=2 -Wfloat-equal -Wlogical-op -Wcast-qual -Wcast-align -D_GLIBCXX_DEBUG -D_GLIBCXX_DEBUG_PEDANTIC -D_FORTIFY_SOURCE=2 -fstack-protector $fileName -o $fileNameWithoutExt && Get-Content input.txt | ./$fileNameWithoutExt | Set-Content output.txt",
        "python": "cd $dir && py $fileName"
    },
    
    "code-runner.runInTerminal": true,
    "code-runner.saveFileBeforeRun": true,
    "editor.acceptSuggestionOnCommitCharacter": false,
    "editor.acceptSuggestionOnEnter": "on",
    "editor.autoClosingBrackets": "always",
    "editor.autoIndent": "full",
    "editor.find.autoFindInSelection": true,
    "editor.minimap.enabled": false,
    "editor.wordWrap": "wordWrapColumn",
    "editor.wordWrapColumn": 120,
    "explorer.autoReveal": false,
    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false,
    "python.formatting.provider": "yapf",
    "python.linting.enabled": true,
    "python.linting.flake8Enabled": true,
    "python.linting.pylintEnabled": false,
    "terminal.integrated.rendererType": "dom",
    "vsicons.dontShowNewVersionMessage": true,
    "workbench.editor.enablePreview": false,
    "workbench.editor.highlightModifiedTabs": true,
    "workbench.panel.defaultLocation": "right",
    "go.formatTool": "goimports",
    "go.useLanguageServer": true,
    "git.autofetch": true,
    "window.zoomLevel": -1,
    "terminal.integrated.defaultProfile.windows": "PowerShell",
    "workbench.iconTheme": "vscode-icons",
    "files.autoSave": "onFocusChange",
    "workbench.preferredLightColorTheme": "Default Light+"
}
