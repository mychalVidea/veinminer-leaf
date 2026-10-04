# VeinMiner – Leaf API Edition (Auto-Sync & Build)

Automatický sestavovací repozitář pro [VeinMiner](https://github.com/2008Choco/VeinMiner) s podporou **Leaf API (26.3)** pro síť **MYCHAL SMP**.

## 🚀 Jak to funguje

Tento repozitář nevyžaduje žádnou manuální údržbu. Pomocí **GitHub Actions** se každý týden automaticky:
1. Stáhne nejnovější kód z oficiálního upstreamu `2008Choco/VeinMiner`.
2. Aplikuje optimalizační záplaty a závislost na `cn.dreeam.leaf:leaf-api`.
3. Zkompiluje hotový plugin `VeinMiner-Bukkit.jar`.
4. Publikuje nejnovější JAR do záložky **[Releases](https://github.com/mychalVidea/veinminer-leaf/releases)**.

## 📥 Stažení nejnovějšího buildu

Nejnovější zkompilovaný JAR najdeš vždy v záložce:
👉 **[Releases / latest-leaf-build](https://github.com/mychalVidea/veinminer-leaf/releases/tag/latest-leaf-build)**

## 🔄 Ruční spuštění sestavení

Kdykoliv autor VeinMineru vydá nový update a nechceš čekat na nedělní automatické sestavení:
1. Přejdi do záložky **Actions**.
2. Vyber workflow **Auto-Sync & Build VeinMiner for Leaf**.
3. Klikni na **Run workflow** -> zelené tlačítko **Run workflow**.
4. Za cca 2 minuty máš v Releases nový čerstvý JAR.
