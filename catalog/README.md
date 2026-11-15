# Shared reward list

Every picture in `icons/` is one reward. The file name is the reward's name: `Gold.png` is "Gold".

- **Add:** Add file → Upload files (a reward tile picture, like the ones the tracker posts).
- **Rename:** rename the file.
- **Remove:** delete the file.

`settings.json` (next to this folder) holds settings every app uses:
- `submit_webhook` - a Discord webhook in the owner's submissions channel. New, unnamed rewards from everyone's
  app are posted there for naming. Leave it empty to turn submissions off.

Every Reward Tracker re-reads this every few minutes. What each person tracks, and their totals, stay on their PC.
