# Settings:
  - Move `settings.json` to: `%APPDATA%\Code\User`.

# Keybindings:
  - Move `keybindings.json` to: `%APPDATA%\Code\User`.

# Clang-Format:
  - Download the LLVM installer. make sure to check 'Add LLVM to system PATH'.
  - Move `.clang-format` to the same directory as `main.cpp`.

# Extensions:
  - Move `extensions.txt` to `%USERPROFILE%\Desktop`.<br>
  - run the following command in the VSCode terminal: (try both, one should work (PowerShell - CMD)).<br>
    - `Get-Content "$env:USERPROFILE\Desktop\extensions.txt" | ForEach-Object {code --install-extension $_}`<br>
    - `for /f "tokens=*" %i in (%USERPROFILE%\Desktop\extensions.txt) do code --install-extension %i`
