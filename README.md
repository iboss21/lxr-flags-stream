# 🚩 LXR Flags — Stream Props

> **Required streaming assets for the [LXR Flags](https://theluxempire.tebex.io/package/7465444) FiveM resource.**

---

## ⚠️ Why does this repo exist?

The **LXR Flags** script is sold exclusively through Tebex:
👉 **[https://theluxempire.tebex.io/package/7465444](https://theluxempire.tebex.io/package/7465444)**

Due to file-size and upload limitations on the CFX/Tebex platform, **custom prop files (`.yft` / `.ytyp`) cannot be bundled inside the Tebex package**. These streaming assets are hosted here on GitHub so customers can download them directly and add them to their server.

> ⚠️ **The script will NOT work correctly without these files.**

---

## 📦 Files Included

| File | Description |
|------|-------------|
| `stream/lxr_flags.ytyp` | Type definition file — registers the custom flag props |
| `stream/prop_flag_ca.yft` | Custom flag prop model (Canada) |
| `stream/prop_flag_mx.yft` | Custom flag prop model (Mexico) |

---

## 🔧 Installation

### Step 1 — Purchase the main script
Buy **LXR Flags** on Tebex:
👉 [https://theluxempire.tebex.io/package/7465444](https://theluxempire.tebex.io/package/7465444)

### Step 2 — Download the stream assets
Download or clone this repository:

**Option A — Download ZIP**
1. Click the green **`< > Code`** button at the top of this page
2. Select **"Download ZIP"**
3. Extract the ZIP

**Option B — Direct file download**
Click each file in the `stream/` folder above → then click the **Download** button (⬇️ raw).

### Step 3 — Add files to your resource
Copy **all files** from the `stream/` folder into the `stream/` folder of your **lxr-flags** resource on your server:

```
resources/
└── lxr-flags/
    └── stream/          ← place files here
        ├── lxr_flags.ytyp
        ├── prop_flag_ca.yft
        └── prop_flag_mx.yft
```

> If a `stream/` folder doesn't exist inside the resource, create one.

### Step 4 — Restart / start the resource
Restart your server or run:
```
ensure lxr-flags
```

---

## ❓ Support

- **Discord:** Join The Lux Empire support server (link provided with your Tebex purchase)
- **Tebex store:** [https://theluxempire.tebex.io](https://theluxempire.tebex.io)

---

## 📜 License

These assets are provided **exclusively for buyers of LXR Flags**. Redistribution, reselling, or re-uploading these files outside of your own FiveM server is strictly prohibited.

© The Lux Empire — All rights reserved.
