# 参考資料

本文の `[[n]]` と `[資料 n]` の番号は、調査を行った作業場所の参考資料の番号をそのまま使う（飛び番がある）。

- <a id="ref-1"></a>[1] UNDOCUMENTED 9801/9821 Vol.2（メモリ・I/O ポート編）のオンライン版（memsys.txt、io_sasi.txt など）: https://www.webtech.co.jp/company/doc/undocumented_mem/
- <a id="ref-3"></a>[3] NEC「PC-9800 シリーズ テクニカルデータブック HARDWARE 編 1993」（第 1 部 第 6 章「スイッチ」、巻末の資料（ROM 搭載オプションボードのアドレス空間）、第 3 部 第 1 章「拡張用スロットバス」、第 3 部 第 5 章「固定ディスクインターフェイス」361〜366 ページ）
- <a id="ref-5"></a>[5] NEC「PC-9801UX ハードウェアマニュアル」（2.5 節「拡張用スロット」、3 章。I/O 80h、82h の説明）
- <a id="ref-12"></a>[12] Project MPS「PM-DOCE98 技術情報」（SASI スロットと SASI/SCSI スロットの信号）: https://projectmps.net/pmdoce98tech.htm
- <a id="ref-13"></a>[13] Project MPS「SASI の話」: https://projectmps.net/sasi98talk.htm
- <a id="ref-14"></a>[14] radioc.dat「PC-9801 拡張ボードの設定」（PC-9801-27、PC-9801-09）: https://radioc.web.fc2.com/column/pc98bas/pc980109.htm
- <a id="ref-16"></a>[16] bauxite「PC-98x1/disk/ジオメトリ」: https://bauxite.sakura.ne.jp/wiki/mypad.cgi?p=PC-98x1%2Fdisk%2F%A5%B8%A5%AA%A5%E1%A5%C8%A5%EA
- <a id="ref-46"></a>[46] PC-9801UX21 の本体の拡張 ROM（SASI と FDD の拡張 BIOS、サウンド BIOS）のダンプの解析（ダンプと逆アセンブルは公開しない）
- <a id="ref-47"></a>[47] PC-9801-27 の SASI BIOS の ROM（WVF01-01、WVF02-01）のダンプの解析（ダンプと逆アセンブルは公開しない）
- <a id="ref-52"></a>[52] NEC「PC-9800 シリーズ テクニカルデータブック」1986 年版（第 1 部 第 2 章「ハードウェア概説」、第 2 部 第 8 章「フロッピーディスクインターフェイス」）
- <a id="ref-65"></a>[65] X3T9/1226、X3T9.3/143 Rev. 7「Preliminary Draft Proposed American National Standard for Interface between Rigid Disk Drive(s) and Host(s)」（1981-04-20。ドライブとコントローラの間のデバイスレベルのインターフェース）
- <a id="ref-66"></a>[66] ANSI X3T9.3 No. 185「SASI: Shugart Associates System Interface」Rev. E（1982-04-02。Part A が物理、Part B が機能）
- <a id="ref-77"></a>[77] SCSI-2（X3T9.2/86-109 Rev. 10L）の 5 章「Physical characteristics」の写し（表 2、シングルエンドの A ケーブルのコンタクトの割り当て）: https://www.staff.uni-mainz.de/tacke/scsi/SCSI2-05.html
- <a id="ref-88"></a>[88] Seagate「ST506/ST412 OEM Manual」（ST-506 のインターフェースの信号、電気的な仕様、タイミング、カードエッジのコネクタ）
- <a id="ref-91"></a>[91] 情報処理学会 コンピュータ博物館「【日本電気】D3116，D3126固定磁気ディスク装置」: https://museum.ipsj.or.jp/computer/device/magnetic_disk/0040.html
- <a id="ref-92"></a>[92] NEC「D3126 PRODUCT DESCRIPTION」REV. 1（806-520467、1986 年 11 月）の要約
- <a id="ref-103"></a>[103] Texas Instruments「SN74LS682」（8 ビットの大小比較器。P = Q# と P > Q# の出力、Q の入力に 20 kΩ のプルアップ）: https://www.ti.com/product/SN74LS682 、onsemi のデータシート: https://www.electro-tech-online.com/datasheets/sn74ls682-84-88n_onsemi.pdf （2026-10-29 に参照）
- <a id="ref-118"></a>[118] NEC「Intelligent Peripheral Devices Data Book」1989 年版（μPD7261A/B Hard-Disk Controllers の 6-3 ページ〜。命令の表、Format、エラー状態のバイト）: https://bitsavers.mirrorservice.org/components/nec/_dataBooks/1989_NEC_Intelligent_Peripheral_Devices_Data_Book.pdf
- <a id="ref-149"></a>[149] kazzez「NEC 製 SASI-HDD の DIP-SW」（NEC の D3142、D3126、D5146H の SW1、SW2 の 1 台目と 2 台目の設定。2026-11-05 に見た）: https://cf953518.cloudfree.jp/kazzez/furoku/sasidip.htm
- <a id="ref-153"></a>[153] PC-9801UX-31 のコントローラ（基板 134-856238-0-3）のファームウェアの EPROM（DS300B-520）のダンプの解析（ダンプと逆アセンブルは公開しない）
- <a id="ref-154"></a>[154] PC-9801UX21 の実機での測定と読み出し（2026-10-25〜。拡張 ROM の見え方、I/O 31h と 82h、DIP スイッチ、ジャンパ SW7、DEBUG と EXDEB での読み出し）
- <a id="ref-162"></a>[162] NEC Retro「PC-9801 UX」（UX21 の CPU: 80286 10 MHz、副の V30 8 MHz。UX41 の項では V30 を 10 MHz と書いていて食い違う。2026-11-05 に見た）: https://necretro.org/PC-9801_UX
- <a id="ref-163"></a>[163] NEC Retro「PC-9801 VX」（80286 は初め 8 MHz で、VX01、VX21、VX41 は 10 MHz。V30 も載せる。2026-11-05 に見た）: https://necretro.org/VX
- <a id="ref-164"></a>[164] NEC Retro「PC-9801 ES」（ES2: 80386SX 16 MHz、副の V30 8 MHz。2026-11-05 に見た）: https://necretro.org/PC-9801_ES2
- <a id="ref-212"></a>[212] 清十郎「EXDEB」（i8086〜Pentium（MMX）の拡張デバッガ。SYMDEB の流れで、PC-98 と DOS/V の両方で動く。版 1.85（1997-07-17）の exdeb185.lzh と説明書 exdeb.man。2026-11-14 に取った）: https://www.vector.co.jp/soft/dos/prog/se008450.html
