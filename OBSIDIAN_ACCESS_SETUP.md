# How to Let Claude Code Manage Your Obsidian Vault (Windows)

## The Simple Version

Your Obsidian vault "Karolina vote" is synced to your Windows PC via iCloud.
Claude Code running on your PC has direct filesystem access — no extra setup needed.

## Step 1: Find Your Vault Path

Your iCloud-synced Obsidian vault is most likely at:

```
C:\Users\<YourUsername>\iCloudDrive\iCloud~md~obsidian\Karolina vote
```

If not there, try:

```
C:\Users\<YourUsername>\Apple\CloudDocs\iCloud~md~obsidian\Karolina vote
```

Or open Obsidian, go to Settings > About, and look at the vault path shown there.

## Step 2: Tell Claude Code on Your PC

In your Claude Code session on your computer, just say:

> Can you access my Obsidian vault at C:\Users\<YourUsername>\iCloudDrive\iCloud~md~obsidian\Karolina vote

Replace `<YourUsername>` with your actual Windows username.

Claude Code will then be able to:
- Read all your notes
- Create new notes
- Edit existing notes
- Organize files and folders

Changes will sync via iCloud back to your iPhone automatically.

## Step 3 (Optional): Start Claude Code From the Vault

For even easier access, open a terminal in the vault folder:

```powershell
cd "C:\Users\<YourUsername>\iCloudDrive\iCloud~md~obsidian\Karolina vote"
claude
```

This way Claude Code's working directory IS the vault.

## Important Notes

- Claude Code on your **phone** (this cloud session) CANNOT access the vault directly
- Claude Code on your **PC** CAN access it because it runs locally with filesystem access
- Any changes Claude makes will sync through iCloud to all your devices
- Back up your vault before letting Claude make bulk changes
