# VeinMiner – Leaf API Edition

> **Auto-synced & compiled fork** of [2008Choco/VeinMiner](https://github.com/2008Choco/VeinMiner) for **Leaf server (Minecraft 26.x)**.  
> No manual maintenance required — GitHub Actions rebuilds it **automatically every week**.

[![Latest Release](https://img.shields.io/github/v/release/mychalVidea/veinminer-leaf?label=latest%20build&color=brightgreen)](https://github.com/mychalVidea/veinminer-leaf/releases/tag/latest-leaf-build)
[![Auto-Build](https://img.shields.io/github/actions/workflow/status/mychalVidea/veinminer-leaf/auto-build.yml?label=auto-build)](https://github.com/mychalVidea/veinminer-leaf/actions)

---

## 📥 Download

Always grab the latest JAR from the Releases page:  
👉 **[Releases → latest-leaf-build](https://github.com/mychalVidea/veinminer-leaf/releases/tag/latest-leaf-build)**

Drop it in your server's `plugins/` folder and you're done.

---

## ⚙️ What this does differently

| Feature | Upstream VeinMiner | This fork |
|---|---|---|
| API target | `spigot-api:1.21.3` | `cn.dreeam.leaf:leaf-api:26.3.local-SNAPSHOT` |
| Leaf 26.x compat | ❌ | ✅ |
| Java | 21 | 25 (required by Leaf 26.3) |
| Auto-update | manual | every Sunday + on-demand |

---

## 🔄 How auto-updates work

Every **Sunday at 03:00 UTC** a GitHub Actions runner:
1. Pulls the latest commit from `2008Choco/VeinMiner` (`master`).
2. Patches the build to use `leaf-api` instead of `spigot-api`.
3. Compiles `VeinMiner-Bukkit-{version}.jar`.
4. Publishes it to the **Releases** tab (replacing the previous build).

You don't have to do anything — just **watch this repo for releases** (the 👁 Watch button → Custom → Releases).

Want a build right now? Go to **Actions → Auto-Sync & Build VeinMiner for Leaf → Run workflow**.

---

## 🛠️ Compatibility

- **Server software:** [LeafMC](https://github.com/Winds-Studio/Leaf) 26.2 / 26.3
- **Minecraft version:** 26.2 – 26.3
- **Java:** 25 (LTS)

---

<details>
<summary>🇨🇿 Česky</summary>

### Stažení

Nejnovější zkompilovaný JAR najdeš vždy v záložce Releases:  
👉 **[Releases / latest-leaf-build](https://github.com/mychalVidea/veinminer-leaf/releases/tag/latest-leaf-build)**

### Jak to funguje

Každou neděli v 03:00 UTC GitHub Actions automaticky:
1. Stáhne nejnovější kód z `2008Choco/VeinMiner`.
2. Patchne závislost na `cn.dreeam.leaf:leaf-api` (kompatibilní s Leaf 26.3).
3. Zkompiluje hotový `VeinMiner-Bukkit.jar`.
4. Nahraje ho do sekce **Releases**.

Nemusíš dělat nic – stačí zapnout notifikace na releases (👁 Watch → Custom → Releases) a vždy uvidíš, kdy přijde nový build.

Chceš build hned? Jdi do **Actions → Auto-Sync & Build VeinMiner for Leaf → Run workflow**.

</details>
