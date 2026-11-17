# Hi, I'm Ubeyde 👋

**Embedded Controller & firmware reverse engineer.** I'm working toward writing EC firmware professionally.

For 6+ years I've worked at the lowest level of laptops: Embedded Controllers, BIOS, and firmware.
Most of that time has gone into reverse engineering EC firmware in Ghidra, mapping how laptops
handle fans, thermals, and power. I'm entirely self-taught: none of this is documented, and AI
tools weren't mainstream when I started.

### 🔧 Highlights
- **Found the EC fan control on Lenovo Legion laptops (2022).** That's the mechanism
  [LegionFanControl](https://www.legionfancontrol.com/) (100k+ downloads) is built on.
- **Reverse engineered the Legion Go 2's fan control (2026)** at the request of the
  LegionFanControl developer. My findings became [LeGo2 Fan Control](https://github.com/Rodpad/LeGo2-Fan-Control),
  a fan control app for SteamOS and Windows.
- **Reverse engineered the ASUS EC mailbox** and contributed it to [PawnIO](https://pawnio.eu/)
  ([PR #58](https://github.com/namazso/PawnIO.Modules/pull/58)), where it was merged. That let
  [G-Helper](https://g-helper.com/experimental/) drop unsafe drivers and an unreliable
  workaround for fan control on ASUS laptops.
- **Built [ITE-EC-Reader](https://github.com/Undervoltologist/ITE-EC-Reader)**, my own read/write
  tool for live inspection and reverse engineering of ITE EC chips.
- **Fixed fan control on newer ASUS EC firmware** with [zephyrusfanfix-24-25](https://github.com/Undervoltologist/zephyrusfanfix-24-25),
  an app that corrects flaws in the stock fan logic.
- **Keep a library of fan tables** ([LaptopFanCurves](https://github.com/Undervoltologist/LaptopFanCurves))
  pulled from EC firmware dumps, including MacBooks, which haven't been properly reverse engineered anywhere else.

### 🤝 Contributions
[PawnIO](https://pawnio.eu/) · [G-Helper](https://github.com/seerge/g-helper) ·
[LenovoLegionToolkit](https://github.com/LenovoLegionToolkit-Team/LenovoLegionToolkit) ·
[LenovoLegionLinux](https://github.com/johnfanv2/LenovoLegionLinux) ·
[LeGo2 Fan Control](https://github.com/Rodpad/LeGo2-Fan-Control) ·
[LegionGen5-6FanControl](https://github.com/Z4ndyz/LegionGen5-6FanControl_WinRing_Smokeless_I-OPortsMethod) · and more

### 🧠 What I work on
- **Firmware & low-level:** Embedded Controllers, BIOS/UEFI, firmware reverse engineering (Ghidra)
- **Thermal design:** fan curve/table design, fan control logic, heatsink modding
- **Acoustics & audio:** speaker & headphone tuning, harmonics, music production (DAWs, audio interfaces), playing instruments
- **Also:** photography & videography since I was 4 📷

### 📫 Contact
[LinkedIn](https://www.linkedin.com/in/ubeyde-bulat-b15677437/) · [Email](mailto:ubulat07@gmail.com)
