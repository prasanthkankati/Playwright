<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/785432bb-b99d-4e84-8acf-63d907c9c784" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/afd88e79-8481-4222-a437-d2ef96cee6bb" />
Mee screenshot choosanu. Ee error message **"running scripts is disabled on this system"** ante, mee Windows PowerShell scripts run avvakunda restrict chestundi ani artham. Deenini chala easy ga fix cheyyocha.

Deeniki **rendu options** unnayi:

### Option 1: Command Prompt (CMD) vadi (Fastest & Easiest)
VS Code terminal lo **PowerShell** badulu **Command Prompt** vadithe ee problem radu.
1. VS Code terminal window lo right side, oka chinna **`+`** icon pakkana dropdown arrow (v mark) untundi, adi click cheyandi.
2. Akkada **"Command Prompt"** select cheyandi.
3. Kotha terminal open avthundi. Ippudu malli ee command kottandi:
   ```bash
   npm init playwright@latest
   ```

---

### Option 2: PowerShell Permission Change Cheyatam
Meeru PowerShell lone cheyali anukunte, permission ivvali:
1. Windows Start button click chesi, **"PowerShell"** ani type cheyandi.
2. Danipaina Right-click kotti **"Run as Administrator"** select cheyandi.
3. Aa window lo ee command type chesi **Enter** kottandi:
   ```powershell
   Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
   ```
4. Appudu adigithe **`Y`** (Yes) ani type chesi Enter kottandi.
5. Ippudu VS Code ki velli, malli Playwright command run cheyandi.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6c1268c9-f95c-4c4b-9652-53df41bacc01" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e1ce496f-082f-4cd6-b67d-73ced112d4dc" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9bc1328a-5d78-4466-8f4e-4e7fe17589f0" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/065b1641-49be-44f0-96fc-e2855e1cfded" />

