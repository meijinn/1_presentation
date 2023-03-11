---
marp: true
theme: base
size: 16:9
paginate: true
headingDivider: 2
math: mathjax
header: インターンシップ報告会
footer: 2022/10/04 専攻科インターンシップ報告会

style: |
    section.split {
        overflow: visible;
        display: grid;
        grid-template-columns: 560px 560px;
        grid-template-rows: 100px auto;
        grid-template-areas: 
            "slideheading slideheading"
            "leftpanel rightpanel";
    }

    /* debug */
    section.split h3, 
    section.split .ldiv, 
    section.split .rdiv,
    section.split h3 {
        grid-area: slideheading;
        font-size: 35px;
    }
    section.split .ldiv { grid-area: leftpanel; }
    section.split .rdiv { grid-area: rightpanel; }

---

# インターンシップ報告会

九州工業大学大学院生命体工学研究科
高専インターンシップに参加

###### 明石高専専攻科機械・電子システム工学専攻<br>ME2208 髙橋尚太郎
<!--
_class: lead
_paginate: false
_header: ""
-->

## 発表構成
- インターンシップの参加目的
- 受け入れ先紹介
- 活動内容
- 活動成果
- 感想

## インターンシップの参加目的
<!--
header: ""
-->
- 専攻科修了後の進路検討
→ 大学院の研究・専門分野を学ぶ
- 本科の授業で興味を持った分野の研究を体験する
パワーエレクトロニクス

## 九工大大学院 生命体工学研究科
<!--
header: "受け入れ先紹介"
-->
- 生体機能応用工学専攻
グリーンエレクトロニクス講座
花本研究室 (教科書の著者)
  - M1:3人/M2:1人/D3:1人
- **永久磁石同期電動機の速度制御**
(keyword: センサレス制御・
ベクトル制御)
- 学部無し 外部生を積極的に募集
## 活動内容
<!--
header: ""
-->
- パワーエレクトロニクスの基礎学習
- PMSMのベクトル制御モデルの学習
- PMSMのPI制御モデルの学習
- 実機モータの特性取得
- **実機とシミュレーションの応答特性比較**
- 会社見学(八幡電機精工株式会社)


## パワーエレクトロニクスの基礎学習
<!--
header: "活動成果"
-->
- コンバータ・インバータ回路
  - DC-DC・DC-AC・三相INV
  - Zeta・Cuk・Sepic CONV


- 座学+ソフトウェアSIM
  - 高専の教科書
  学部~大学院生の**講義資料**
  - **PSIMによる動作理解**

## PMSMのベクトル制御モデルの学習
- 交流モータを
直流モデルで制御する研究

- 座学+ソフトウェアSIM
  - 大学院生の**講義資料**
  - MATLAB

## PMSMのPI制御モデルの学習

## 実機モータの特性取得
- Moterware (制御ソフトウェア)
- unitec DTBL-3518X (モータ本体)


## 実機とシミュレーションの応答特性比較
- 実測値からPIゲインを算出
→ シミュレーションに値を代入


## 会社見学 (八幡電機精工株式会社)
- モータの生産工程の見学
- 回転機総合メーカ
- 安川ブランドと自社製品を開発
- 営業→開発設計→製造→試験検査 を一気通貫
  - 電気設計(モータ内部の機構の電気的な設計)
コイルの巻き数、材質、大きさ等を検討

## 感想
<!--
header: ""
-->
- 本科の授業(座学)を深く学べた
  - 教科書で勉強するだけではなくて実機を動かす体験
  → **期待通りに動作させられるか**
- 九工大の授業を体験することができた
- 研究室の雰囲気が自分に合っていると感じた
- **他高専の学生との交流を通じて自分の立ち位置が分かった**