# R2R DAC
![R2R DAC_v2.0_Front](<Images/R2R DAC_v2.0_Front.jpg>)

## 概要 / Overview

**R2R DAC** は、5つのゲート信号を階段状のコントロール電圧（CV）に変換する、2HPサイズのR-2RラダーDACモジュールです。
5つのゲート入力（/2, /4, /8, /16, /32）のON/OFFの組み合わせによって、0〜31段階のステップ電圧を生成する5ビットのデジタル→アナログ変換器として動作します。

クロックディバイダーやゲートシーケンサーと組み合わせることで、周期的な階段波、疑似ランダムなCVパターン、アルペジオ風のピッチ変化、フィルターやVCAのステップモジュレーションなどを簡単に作ることができます。
CV出力にはアッテネーターを備えており、ピッチCVからモジュレーション用途まで、パッチに合わせて出力レベルを調整できます。

**Update:** v2.0では、v1.0の4ビット仕様から5ビット仕様へ変更され、生成できるステップ数が16段階から32段階に拡張されました。

**R2R DAC** is a compact 2HP R-2R ladder DAC module that converts five gate signals into stepped control voltages (CV).
By combining the ON/OFF states of the five gate inputs (/2, /4, /8, /16, /32), it functions as a 5-bit digital-to-analog converter capable of generating 32 discrete voltage steps (0–31).

When paired with clock dividers or gate sequencers, it can create stepped waveforms, pseudo-random CV patterns, arpeggio-like pitch movement, or stepped modulation for filters, VCAs, and other CV destinations.
The CV output is equipped with an attenuator, allowing the output level to be adjusted for anything from pitch control to general modulation use.

**Update:** In v2.0, the design has been updated from the 4-bit configuration of v1.0 to a 5-bit R-2R DAC, expanding the available resolution from 16 steps to 32 steps.


## 仕様 / Spec
- Format: Eurorack
- Function: R2R DAC
- Current needs: +12V: 15mA, -12V: 15mA
- Width: 2 HP
- Depth: 28mm (including power connector)


## 販売 / Sales

StudioKATオフィシャルショップで販売しています。(日本国内限定)  
https://www.studiokat.jp/items/149564763


## ライセンス / License

この作品は [Creative Commons 表示 - 継承 4.0 国際 (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/deed.ja) の下でライセンスされています。  
This work is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).


## クレジット / Credits

- Designed by : StudioKAT
- Website : https://www.studiokat.jp/
- GitHub : https://github.com/StudioKAT
- X(Twitter) : https://x.com/StudioKAT_synth
- Instagram : https://www.instagram.com/studiokat_modular/

## 更新履歴 / Changelog

- `2025-11-22` v1.0 Released version 1.0
- `2026-07-05` v2.0 Released version 2.0