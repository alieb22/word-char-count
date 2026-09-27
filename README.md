# Character Count for Word

A Word task-pane add-in that shows live **characters (with spaces)**, characters (no spaces), and words for the current selection, or for the whole document when nothing is selected. Everything runs locally inside Word; no document text leaves the app.

## Install (Mac)

```bash
mkdir -p ~/Library/Containers/com.microsoft.Word/Data/Documents/wef
cp manifest.xml ~/Library/Containers/com.microsoft.Word/Data/Documents/wef/
```

Restart Word, then click **Home → Character Count**. If the button doesn't appear, look under **Home → Add-ins → My Add-ins → Developer Add-ins**.
