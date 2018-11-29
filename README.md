# rime-bopomofo-symbols

用於中州韻輸入注音和方音符號的輸入法

## 特色

- 幫助拼音習慣用戶鍵入注音符號
- 以 1932 年教育部新國音注音符號形式爲標準
- 支援整體音節音變（例如：ㄓ zhi）
- 支援組合韻母音變（例如：ㄧㄢ yan）
- 支援「ㄧ」的橫排版寫法「丨」
- 支援使用白話字/台羅拼音鍵入方音符號
- 重疊部分按漢語拼音、白話字、台羅拼音的優先級排序
- 支援 5 種注音符號音調和 3 種方音符號音調。按 / 鍵鍵入（例：ㄚˉㄚˊㄚˇㄚˋㄚ˙ㄚ˪ㄚ˫ㄍ̇）
- 未來版本考慮加入「譯音符號（注音符號第二式）」支援

## 載入方法

### 下載
```bash
git clone https://github.com/dsh0416/rime-bopomofo-symbols.git
cd rime-bopomofo-symbols
ln -s ./bopomofo_symbols.* THE_DIRECTORY_OF_YOUR_RIME_LIBRARY
```

### 載入

- 修改 `default.custom.yaml`
- 將 `- schema: bopomofo_symbols` 加入 `schema_list`
- 重新 deploy

## 版本歷史

- 2018.10.4 首個版本
