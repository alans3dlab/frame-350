# Alan's 3D Lab — Voron 350 主體機構／Voron 350 main frame

版本 v0.2 測試版・2026-11-14　（Version v0.2, test release, 2026-11-14）
網頁 Page：https://www.voron.com.tw/works/frame

## 開放測試中 檔案免費下載・尚未經過實機驗證
這是我正在一步一步列印、組裝、改裝中的設計，先把完整模型和檔案開放出來，給想一起測試的人參考。
我自己還沒完成實機驗證，之後可能會有修正檔更新；全部組裝好之後，會補上實機照片。

## 下載須知
這是測試分享，不保證能直接用；請自行評估、自負列印與使用風險。發現問題歡迎回報，修正後會在更新紀錄寫清楚改了什麼。
回報問題：LINE https://line.me/ti/p/gBlruyjDjE

## 授權
修改說明：本資料夾的零件是 Alan 為自己的 Voron 2.4 350 機台設計、修改的列印件（2026 年），整體機台設計來自 Voron Design。GPL-3.0 全文在 LICENSE.txt。
根據 Voron Design 官方設計修改，沿用 GPL-3.0 授權；原始設計版權屬於 Voron Design。
Voron Design 官方網站：https://vorondesign.com
Voron 2.4 官方設計（GitHub）：https://github.com/VoronDesign/Voron-2
GPL-3.0 授權條款：https://www.gnu.org/licenses/gpl-3.0.html
v0.2 的鉸鏈、把手、門扣改自 chrisrgonzales「270° Front Panel Hinge」（GPL-3.0）；Z 皮帶蓋改自 Akio 的 V2.4 Z 皮帶蓋（Voron Mods，GPL-3.0）：https://mods.vorondesign.com/details/LzEFU0RDHXUarF7y69x2Q

## 建議列印參數
材料：ASA 或 ABS；少數件建議 TPU 或 PETG，寫在各零件卡片上。
噴嘴與線寬：0.4 mm 噴嘴，線寬 0.4 mm
層高：0.2 mm
外牆：4 圈
頂層與底層：各 5 層
填充：40%（網格、Gyroid 或立方體）
擺放與支撐：檔案已轉成建議的列印方向，直接切片；有些零件接觸面小或有懸空，依切片軟體提示加支撐（只從列印板長出即可）。
先試一件：先印一件小零件，確認尺寸和螺絲配合再印整套。

## 內容 STL/ 資料夾裡是全部 50 件列印件，parts.csv 是零件清單（名稱、建議材料、配色、重量、外形尺寸）。
這裡是我自己設計的列印件。Voron 原本的標準列印件請到 Voron 官方 GitHub 下載；購買的零件不在這裡。

## 更新紀錄
v0.2 測試版（2026-11-14）
・新增前門與加高框罩相關列印件 16 種（STL），其中 10 種附 STEP 方便修改：270° 前門鉸鏈（門側夾板、背板、固定座）、門把手（上左右、下左右）、上樑磁吸門扣、Z 皮帶蓋（A／B 鏡像）、框罩角座（A／B）、座圈填塊（前、側）、換頭線束梳座與磁吸壓蓋。
・v0.1 的 50 件主體列印件照舊在 v0.1；v0.1 裡舊的 12 件加高框檔案已由本版取代。
・授權：全部 GPL-3.0。鉸鏈、把手、門扣改自 chrisrgonzales 的「270° Front Panel Hinge」（GPL-3.0，鉸鏈加厚到 2 mm）；Z 皮帶蓋改自 Akio 在 Voron Mods 發表的 V2.4 Z 皮帶蓋（GPL-3.0，https://mods.vorondesign.com/details/LzEFU0RDHXUarF7y69x2Q），加上 Voron LOGO；其餘為 Alan 自行設計。尚未經過實機驗證。
v0.1 測試版（2026-11-06）
・第一次開放測試下載：50 件列印件 STL。
・已知問題：9 件側裙蜂窩框有幾條邊同時接著兩個面（非流形邊），常用切片軟體會自動修好；左右提手墊、穿牆斜角座、拖鏈下固定塊 4 件的底面有 0.1 到 0.2 mm 高低差，第一層建議加 brim。

