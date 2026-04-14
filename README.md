🔐 SecVault (VAULT)

SecVault is a client-side encrypted password manager built with modern web technologies. It allows you to securely store passwords, images, seed phrases, and notes using strong cryptographic standards — all locally in your browser.

⸻

🚀 Features

🔑 Multi Authentication Methods
	•	Alphanumeric Master Password
	•	🌱 Seed Phrase (BIP-39 based)
	•	📱 TOTP (Authenticator-based login)
	•	Optional 2FA for password accounts

🔒 Strong Security
	•	AES-256-GCM encryption
	•	Argon2id (preferred) with PBKDF2 fallback
	•	Zero server interaction (localStorage only)
	•	Memory-hard key derivation

📦 Entry Types
	•	🔑 Passwords (with strength meter & generator)
	•	🖼️ Images (compressed & encrypted)
	•	🌱 Seed phrases (12/24 words)
	•	📝 Secure notes

🧠 Smart UX
	•	Multi-user support
	•	Avatar-based account selection
	•	Auto-lock after inactivity
	•	Clipboard auto-clear (30s)
	•	Search & filtering
	•	Expandable content (images, notes, seeds)
	    Contains Particle motion with cursor sensitive in the background

📲 TOTP Integration
	•	QR-based setup
	•	Compatible with Google & Microsoft Authenticator
	•	Time-based verification (30s window)

⸻

🛠️ Tech Stack
	•	HTML, CSS, Vanilla JavaScript
	•	Web Crypto API
	•	Argon2 (via CDN)
	•	QRCode.js
	•	BIP-39 wordlist

⸻

🔐 Security Model
	•	All data is encrypted before storage
	•	Encryption key derived from user credentials
	•	No backend, no tracking, no data leakage
	•	Seed phrases & passwords are never recoverable

⚠️ Important: If you lose your credentials, your data is permanently unrecoverable.

⸻

📁 Storage

Data is stored locally using:
	•	localStorage
	•	Encrypted blobs per user
	•	Separate salts and authentication data

⸻

📤 Export
	•	Encrypted JSON (recommended)
	•	Plain text (⚠️ insecure, for emergency use only)

⸻

⚙️ Features in Detail

🔄 Auto Lock
	•	Locks after 5 minutes of inactivity

🔍 Search & Filter
	•	Filter by type: Passwords, Images, Seeds, Notes
	•	Instant search across entries

🎲 Generators
	•	Random strong password generator
	•	Mnemonic-style password generator

⸻

🚧 Limitations
	•	No cloud sync (by design)
	•	Data tied to browser/device
	•	Clearing browser storage will erase data

⸻

📌 Usage
	1.	Open the app in your browser
	2.	Create an account (Password / Seed / TOTP)
	3.	Add entries securely
	4.	Lock/unlock anytime

⸻

🧪 Future Ideas
	•	Encrypted cloud backup
	•	Browser extension
	•	Biometric unlock
	•	Dark/light theme toggle
	•	Sharing vaults securely

⸻

⚠️ Disclaimer

This is a local-first security tool. You are responsible for:
	•	Backing up your encrypted data
	•	Safely storing your credentials

⸻

💡 Inspiration

I saw my mom struggling to save passwords in one place so i made one local to save passwords and all kinds of notes and types.

Built for users who want:
	•	Full control over their secrets
	•	No reliance on third-party servers
	•	Maximum privacy with strong cryptography

  
