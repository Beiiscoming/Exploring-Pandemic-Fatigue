# 由人類行為與心理探討新冠肺炎疫情下各地區的防疫疲乏

## 背景介紹
本研究探討了新冠肺炎疫情下的防疫疲乏現象，旨在了解人們在疫情期間因應防疫政策的疲勞程度。研究分為行為上的疲乏和心理上的疲乏兩個主要面向，並試圖量化這些疲乏指標。

## 摘要
本研究發現，全球不同地區的人們在疫情期間表現出不同程度的防疫疲乏。行為上的疲乏主要體現在人潮移動和日常習慣的變化，心理上的疲乏則反映在人們的負面情緒和心理健康問題上。

## 研究流程

### 1. 針對防疫疲乏之各面向提出假設定義
- 確定研究的主要面向：人潮移動疲乏、日常習慣疲乏和心理疲乏。
- 為每個面向提出具體的假設，定義每個面向的具體指標。

### 2. 資料蒐集
- **網路爬蟲**：使用爬蟲技術自動蒐集相關數據。
- **申請下載權限**：向數據提供方申請必要的數據下載權限。
- **手動下載**：手動下載所需數據，確保數據的完整性和準確性。
  
| Keywords                          | Dataset                                 | What I utilized                                                | 數據收集方式    | 相關工具/套件                                    |
|-----------------------------------|-----------------------------------------|----------------------------------------------------------------|-----------------|------------------------------------------------|
| Define “a wave” of covid-19 pandemic | Our World in Data                      | New cases per million per day                                  | 網路爬蟲        | Python的Requests套件和Beautifulsoup4套件        |
| **People Movement Fatigue Index** | COVID-19 Community Mobility Report      | Mobility                                                       | 網路爬蟲        | Python的Requests套件和Beautifulsoup4套件        |
| **People Movement Fatigue Index** | Facebook Movement Range Map             | Mobility                                                       | 網路爬蟲        | Python的Requests套件和Beautifulsoup4套件        |
| **People Movement Fatigue Index** | OxCGRT                                  | Stringency value about containment and closure (8 policies)    | 網路爬蟲        | Python的Requests套件和Beautifulsoup4套件        |
| **Daily Habit Fatigue Index**, **Mental Fatigue Index** | CTIS               | 2 Questionnaire answers about daily habit and mental situation | 申請授權後下載  | -                                                |
| **Daily Habit Fatigue Index**     | ICL-YouGov Global Survey                | 8 Questionnaire answers about daily habit                      | 申請授權後下載  | -                                                |


### 3. 資料探勘
- **移動平均**：對數據進行移動平均處理，平滑數據波動。
- **數值代換**：對遺漏值和異常值進行數值代換，確保數據完整性。
- **去除遺漏值**：清理數據中的遺漏值，以提高數據質量。

### 4. 建立一波疫情之定義
- 確定疫情波段的標準，將數據按疫情波段進行分類和處理。

### 5. 各國之疫情波段設定
- 根據前一步的標準，對各國的疫情數據進行波段設定，方便後續分析。

### 6. 根據各面向的假設定義計算人潮移動疲乏指數、日常習慣疲乏指數、心理疲乏指數
- 使用定義的計算方法，計算出每個面向的疲乏指數。

### 7. 得出人潮移動疲乏指數、日常習慣疲乏指數、心理疲乏指數
- 獲得各地區和各面向的疲乏指數數據。

### 8. 將人潮移動疲乏指數、日常習慣疲乏指數、心理疲乏指數可視化
- 使用數據可視化技術，生成圖表展示不同地區和面向的疲乏趨勢。

### 9. 評估人潮移動疲乏指數、日常習慣疲乏指數、心理疲乏指數計算方法之可行性
- 分析計算結果，評估所用方法的可行性和準確性，提出改進建議。