------------------------------------------------------------

[Open testing] Free download. Not yet verified on a real machine.
This is a design I'm printing, assembling and modifying step by step. I'm sharing the full model and files now for anyone who wants to test it with me.
I haven't finished testing it on a real machine yet, so fixes may follow. Once everything is assembled, I'll add photos of the real build.

[Before you use these files]
This is a test share and may not work as-is. Please judge for yourself; printing and use are at your own risk. Problem reports are welcome, and every fix will be described in the changelog.
Report a problem on LINE: https://line.me/ti/p/gBlruyjDjE

[License]
Notice of modification: the parts in this folder were designed or modified by Alan in 2026 for his own Voron 2.4 350 build; the machine design comes from Voron Design. The full GPL-3.0 text is in LICENSE.txt.
Modified from the official Voron Design design and licensed under GPL-3.0, as the original is. Copyright in the original design belongs to Voron Design.
Voron Design website: https://vorondesign.com
Official Voron 2.4 design (GitHub): https://github.com/VoronDesign/Voron-2
GPL-3.0 license text: https://www.gnu.org/licenses/gpl-3.0.html
In v0.2, the hinge, handles and latch are derived from chrisrgonzales' "270° Front Panel Hinge" (GPL-3.0); the Z belt covers are derived from Akio's V2.4 Z belt cover (Voron Mods, GPL-3.0): https://mods.vorondesign.com/details/LzEFU0RDHXUarF7y69x2Q

[Suggested print settings]
Material: ASA or ABS. A few parts suit TPU or PETG; see each part card.
Nozzle and line width: 0.4 mm nozzle, 0.4 mm lines
Layer height: 0.2 mm
Walls: 4
Top and bottom layers: 5 each
Infill: 40% (grid, gyroid or cubic)
Orientation and supports: Files are already in the suggested print orientation, so slice them as they are. Some parts have a small footprint or overhangs; add supports where the slicer suggests (from the build plate only is enough).
Test first: Print one small part first to check sizes and screw fits before printing the full set.

[Contents] STL/ holds all 50 printed parts; parts.csv lists name, material, color, weight and size.
These are the printed parts of my own design. Get the standard Voron printed parts from the official Voron GitHub; bought parts are not included.

[Changelog]
v0.2 test release (2026-11-14)
- Adds 16 printed parts for the front doors and the raised hood (STL); 10 of them also come as STEP for editing: 270° front-door hinge (door plate, back plate, mount), door handles (upper L/R, lower L/R), magnetic door latch, Z belt covers (A/B mirrored), hood corner blocks (A/B), sill fillers (front, side), and the toolchanger cable comb with its magnetic cap.
- The 50 main-frame parts stay in v0.1; the 12 old hood-riser files in v0.1 are superseded by this release.
- License: all GPL-3.0. Hinge, handles and latch are derived from chrisrgonzales' "270° Front Panel Hinge" (GPL-3.0; hinge thickened to 2 mm). The Z belt covers are derived from Akio's V2.4 Z belt cover on Voron Mods (GPL-3.0, https://mods.vorondesign.com/details/LzEFU0RDHXUarF7y69x2Q) with a Voron logo added. Everything else is Alan's own design. Not yet verified on a real machine.
v0.1 test release (2026-11-06)
- First open-test release: 50 printed parts as STL.
- Known issues: 9 honeycomb skirt frames have a few edges shared by more than two faces (non-manifold); common slicers repair this automatically. The two handle pads, the wall-pass collar and the lower drag-chain mount have 0.1 to 0.2 mm steps on their bottom face, so add a brim.

## 下載 Downloads

| 版本 | 下載 |
| --- | --- |
| v0.2 測試版（前門、加高框罩新零件） | [逐件檔案 / individual files](https://github.com/alans3dlab/frame-350/releases/tag/v0.2) |
| v0.1 測試版 | [整包 zip / all files](https://github.com/alans3dlab/frame-350/releases/download/v0.1/alans3dlab-frame350-v0.1-stl.zip) · [逐件檔案 / individual files](https://github.com/alans3dlab/frame-350/releases/tag/v0.1) |

網頁 Page：https://www.voron.com.tw/works/frame
