# Installing the Adventurer's Journal

Installing takes about two minutes. Your computer will warn you once, because the app
isn't from a big company. That warning is expected, and this guide shows you how to get past it.

## What you need
- **A Windows PC or a Mac.** Phones and tablets aren't supported.
- **The installer**, from the [latest release](../../releases/latest) or from your DM. On Windows it ends in `-setup.exe`. On a Mac it ends in `.dmg`.
- **Spotify Premium, if you want music.** This is optional. The journal works fine without it.

## Installing on Windows
1. Save the `-setup.exe` file to your Downloads folder.
2. Right-click the file, choose **Properties**, tick **Unblock** at the bottom of the General tab, and click **OK**. If there's no Unblock box, skip this step.
3. Double-click the file.
4. If a blue box says **"Windows protected your PC"**, click **More info**, then **Run anyway**.
5. Click through the installer. You don't need to change anything.
6. Open **Adventurer's Journal** from the Start menu.

If you click Run anyway and nothing happens, restart your PC, do step 2 again, and try once more.

## Installing on a Mac
1. Double-click the `.dmg` file.
2. Drag **Adventurer's Journal** into the **Applications** folder.
3. Open Applications and double-click the journal. macOS will refuse to open it the first time.
4. Open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to Adventurer's Journal. Confirm with your password.

On older versions of macOS, you can instead right-click the app, choose **Open**, then click **Open** again. You only do this once.

## Your first time in
- Write your name on the **Property of** label on the cover. Then click **Unclasp & open**.
- The book opens to its **Contents**. Use the tabs along the top to reach your journal, character sheet, spells, bestiary, maps, letters, quests and inventory.
- To draw, pick up the quill or another tool from the tray on the left. Dip it in an inkwell on the right.
- **Everything saves by itself.** Next to the page number you'll see "Ink drying…" and then a wax seal. There is no save button.
- Press **F11** for full screen. Press **Ctrl+F** to search and **Ctrl+P** to print or save a PDF.
- Use the gear in the bottom-left corner for sound, ambience and backups. The shelf icon there lets you keep a separate journal for each campaign.

## Music (optional)
The journal can control your own Spotify, but you need **Spotify Premium**. The music plays in your Spotify app, not in the journal.

1. Send your DM the email address you use for Spotify. They need to add you before you can sign in. There's room for 5 players.
2. Open Spotify on your computer.
3. In the journal, click **Play your Spotify** on the right of the desk and sign in.

Closing the journal doesn't stop the music. Pause it in Spotify.

## New versions, backups and removing it
- **New version:** install the new installer the same way. It installs over the old one, and your journal stays as it is.
- **Backups:** the journal keeps copies of itself, once a day by default. You can change this under the gear, in **Keeping**. **Keep a copy now** makes one straight away. **Open a kept copy** brings an older one back as a separate journal.
- **Removing it:** on Windows, go to the gear, then **Uninstall the journal…**. Your journal is kept unless you tick "Delete the application data". On a Mac, drag the app to the Bin.

## If something goes wrong
| What you see | What to do |
| --- | --- |
| Nothing happens after Run anyway | Restart, right-click the file, choose Properties, tick Unblock, and try again |
| macOS says the app "is damaged" | Open Terminal and run `xattr -cr "/Applications/Adventurer’s Journal.app"`, then open it again |
| "The ink won't take" next to the page number | Click **Try again**. If it keeps happening, tell your DM |
| "Some words were still wet" when you open the journal | Click **Restore them** to get back what you wrote just before it closed |
| Spotify won't sign in | Check you have Premium and that your DM has added your Spotify email |
