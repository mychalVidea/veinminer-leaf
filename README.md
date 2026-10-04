# VeinMiner – Leaf Edition

> **Auto-synced & compiled fork** of [MiraculixxT/Veinminer](https://github.com/MiraculixxT/Veinminer) for **Leaf / Paper server (Minecraft 26.x)**.  
> No manual maintenance required — GitHub Actions rebuilds it **automatically every week**.

[![Latest Release](https://img.shields.io/github/v/release/mychalVidea/veinminer-leaf?label=latest%20build&color=brightgreen)](https://github.com/mychalVidea/veinminer-leaf/releases/tag/latest-leaf-build)
[![Auto-Build](https://img.shields.io/github/actions/workflow/status/mychalVidea/veinminer-leaf/auto-build.yml?label=auto-build)](https://github.com/mychalVidea/veinminer-leaf/actions)

---

## 📥 Download

Always grab the latest JARs from the Releases page:  
👉 **[Releases → latest-leaf-build](https://github.com/mychalVidea/veinminer-leaf/releases/tag/latest-leaf-build)**

The release includes:
- `veinminer-leaf-{version}.jar` (Core plugin)
- `veinminer-enchant-{version}.jar` (Enchantment addon)

Drop them into your server's `plugins/` folder and restart.

---

## ⚙️ Features

- Built natively for **Paper, Purpur, Leaf, and Folia**.
- Supports modern Minecraft (26.x / Java 25).
- Clean JSON configuration (`settings.json`, `enchantmentSettings.json`, `groups.json`).
- Custom enchantment support with `veinminer-enchant`.
- In-memory high-performance block breaking.

---

## 🔄 How auto-updates work

Every **Sunday at 03:00 UTC** a GitHub Actions runner:
1. Pulls the latest commit from `MiraculixxT/Veinminer` (`main`).
2. Compiles `veinminer-leaf` and `veinminer-enchant` using Java 25.
3. Publishes both JARs to the **Releases** tab (replacing the previous build).

You don't have to do anything — just **watch this repo for releases** (the 👁 Watch button → Custom → Releases).

Want a build right now? Go to **Actions → Auto-Sync & Build VeinMiner for Leaf → Run workflow**.

---

## 🛠️ Compatibility

- **Server software:** [LeafMC](https://github.com/Winds-Studio/Leaf) 26.2 / 26.3, Purpur, Paper, Folia
- **Minecraft version:** 26.2 – 26.3
- **Java:** 25 (LTS)

---

<details>
<summary>🇨🇿 Česky</summary>

### Stažení

Nejnovější zkompilované JAR soubory najdeš v záložce Releases:  
👉 **[Releases / latest-leaf-build](https://github.com/mychalVidea/veinminer-leaf/releases/tag/latest-leaf-build)**

Release obsahuje:
- `veinminer-leaf-{version}.jar` (hlavní plugin)
- `veinminer-enchant-{version}.jar` (enchantment addon)

Vlož je do složky `plugins/` a restartuj server.

### Jak to funguje

Každou neděli v 03:00 UTC GitHub Actions automaticky:
1. Stáhne nejnovější kód z `MiraculixxT/Veinminer`.
2. Zkompiluje `veinminer-leaf` i `veinminer-enchant` přes Java 25.
3. Nahraje hotové JARy do sekce **Releases**.

Nemusíš dělat nic – stačí zapnout notifikace na releases (👁 Watch → Custom → Releases) a vždy uvidíš, kdy vyjde nový build.

Chceš build hned? Jdi do **Actions → Auto-Sync & Build VeinMiner for Leaf → Run workflow**.

</details>
