# CFB 27 Playoff Room

**Run 33-64 team playoffs in a College Football 27 dynasty you already have (PC).**

The Playoff Customizer mod (1.1.0 or later) can run playoffs of 33 to 64 teams, but only in a dynasty that had room
for the extra games when it was created. A dynasty started without the mod doesn't have that room. CFB 27 Playoff Room
gives it the room, so you can keep your dynasty instead of starting over.

- **One click per dynasty.** The app lists your dynasties and shows which ones have the room. Click **Make room**.
- **Your autosave too.** The dynasty's `-AUTOSAVE` gets the same change, so it doesn't matter which one you load.
- **Nothing else changes.** It only adds empty space to the list of the season's games: 970 slots in a normal
  dynasty, 1152 in one created with the mod. Teams, players, schedules and settings stay as they are.
- **Backed up and checked.** Every save is backed up before it changes, and the change is checked by reading the save
  back before it replaces the original.

---

## What you need

- **College Football 27 on PC.**
- **The Playoff Customizer mod, 1.1.0 or later**, installed in the Mod Manager. This app only makes the room; the mod
  runs the playoff.

---

## How to use it

1. **Close College Football 27.** The game saves its own copy over any change made while it runs, so the app won't
   work while the game is open.
2. Unzip the download anywhere you like and double-click `CFB 27 Playoff Room.exe`. A black window opens and your
   browser opens the app. Keep the black window open while you use it.
   Windows may warn about an unknown app the first time (it is not signed): click **More info**, then **Run anyway**.
3. Find your dynasty and click **Make room**. **Ready** means it has the room.
4. Start the game with the Playoff Customizer installed and load the dynasty.
5. **If the dynasty was started without the mod, advance one week first.** The mod sets up its settings when a week
   begins, so until then they are greyed out. Settings can be changed in the preseason and in weeks 1 to 15.
6. In **League Settings > Playoff Customization**, set **Playoff Format** to **Custom**, then pick the number of
   **Playoff Teams**.

| Badge | Meaning |
|---|---|
| **Ready** | The dynasty has room for 33-64 teams. |
| **Partly ready** | Made with an older version of the mod: room in most seasons only. **Make room** finishes it. |
| **Needs room** | A normal dynasty. Not enough room for 33-64 teams until you click **Make room**. |

The app finds your saves folder by itself (Documents, OneDrive or a moved Documents folder). If it can't, click
**Choose the saves folder** and pick the folder with your `DYNASTY-` files.

---

## Stuck dynasty? (Advance or other actions are gone, rows repeat in Actions)

The game keeps a list of each coach's open actions, and it holds at most 2,048. The Playoff Customizer adds its own
entries to that list every week, and the game only clears them when a new season starts. With a big playoff field
the list can fill up before then, often around National Signing Day, but it can happen during the season too.
When it is full, the game can't add its own actions: **Advance** or the week's actions disappear, and rows such as
**View Playoff Picture** or **Manage Blueprint** repeat (Manage Blueprint won't confirm).

- **Request list** under each save shows how full it is: **OK**, **Filling up** (fix it before Signing Day) or **Stuck**.
- **Fix stuck playoff save** takes the playoff mod's old entries out of the list, keeps the newest Manage Blueprint
  and puts back every game action that couldn't be listed (Advance and the like). It shows a preview first and only changes the save when you click **Apply**. The save and
  its autosave are each checked and fixed on their own, with a backup first. Your playoff settings are kept.

The fix lasts until the list fills up again, usually about once a season with a 64-team field.

---

## Backups and undo

Every change makes a backup first, in `Documents\CFB 27 Save Backups\Playoff Room Backups\` (not inside `saves`:
the EA app syncs that folder to a 1 GB cloud). Files there are named like `DYNASTY-MYTEAM.bak-2026-10-16_14-30-00`.

To undo: close the game, copy the backup into the saves folder and rename it back to the save's name
(`DYNASTY-MYTEAM`), replacing the current file. The app has an **Open the backups folder** button.

---

## Good to know

- Nothing is installed and nothing is sent anywhere. The page only runs on your own computer.
- A save only changes when you click **Make room**. Running it again on a dynasty that already has the room does nothing.
- No `.fbmod` and no game files are changed.
- Delete the folder to remove the app.
