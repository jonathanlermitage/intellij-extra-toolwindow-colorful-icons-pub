# Extra ToolWindow Colorful Icons Change Log

## 2025.1.9 (2025/06/27)
* fix [#16](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/16): `SettingsServiceB is in unnamed module of loader com.intellij.ide.plugins.cl.PluginClassLoader` errors.
* add colors to the Android Profiler tool window icon.
* rework the Android Build Variants tool window icon (New UI).

## 2025.1.8 (2025/06/13)
* the minimal IDE version is now 2024.3 instead of 2023.3.1. This was needed to use newer JetBrains APIs and stay compatible with future IDEs (2025.2+).
* fix usage of some JetBrains deprecated APIs, improving the compatibility with future IDEs (2025.2+).
* [#13](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/13): rework and add colors to the Hierarchy tool window icon.
* [#13](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/13): add colors to the Open Project main menu icon (New UI).
* [#13](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/13): add colors to the JetClient tool window icons (New UI).
* [#13](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/13): add colors to the SonarQube tool window icons (New UI).
* [#13](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/13): add colors to the TeamCity tool window icons (New UI).
* [#13](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/13): add colors to the YouTrack tool window icons (New UI).
* [#13](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/13): add colors to the Search Everywhere main toolbar icon (New UI).
* [#13](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/13): add colors to the IDE Settings icons (New UI).
* [#13](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/13): add colors to the Code With Me main toolbar icon (New UI).
* [#14](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/14): add colors to the AI Assistant main toolbar icon (New UI).
* add colors to the Kubernetes tool window icon.
* add colors to the UI Theme Color Picker tool window icon (appeared with 2025.2 IDEs, internal mode).
* rework the Python Console tool window icon and add alternative icons.
* rework the Python Packages tool window icon and add alternative icons.
* optimize the plugin size on disk by reorganizing resource files.
* minor visual improvements in settings dialogs.

## 2025.1.7 (2025/05/06)
* fix for error `Class initialization must not depend on services. Consider using instance of the service on-demand instead`.
* various minor code reworks.

## 2025.1.6 (2025/04/14)
* implement [#12](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/12): add colors to some tool window icons in various plugins for Microsoft Azure.
* rework the Make tool window icon (New UI).
* improve support of third-party plugins.

## 2025.1.5 (2025/03/17)
* settings can now be loaded and saved by the **Backup and Sync** plugin.
* implement [#10](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/10): add colors to the GitHub Copilot tool window and status bar icons (welcome, Copilot, chat, connection status).
* rework the Notifications tool window icon. The purple icon turned orange when selected.
* add some alternative icons for the Notifications tool window icon.
* add an alternative icon for the Structure tool window icon (the new icon introduced by IntelliJ 2025.1).
* add colors to the Power Save Mode icons (status bar and inspection).
* add colors to the (Android Studio) Device Explorer, Device Manager, and App Quality Insights tool window icons.
* add colors to the (Android Studio, Gemini) AI Code Completion status icon.
* add colors to the JetBrains Junie tool window icon.
* important code rework: better support of icon override for the icons coming from third-party plugins.
* improve the Chinese localization.
* various code reworks.

## 2025.1.4 (2025/02/25)
* implement [#8](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/8): add colors to the Notifications tool window icon.
* implement [#9](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/9): add colors to the Coverage tool window icon.
* settings UI: add a search field to filter the icon table. This should help you find icons to (de)activate.
* improve the way IDE icons are replaced by custom icons, especially when using the New UI and deactivating the Compact Mode.
* improve the plugin's compatibility range. The minimal IDE version is now 2023.3.1 instead of 2024.1.

## 2025.1.3 (2025/01/27)
* update the plugin description to announce lifetime licenses.

## 2025.1.2 (2025/01/24)
* implement [#7](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/7): the freemium mode now allows selecting icons to enable and disable (still from the Classic UI icon theme).

## 2025.1.1 (2025/01/21)
* implement [#6](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/6): add colors to the `Show History` icon.
* add colors to the `Bazel` tool window icon.
* rework the `Add`, `Back`, `Bookmarks`, `Branch`, `Build`, `Close` (multiple icons), `Collapse`, `Collapse All`, `Changes` (VCS), `Commit`, `Database`, `Database Changes`, `Debug`, `Endpoints`, `Expand`, `Expand All`, `Fetch`, `Forward`, `Gradle`, `Learn` (Feature Trainer), `Maven`, `Merge`, `Profile`, `Redo`, `Remove`, `Run`, `Problems`, `Push`, `Reset`, `Rollback`, `Services`, `Show Diff`, `Spring`, `SQL Generator`, `Terminal`, `Undo`, `Update`, and `Writerside` tool window icons when using the New UI.
* add colors to the `Chevron Up` and the `Chevron Down` normal and large icons.
* some icons now have variants, similar to [alternative icons from Extra Icons](https://jonathanlermitage.github.io/ij-extra-tools-pack-docs/extra-icons-plugin-icons.html#alternative-icons).
* the New UI theme has been reworked, and a third theme "New UI Remix" has been added, which looks like the New UI theme with more visible lines.
* improve the Chinese localization.
* rework how the Chinese language is detected. This should avoid rare scenarios where the Chinese localization of the plugin was loaded on non-Chinese computers.
* [documentation](https://jonathanlermitage.github.io/ij-extra-tools-pack-docs/extra-tci.html).

## 2024.6.3 (2024/12/13)
* minor UI reworks in the settings panel.
* minor code reworks.

## 2024.6.2 (2024/11/19)
* hopefully fix `com.intellij.diagnostic.PluginException: Cannot init component state (...)` errors.
* fix a potential licensing issue introduced by the previous plugin version.

## 2024.6.1 (2024/11/16)
* rework the Hierarchy toolbar icon.
* rework the [Extra IDE Tweaks](https://plugins.jetbrains.com/plugin/23927-extra-ide-tweaks) Open Editors tool window icon.
* rework the Writable and the Read-Only tool window icons when using the New UI.
* add colors to the Persistence tool window icon.
* add colors to the Android Resources Manager tool window icon.
* add colors to the WriterSide Collapse All and Expand All icons in the WriterSide tool window. For now, this works with the New UI only. The Classic UI is affected by a bug (see [WRS-6459](https://youtrack.jetbrains.com/issue/WRS-6459)).
* implement [#4](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/4): add colors to the Tests tool window in Rider.
* fix support of the editor tab pinned icon. No longer overrides the WriterSide "Pin the Preview" icon.

## 2024.5.4 (2024/10/29)
* fix potential component ID collisions when installing this plugin alongside other obfuscated plugins.
* code rework: replace usage of obsolete JetBrains APIs, improving compatibility with future IDEs.

## 2024.5.3 (2024/10/21)
* remove the unused third-party library Apache Commons IO.

## 2024.5.2 (2024/09/23)
* fix usage of some JetBrains deprecated APIs, improving the compatibility with future IDEs (2024.3+).

## 2024.5.1 (2024/09/17)
* improve compatibility with future IDEs (2024.3+).
* add colors to the AI Assistant status icon (status: disabled).
* add colors to the Grazie Pro status icon (status: local processing).
* rework AI Assistant and Grazie Pro tool window icons color. AI Assistant is green when enabled. Grazie Pro is green when using local processing and blue when connected to the cloud. Both are red when disabled or unavailable.

## 2024.4.1 (2024/08/20)
* add colors to the Writerside icons.
* rework the [PsiViewer](https://plugins.jetbrains.com/plugin/227-psiviewer) icon.

## 2024.3.1 (2024/07/29)
* [request #1](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/1): add colors to the NuGet icon.
* fix [#3](https://github.com/jonathanlermitage/intellij-extra-toolwindow-colorful-icons-pub/issues/3): the Project icon should be yellow, even when inactive (new UI, dark theme).

## 2024.2.1 (2024/07/21)
* add colors to the Server icon.

## 2024.1.1 (2024/07/08)
* Extra ToolWindow Colorful Icons is now a freemium plugin.  
  Please look at the plugin description for details.

## 1.37.1 (2024/07/03)
* display a notification about the upcoming freemium plan.  
  Starting with the plugin version 2024.1.1, and after more than 3 years of development, Extra ToolWindow Colorful Icons becomes a freemium plugin.  
  **Icons coming from the [original ToolWindow Colorful Icons plugin](https://plugins.jetbrains.com/plugin/10863-toolwindow-colorful-icons) stay free, plus a subset of additional icons I added over time.
  All the other icons will require a paid license**.
* optimize all SVG icons.

## 1.37.0 (2024/07/01)
* add colors and rework the Grazie Pro status icons (status: connected to the cloud, error).
* add colors to the AI Assistant status icon (status: enabled).
* rework the AI Assistant dark tool window icon.

## 1.36.0 (2024/06/14)
* add colors and rework the AGP Assistant tool window icon (Android Studio).
* integrate the new IDE [Exception Analyzer](https://plugins.jetbrains.com/docs/marketplace/exception-analyzer.html). This is an easy way to report plugin exceptions from IntelliJ Platform-based products to plugin developers right on JetBrains Marketplace, instead of opening an issue on the plugin's GitHub repository.

## 1.35.0 (2024/04/12)
* fix usage of a JetBrains deprecated API.

## 1.34.0 (2024/03/29)
* add colors to [Extra IDE Tweaks](https://plugins.jetbrains.com/plugin/23927-extra-ide-tweaks) Open Editors tool window icon.

## 1.33.0 (2024/02/17)
* add colors to toolbar's specific Collapse and Expand icons in new UI.

## 1.32.0 (2024/02/10)
* rework some new UI icons (thicker lines, to make them more visible when coloured, in normal and compact modes): Refresh, Rollback Commit, Bookmarks, Services.
* restore the new UI Collapse, Collapse All, Expand and Expand All icons (I was still using the old icons even with the new UI), and add colors to them.
* add colors to Back icon in new UI.
* add colors to Forward icon in new UI.
* add colors to Diff icon in new UI.
* add colors to Pull icon in new UI.
* add colors to Push icon in new UI.
* add colors to Undo icon in new UI.
* add colors to Redo icon in new UI.

## 1.31.1 (2024/01/23)
* minor code rework.

## 1.31.0 (2024/01/09)
* add colors to [Key Promoter X](https://plugins.jetbrains.com/plugin/9792-key-promoter-x) icon.
* add colors to [Developer Tools](https://plugins.jetbrains.com/plugin/21904-developer-tools) icon and make it a bit more visible (bigger).
* rework [PlantUML integration](https://plugins.jetbrains.com/plugin/7017-plantuml-integration) icon's colors and convert it from PNG to SVG.

## 1.30.0 (2024/01/02)
* rework and add colors to more Android Studio (and Android plugin) tool window icons.
* add colors to GraphQL icon.
* add colors to Logcat icon.

## 1.29.0 (2023/12/06)
* add colors to JPA Buddy tool window icons (back-ported from [Extra Icons plugin theme](https://plugins.jetbrains.com/plugin/11058-extra-icons)).
* optimize SVG icons size with SVGO 3.0.5.

## 1.28.0 (2023/11/28)
* add colors to AI Assistant tool window icon (back-ported from [Extra Icons plugin theme](https://plugins.jetbrains.com/plugin/11058-extra-icons)).
* help needed: don't hesitate to submit ideas of custom icons for JPA Buddy *dog* icons (JPA Explorer and JPA Designer tool windows) ;-)

## 1.27.1 (2023/11/21)
* fix missing Grunt icon in light theme.
* optimize SVG icons size with SVGO 3.0.4.

## 1.27.0 (2023/09/03)
* add an option to prefer Old UI or New UI icon variants.
* add colors to Swap Panels icon.
* add new UI variants for Bookmarks, Commit, Refresh, Rollback and Services icons. **Future updates will add variants for more icons** (contributions would be highly appreciated).
* internal: code cleanup, remove compatibility code for unsupported old IDEs.
* **new UI support: [up-voting this issue](https://youtrack.jetbrains.com/issue/IDEA-321006/cant-override-IDE-SVG-icons-using-IconPathPatcher-in-newUI) would help**. Thanks!

## 1.26.0 (2023/06/03)
* fix support for Pinned Tab icon in recent IDEs.
* rework colouring of Bookmarks and Pin icons.
* **new UI support: [up-voting this issue](https://youtrack.jetbrains.com/issue/IDEA-321006/cant-override-IDE-SVG-icons-using-IconPathPatcher-in-newUI) would help**. Thanks!

## 1.25.0 (2023/05/10)
* add colors to Hierarchy icon.
* nota: plugin doesn't work well with the new UI. I am aware of that, and I am investigating this issue. **Any help would be highly appreciated**.
* nota: a future plugin update will offer icons dedicated to the new UI. In other words, there will be an option to display old or new UI icons, both colorful.

## 1.24.0 (2022/12/03)
* add colors to File Transfer icons.
* add colors to Endpoints Action icon.
* add colors to Spring Boot Endpoint icon.
* add colors to Endpoints icon.
* add colors to Download icon.
* add colors to Upload icon.

## 1.23.0 (2022/07/23)
* add colors to Branch Node icon.
* found a way to continue to support IDEs based on IJ 2020 and 2021. IDE build number is detected at runtime and code is adapted when needed.

## 1.22.0 (2022/07/09)
* fix compatibility with IDEs based on IJ 2020 and 2021 (like Android Studio).
* this build is compatible with IDE `>=2020.1` and `<2022.2`.

## 1.21.0 (2022/06/25)
* prevent a crash with the new IntelliJ UI (currently in preview) for IntelliJ 2022.2+ EAP (222.2889.14+).
* rework Dependencies icons.
* rework Gradle icons.

## 1.20.0 (2022/05/29)
* add colors to Delete icon.
* add colors to GC icon (notably used by the Kubernetes plugin to delete components).
* add colors to multiple Pin (pinned tab, etc.) icons.
* config panel GUI: add a description for some icons.

## 1.19.0 (2022/05/14)
* add colors to CherryPick icon.

## 1.18.0 (2022/03/06)
* improve support of various "close" icons.

## 1.17.0 (2022/02/23)
* remove the unwanted customization of the "close on hover" button of the IDE window.

## 1.16.0 (2022/02/20)
* add colors to Add to dictionary icon.
* add colors to Close icons.
* add colors to Scroll Up and Scroll Down icons.
* add colors to Toggle Soft Wrap icon.

## 1.15.0 (2021/12/27)
* rework the Collapse All icon.
* add colors to Feature Trainer icon.
* add colors to Remote Host icon.
* add colors to Cloud Config (connected) icon.
* add colors to Add to List icon.

## 1.14.0 (2021/12/04)
* add colors to CodeWithMe Access Off icon.
* add colors to Gradle icon.
* add colors to Kotlin icon.
* config panel: minor UI improvements.

## 1.13.0 (2021/11/26)
* add colors to Bookmarks icon (2021.3+).

## 1.12.0 (2021/10/30)
* add colors to Back icon.
* add colors to Cut icon.
* add colors to Redo icon.
* add colors to Undo icon.

## 1.11.0 (2021/10/24)
* add colors to Collapse All icon.
* add colors to Expand All icon.
* add colors to Messages icon.
* add colors to Print icon.
* add colors to TODO icon.

## 1.10.0 (2021/10/17)
* add colors to Remove icon.

## 1.9.0 (2021/08/11)
* add a config panel to choose icons to apply. See `Settings` > `Appearance & Behavior` > `Extra ToolWindow Colorful Icons`.

## 1.8.0 (2021/08/07)
* fix Problems icon size.
* add colors to (Android) Emulator icon.
* add colors to (Android) Profiler icon.
* add colors to Read-Only icon.
* add colors to Read-Write icon.
* add colors to Lock icon.
* add colors to Add icon.
* add colors to Merge icon.
* rework and add colors to App Inspection and Inspection Results icons.

## 1.7.0 (2021/07/30)
* add colors to Dependencies icon.
* rework the Python Packages icon.

## 1.6.0 (2021/07/25)
* add colors to Services icon.
* rework the Feature Trainer light icon.

## 1.5.0 (2021/06/20)
* add colors to Reset and Rollback icons.

## 1.4.0 (2021/06/10)
* add colors to Reload All from Disk and Reload from Disk icons.
* revert Paste icon.

## 1.3.0 (2021/05/29)
* add colors for Make icon (tested with GoLand IDE).
* add colors for Ant, Paste, Save All and Show Context Actions icons. 

## 1.2.0 (2021/05/22)
* plugin can be loaded with no IDE restart.

## 1.1.0 (2021/04/22)
* terminal icon: bigger icon.
* branch (dark) icon: brighter color.
* problem icon: use a green color.
* add colors to Commit icon.
* add colors to Python Packages icon.

## 1.0.0 (2021/04/19)
* first release. Add colors or rework to Terminal, Pull Request, Gradle, Problems (when empty), Project, Branch icons. A future release will make this configurable.
