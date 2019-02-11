# AirbnbCodeFormattingSample
Airbnbのコードフォーマットを試したSample

### 注意！
本プロジェクトをBuildすると、`DVTTextIndentWidth`が`2`に変更されます。
設定を戻したいときは、以下のbashを読み込んでください。

```bash
defaults write com.apple.dt.Xcode DVTTextEditorTrimTrailingWhitespace -bool NO
defaults write com.apple.dt.Xcode DVTTextEditorTrimWhitespaceOnlyLines -bool NO
defaults delete com.apple.dt.Xcode DVTTextIndentTabWidth
defaults delete com.apple.dt.Xcode DVTTextIndentWidth
defaults delete com.apple.dt.Xcode DVTTextPageGuideLocation
```
