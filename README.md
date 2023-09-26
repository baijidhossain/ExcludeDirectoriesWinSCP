
### To exclude directories in WinSCP open the application and do the following:
1. From the `Login` window click `Tools > Preferences...`;
2. In the `Preferences` window navigate to `Transfer` section in the left side;
3. From the right side click `Add...` button;
4. In the `Add transfer settings preset` window, add a title for your preset in the `Preset description` field;
5. Make sure that `Binary (archives, doc, ...)` is selected under the `Transfer mode` section;
6. Under the `Other` section, at the end of the `File mask:` field, click the `Edit...` button;
7. Add your files to exclude in the `Exclude files:` field, one per line;
8. Add your directories to exclude in the `Exclude directories:` field, one per line;
9. Click `OK` to close the window and to add the file masks;
10. In the `Edit transfer settings preset`, check the `Automatically select the preset when` from the top right and;
11. In the `Remote directory mask:` field add `/` to make this preset load automatically on each host;
12. Now click `OK` and `OK` to close the `Preferences` windows;
13. Done. You can now login to your hosts and start transfering files and folders without worrying.

### Exclude files:
- `.DS_Store`
- `Thumbs.db`
- `Desktop.ini`
- `.ftpquota`
- `*.log`

### Exclude directories:
- `.git`
- `node_modules`
- `.idea`
- `.vscode`
- `_notes`
- `.well-known`
- `cgi-bin`
- `$RECYCLE.BIN`
