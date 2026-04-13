# Huananzhi X99-F8 / T8 / TF BIOS (CX99DE77 ISSUE2)

> **ℹ️ Note / Nota:**
> This BIOS is an exclusive leak from **iEngineer** (BIOS Engineer). 
> *Esta BIOS é um vazamento exclusivo do **iEngineer** (Engenheiro de BIOS).*

## ⚠️ Important Warning (Aviso Importante)

| Language | Instructions |
| :--- | :--- |
| **English** | Use `flash.nsh` with the UEFI Shell and `AfuEFIx64.efi` **only** on CX99DE77 ISSUE2 firmware to switch between CSM and UEFI. In all other cases, use a hardware programmer. |
| **Português (Brasil)** | Use `flash.nsh` com o UEFI Shell e `AfuEFIx64.efi` **apenas** no firmware CX99DE77 ISSUE2 para alternar entre CSM e UEFI. Em todos os outros casos, use um programador de hardware. |
| **Español** | Use `flash.nsh` con UEFI Shell y `AfuEFIx64.efi` solo en el firmware CX99DE77 ISSUE2 para cambiar entre CSM y UEFI. En todos los demás casos, utiliza un programador de hardware. |
| **Français** | Utilisez `flash.nsh` avec UEFI Shell et `AfuEFIx64.efi` uniquement sur le firmware CX99DE77 ISSUE2 pour passer entre CSM et UEFI. Dans tous les autres cas, utilisez un programmateur matériel. |
| **Deutsch** | Verwenden Sie `flash.nsh` mit der UEFI-Shell und `AfuEFIx64.efi` nur bei der CX99DE77 ISSUE2-Firmware, um zwischen CSM und UEFI zu wechseln. In allen anderen Fällen verwenden Sie einen Hardware-Programmer. |
| **Italiano** | Usa `flash.nsh` con UEFI Shell e `AfuEFIx64.efi` solo sul firmware CX99DE77 ISSUE2 per passare tra CSM e UEFI. In tutti gli altri casi, usa un programmatore hardware. |
| **Polski** | Używaj `flash.nsh` z UEFI Shell i `AfuEFIx64.efi` tylko na firmware CX99DE77 ISSUE2, aby przełączać się między CSM a UEFI. We wszystkich pozostałych przypadkach używaj programatora sprzętowego. |
| **日本語** | CSM と UEFI を切り替える場合、`flash.nsh` と UEFI Shell、そして `AfuEFIx64.efi` は CX99DE77 ISSUE2 ファームウェアでのみ使用してください。その他の場合は、ハードウェアプログラマーを使用してください。 |
| **한국어** | CSM과 UEFI 전환은 CX99DE77 ISSUE2 펌웨어에서만 `flash.nsh`, UEFI Shell, `AfuEFIx64.efi`를 사용하십시오. 그 외 모든 경우에는 하드웨어 프로그래머를 사용하세요. |

## 🛠️ Files Included (Arquivos Inclusos)
- `CX99DE77.ROM` - The BIOS ROM file / O arquivo ROM da BIOS.
- `AfuEFIx64.efi` - AMI Firmware Update utility for EFI / O utilitário de atualização da AMI para EFI.
- `flash.nsh` - UEFI Shell script to automate flashing / Script do UEFI Shell para automatizar a gravação.

## 🚀 How to Flash (Como Gravar)
1. Format a USB Flash Drive as **FAT32**. (Formate um pen drive em FAT32).
2. Copy all files (`CX99DE77.ROM`, `AfuEFIx64.efi`, `flash.nsh`) to the root of the USB drive. (Copie os arquivos para a raiz do pen drive).
3. Boot into **UEFI Shell** from your motherboard boot menu. (Inicie o UEFI Shell através do menu de boot).
4. Select your USB drive (usually `fs0:` or `fs1:`). Type `fs0:` and press Enter. (Selecione o pen drive digitando fs0: ou fs1: e pressionando Enter).
5. Type `flash.nsh` and press Enter to start the process. (Digite flash.nsh e aperte Enter para iniciar).
6. **DO NOT turn off your PC during the process!** (NÃO desligue o PC durante o processo!).
