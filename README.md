<p align="center">
  <img src="icon.png" width="128" alt="PalaceGrid" />
</p>

<h1 align="center">PalaceGrid</h1>

<p align="center">A desktop client for The Palace chat servers.</p>

<p align="center">
  <a href="https://github.com/glennox2009/palacegrid-releases/releases/latest"><b>⬇ Download the latest version</b></a>
</p>

## What PalaceGrid can do

Everything below works in the current version. The list grows with each release — see the [release notes](https://github.com/glennox2009/palacegrid-releases/releases) for what changed when.

**Connecting**
- Connects to any Palace server: type an address like `palacegrid.com:9998` and it is remembered for next time.
- Works with servers that only accept PalaceChat clients, such as Elite Palaces.
- Pick the name you appear under.
- Checks for updates on startup and shows what's new before installing.

**The room**
- Shows the room and its background, scaled to fit the window.
- Everyone appears as a smiley in their own face and color, with their name underneath.
- Click anywhere in the room to walk there.

**Talking**
- Type in the message bar and press Enter.
- Messages appear as chat bubbles next to the speaker, with the name and the time.
- Start a message with `:` for a thought, `!` to shout in a spiky bubble, or `^` to keep the bubble up. Whispers arrive in a muted, italic bubble.

**Keeping track**
- A chat log below the room with timestamps and names in each speaker's color, resizable, or detached into its own window that stays in front.
- A **Users** list of everyone on the server, showing owners and operators.
- A **Rooms** list with how busy each room is; click one to go there.
- Filter either list by name, and see at a glance which room you are in.

### Not there yet

Props and avatars beyond the smileys, spots and doors you can click, several palaces open at once, and painting. They are on the way.

## Which file do I need?

| System | File |
| --- | --- |
| macOS (Apple Silicon and Intel) | `PalaceGrid_x.y.z_universal.dmg` |
| Windows 10 / 11 | `PalaceGrid_x.y.z_x64-setup.exe` |

## Installing

**macOS:** open the `.dmg` and drag PalaceGrid into Applications. The app is not signed with an Apple developer certificate, so the first time you open it macOS says it is damaged or cannot be opened. Two ways round it:

- Open it once, let the warning appear, then go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway**.
- Or run this once in Terminal:

```
xattr -cr /Applications/PalaceGrid.app
```

**Windows:** run the setup `.exe`. If SmartScreen shows a warning, click **More info → Run anyway**.
