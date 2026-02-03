## 详细
- 开始着重打磨ui
- 开始优化引擎
- 移植跨平台compose


## 技术栈

*   **语言:** Kotlin
*   **UI 框架:** Jetpack Compose
*   **设计语言:** Material Design 3


## 构建与运行

### 环境要求

*   Android Studio (推荐最新稳定版)
*   Android SDK (API 36)
*   JDK 17

## 开发约定

*   **UI 开发:** 使用 Jetpack Compose 进行声明式 UI 开发。
*   **状态管理:** 利用 Compose 的 `State` 和 `ViewModel` (如果使用) 来管理 UI 状态。
*   **导航:** 使用 `androidx.navigation:navigation-compose` 进行单 Activity 多 Composable 的页面导航。
*   **主题:** 使用 Material Design 3 主题系统，并支持深色模式和多种主题颜色自定义。
*   **设置存储:** Android平台使用 `SharedPreferences` (通过 `SettingsRepository` 封装) 来持久化用户设置。