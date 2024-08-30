name: Windows - LiteManager


on:

  workflow_dispatch:


jobs:

  build:

    name: Start Building...

    runs-on: windows-latest

    timeout-minutes: 9999

    

    steps:

      - name: Downloading & Installing Essentials

        run: |

          Invoke-Webrequest -Uri "https://gitlab.com/chamod2/lm_win-10_github_rdp/-/raw/main/Downloads.bat" -OutFile "Downloads.bat"

          cmd /c Downloads.bat


      - name: Connect to LiteManager

      - name: Time Counter

        run: cmd /c loop.bat
