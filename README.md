# Settings:
  - Move `settings.json` to: `%APPDATA%\Code\User`.

# Keybindings:
  - Move `keybindings.json` to: `%APPDATA%\Code\User`.

# Clang-Format:
  - Download the MSYS2 from vscode guide c++.
  - Also use Msys2 shell to install clang.
  - Move `.clang-format` to the same directory as `main.cpp`.

# Extensions:
  - Move `extensions.txt` to `%USERPROFILE%\Desktop`.<br>
  - run the following command in the VSCode terminal: (try both, one should work (PowerShell - CMD)).<br>
    - `Get-Content "$env:USERPROFILE\Desktop\extensions.txt" | ForEach-Object {code --install-extension $_}`<br>
    - `for /f "tokens=*" %i in (%USERPROFILE%\Desktop\extensions.txt) do code --install-extension %i`
