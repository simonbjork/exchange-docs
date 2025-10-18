
Download the `ExchangeNuke.zip` file and extract it.

**Basic Installation:**

Copy the `ExchangeNuke` directory to your `~/.nuke` folder.

In the `.nuke` directory, edit or create an `init.py` file and add:

```
import nuke
nuke.pluginAddPath('./ExchangeNuke')
```

Restart Nuke. The "ex" icon will appear in the nodes toolbar.



**Recommended installation (custom directory)**

For better organization, set up a global plugins directory. In this example we will use `D:/tools/nuke`, but it could also be on a server or shared Dropbox directory.

Create a `python` subdirectory and copy `ExchangeNuke` into it.

In `D:/tools/nuke`, create an `init.py` file with:
```
import nuke
nuke.pluginAddPath('./python/ExchangeNuke')
```

Ensure Nuke scans the custom tools directory at startup:
   
   - **Option 1:** Add this to your `.nuke/init.py`:

```
import nuke
nuke.pluginAddPath('D:/tools/nuke')
```

   - **Option 2:** Set the `NUKE_PATH` environment variable to `D:/tools/nuke`.

**Note:** Use forward slashes (`/`) or double backslashes (`\\`) even on Windows.