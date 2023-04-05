# How to get auto-updating mods in MultiMC/PrismLauncher

1. Download the latest release of <https://github.com/packwiz/packwiz-installer-bootstrap/releases>.
2. Place the downloaded file in your MultiMC instance's `minecraft` or `.minecraft` folder.
3. In your MultiMC instance's settings (`Edit Instance` or `Edit` on the right sidebar), go to `Settings`, then `Custom commands`. Toggle on the `Custom Commands` checkbox.
4. Paste the following command in the `Pre-launch command` field: `"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/leservermods/lemodpack-fabric/main/modpack/pack.toml`.
5. Done!
