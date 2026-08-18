# Mobile Developer Roadmap

> A complete roadmap from Junior to Staff Mobile Engineer (iOS / Android / Flutter)

## Roadmap Overview

```
                           ┌─────────────────────────────────────────────────────────────┐
                           │                    MOBILE DEVELOPER                          │
                           │                    Junior → Staff                            │
                           └─────────────────────────────────────────────────────────────┘
                                                    │
          ┌─────────────────────────────────────────┼─────────────────────────────────────────┐
          │                                         │                                         │
          ▼                                         ▼                                         ▼
   ┌──────────────┐                        ┌──────────────┐                        ┌──────────────┐
   │   INTERN /   │                        │    JUNIOR     │                        │    INTERN     │
   │  BEGINNER    │                        │   DEVELOPER   │                        │   (0-6 mo)    │
   └──────┬───────┘                        └──────┬───────┘                        └──────────────┘
          │                                         │
          ▼                                         ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              FOUNDATIONS (6-12 months)                                       │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Mobile UX  │  Git  │  HTTP/REST  │  JSON  │  Basic Algorithms  │  OOP                      │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              PLATFORM PATHS (12-24 months)                                   │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │                                                                                              │
   │    ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐                        │
   │    │      iOS        │    │    ANDROID      │    │     FLUTTER     │                        │
   │    │  ─────────────  │    │  ─────────────  │    │  ─────────────  │                        │
   │    │  • Swift        │    │  • Kotlin       │    │  • Dart         │                        │
   │    │  • SwiftUI      │    │  • Jetpack Comp │    │  • Widgets      │                        │
   │    │  • UIKit        │    │  • Material 3   │    │  • BLoC/Riverpod│                        │
   │    │  • Combine      │    │  • Coroutines   │    │  • Platform Ch. │                        │
   │    │  • Core Data    │    │  • Room DB      │    │  • Isolates     │                        │
   │    └─────────────────┘    └─────────────────┘    └─────────────────┘                        │
   │                                                                                              │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              CROSS-PLATFORM (18-24 months)                                   │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  React Native  │  Flutter  │  Shared Business Logic  │  Platform-Specific UI               │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              ADVANCED (24-36 months)                                         │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Architecture  │  Performance  │  Testing  │  CI/CD  │  Push Notifications  │  Offline      │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              SENIOR (3-5 years)                                              │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  App Architecture  │  Design Systems  │  Accessibility  │  Security  │  Analytics           │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
          │
          ▼
   ┌──────────────────────────────────────────────────────────────────────────────────────────────┐
   │                              STAFF+ (5+ years)                                               │
   ├──────────────────────────────────────────────────────────────────────────────────────────────┤
   │  Mobile Strategy  │  Platform Leadership  │  Innovation  │  SDK/Library  │  Mentoring       │
   └──────────────────────────────────────────────────────────────────────────────────────────────┘
```

---

## Stage 1: Foundations (0-12 months)

### Skills Checklist

- [ ] **Mobile UX Fundamentals**
  - [ ] Human Interface Guidelines (iOS)
  - [ ] Material Design (Android)
  - [ ] Responsive layouts
  - [ ] Touch interactions
  - [ ] Navigation patterns (tabs, drawer, stack)
  - [ ] Dark mode support

- [ ] **Programming Basics**
  - [ ] Object-oriented programming
  - [ ] Data structures (arrays, lists, maps)
  - [ ] Algorithms basics
  - [ ] Design patterns (MVC, MVVM)

- [ ] **Web Technologies**
  - [ ] HTTP/REST API concepts
  - [ ] JSON parsing
  - [ ] Authentication (JWT, OAuth)
  - [ ] WebSocket basics

- [ ] **Developer Tools**
  - [ ] Git version control
  - [ ] Package managers (CocoaPods, Gradle, pub)
  - [ ] IDE setup (Xcode, Android Studio, VS Code)
  - [ ] Debugging tools

### Learning Resources

| Resource | Type | Cost | Link |
|----------|------|------|------|
| Google UX Design Certificate | Course | Paid | https://www.coursera.org/professional-certificates/google-ux-design |
| Material Design Guidelines | Documentation | Free | https://m3.material.io |
| Apple Human Interface Guidelines | Documentation | Free | https://developer.apple.com/design/human-interface-guidelines |
| freeCodeCamp Mobile Dev | Course | Free | https://www.freecodecamp.org |

### Project Ideas

1. **Calculator App** - Basic UI, state management
2. **Weather App** - API integration, location services
3. **Todo List** - Local storage, CRUD operations
4. **News Reader** - List views, detail screens, API

---

## Stage 2: Platform-Specific Development (12-24 months)

### iOS Path (Swift)

- [ ] **Swift Language**
  - [ ] Optionals and error handling
  - [ ] Protocols and extensions
  - [ ] Generics
  - [ ] Structs vs classes
  - [ ] Closures and higher-order functions
  - [ ] Concurrency (async/await, actors)

- [ ] **SwiftUI**
  - [ ] Views and modifiers
  - [ ] State management (@State, @Binding, @ObservedObject)
  - [ ] Navigation (NavigationStack, NavigationSplitView)
  - [ ] Lists and lazy loading
  - [ ] Animations
  - [ ] Custom views and view builders

- [ ] **UIKit** (Still important)
  - [ ] View controllers lifecycle
  - [ ] Auto Layout
  - [ ] UITableView / UICollectionView
  - [ ] Storyboards vs programmatic UI

- [ ] **iOS Ecosystem**
  - [ ] Core Data / SwiftData
  - [ ] Combine framework
  - [ ] URLSession networking
  - [ ] Keychain services
  - [ ] Core Location
  - [ ] Push notifications (APNs)

### Android Path (Kotlin)

- [ ] **Kotlin Language**
  - [ ] Null safety
  - [ ] Extension functions
  - [ ] Coroutines and flows
  - [ ] Data classes
  - [ ] Sealed classes
  - [ ] Higher-order functions

- [ ] **Jetpack Compose**
  - [ ] Composable functions
  - [ ] State management (remember, State)
  - [ ] Navigation (Navigation Compose)
  - [ ] LazyColumn / LazyRow
  - [ ] Material 3 components
  - [ ] Theming and styling

- [ ] **Android Architecture**
  - [ ] ViewModel
  - [ ] LiveData / StateFlow
  - [ ] Room database
  - [ ] Retrofit (networking)
  - [ ] Hilt (dependency injection)
  - [ ] WorkManager (background tasks)

- [ ] **Android Ecosystem**
  - [ ] Android Jetpack libraries
  - [ ] Google Play Services
  - [ ] Firebase integration
  - [ ] Location services
  - [ ] Camera and media

### Flutter Path (Dart)

- [ ] **Dart Language**
  - [ ] Variables and types
  - [ ] Null safety
  - [ ] Async programming (Future, Stream)
  - [ ] Generics
  - [ ] Extension methods

- [ ] **Flutter Widgets**
  - [ ] StatelessWidget / StatefulWidget
  - [ ] Layout widgets (Row, Column, Stack)
  - [ ] List widgets (ListView, GridView)
  - [ ] Material / Cupertino widgets
  - [ ] Custom painters

- [ ] **State Management**
  - [ ] Provider
  - [ ] Riverpod
  - [ ] BLoC pattern
  - [ ] GetX (alternative)

- [ ] **Flutter Ecosystem**
  - [ ] HTTP / Dio (networking)
  - [ ] SharedPreferences / Hive (local storage)
  - [ ] Firebase integration
  - [ ] Platform channels
  - [ ] Packages (pub.dev)

### Learning Resources

| Resource | Type | Cost | Link |
|----------|------|------|------|
| Apple Developer Documentation | Docs | Free | https://developer.apple.com/documentation |
| Android Developer Docs | Docs | Free | https://developer.android.com |
| Flutter Documentation | Docs | Free | https://docs.flutter.dev |
| Hacking with Swift | Course | Free | https://www.hackingwithswift.com |
| Kotlin Koans | Interactive | Free | https://play.kotlinlang.org |
| Flutter Widget of the Week | Videos | Free | YouTube |

### Project Ideas

1. **Social Media App** - Feed, profiles, posts, likes
2. **E-commerce App** - Products, cart, checkout
3. **Fitness Tracker** - Charts, history, goals
4. **Recipe App** - Categories, search, bookmarks
5. **Chat App** - Real-time messaging, notifications

---

## Stage 3: Cross-Platform & Advanced (18-36 months)

### Skills Checklist

- [ ] **React Native**
  - [ ] Core components
  - [ ] Navigation (React Navigation)
  - [ ] State management (Redux Toolkit)
  - [ ] Native modules
  - [ ] Hermes engine
  - [ ] Expo framework

- [ ] **Architecture Patterns**
  - [ ] MVVM (Model-View-ViewModel)
  - [ ] Clean Architecture
  - [ ] BLoC pattern
  - [ ] Redux / MVI
  - [ ] Dependency injection
  - [ ] Repository pattern

- [ ] **Testing**
  - [ ] Unit testing (XCTest, JUnit, flutter_test)
  - [ ] Widget/UI testing
  - [ ] Integration testing
  - [ ] Snapshot testing
  - [ ] Mocking (Mockito, MockK)
  - [ ] Code coverage

- [ ] **Performance Optimization**
  - [ ] Memory management
  - [ ] Battery optimization
  - [ ] Network optimization
  - [ ] Image caching
  - [ ] App size reduction
  - [ ] Startup time optimization
  - [ ] Profiling tools

- [ ] **Offline Support**
  - [ ] Local databases (SQLite, Realm, Hive)
  - [ ] Sync strategies
  - [ ] Offline-first architecture
  - [ ] Cache invalidation
  - [ ] Background sync

- [ ] **CI/CD**
  - [ ] Fastlane
  - [ ] GitHub Actions for mobile
  - [ ] Code signing
  - [ ] Automated testing
  - [ ] Beta distribution (TestFlight, Firebase App Distribution)

### Project Ideas

1. **Offline-First App** - Full functionality without internet
2. **Real-time Collaboration** - WebSocket, optimistic updates
3. **Complex Animation App** - Custom transitions, gestures
4. **Multi-platform App** - Shared logic, platform-specific UI

---

## Stage 4: Senior Mobile Engineer (3-5 years)

### Skills Checklist

- [ ] **App Architecture**
  - [ ] Modular architecture
  - [ ] Micro-apps / feature modules
  - [ ] Shared libraries
  - [ ] Design system implementation
  - [ ] Navigation architecture

- [ ] **Security**
  - [ ] Secure storage (Keychain, EncryptedSharedPreferences)
  - [ ] Certificate pinning
  - [ ] Code obfuscation
  - [ ] Jailbreak/root detection
  - [ ] OWASP Mobile Top 10
  - [ ] Biometric authentication

- [ ] **Analytics & Monitoring**
  - [ ] Crash reporting (Crashlytics, Sentry)
  - [ ] Analytics (Firebase, Mixpanel, Amplitude)
  - [ ] A/B testing
  - [ ] Feature flags
  - [ ] Performance monitoring
  - [ ] User behavior tracking

- [ ] **Accessibility**
  - [ ] Screen reader support
  - [ ] Dynamic type / font scaling
  - [ ] Color contrast
  - [ ] Touch target sizes
  - [ ] WCAG mobile guidelines

- [ ] **App Store Optimization**
  - [ ] ASO (App Store Optimization)
  - [ ] Store listing optimization
  - [ ] Review management
  - [ ] Release management
  - [ ] Phased rollouts

- [ ] **Leadership**
  - [ ] Code review proven patterns
  - [ ] Technical documentation
  - [ ] Mentoring
  - [ ] Cross-team collaboration

### Project Ideas

1. **Design System Library** - Shared component library
2. **Accessibility Toolkit** - A11y testing and utilities
3. **Analytics Platform** - Custom event tracking

---

## Stage 5: Staff+ Mobile Engineer (5+ years)

### Skills Checklist

- [ ] **Mobile Strategy**
  - [ ] Platform selection (native vs cross-platform)
  - [ ] Technology roadmap
  - [ ] Build vs buy decisions
  - [ ] Vendor evaluation
  - [ ] Mobile-first product thinking

- [ ] **Platform Leadership**
  - [ ] SDK development
  - [ ] Open source libraries
  - [ ] Developer experience (DX)
  - [ ] Internal tools and frameworks
  - [ ] Architecture review boards

- [ ] **Innovation**
  - [ ] AR/VR (ARKit, ARCore)
  - [ ] Machine learning on device (Core ML, ML Kit)
  - [ ] IoT integration
  - [ ] Wearable development
  - [ ] Emerging platforms

- [ ] **Organizational Impact**
  - [ ] Engineering culture
  - [ ] Hiring and interviewing
  - [ ] Conference speaking
  - [ ] Technical writing
  - [ ] Open source leadership

---

## Interview Preparation

### Common Interview Topics

1. **Language & Framework**
   - Swift/Kotlin advanced features
   - SwiftUI/Jetpack Compose internals
   - Memory management
   - Concurrency patterns

2. **Architecture & Design**
   - MVVM vs MVC vs Clean Architecture
   - Dependency injection
   - State management
   - Navigation patterns

3. **System Design**
   - Design a chat application
   - Design a social media feed
   - Design an offline-first app
   - Design a real-time collaboration tool

4. **Coding Challenges**
   - Implement pagination
   - Build a custom view/component
   - Create a caching layer
   - Design a state management solution

5. **Platform Knowledge**
   - iOS: App lifecycle, memory management, Core Data
   - Android: Activity lifecycle, ViewModel, Room
   - Flutter: Widget tree, rendering pipeline, isolates

### Salary Expectations (USD, Annual)

| Level | Years | US (Median) | US (Range) | Remote (US) |
|-------|-------|-------------|------------|-------------|
| Junior | 0-2 | $75,000 | $55K - $95K | $60K - $85K |
| Mid | 2-4 | $110,000 | $85K - $135K | $90K - $125K |
| Senior | 4-7 | $150,000 | $125K - $185K | $125K - $170K |
| Staff | 7-10 | $195,000 | $165K - $245K | $160K - $220K |
| Principal | 10+ | $245,000 | $205K - $320K | $195K - $275K |

*Note: iOS developers typically earn 5-10% more than Android developers in the US market.*

---

## 中文版本 - 移动开发路线图

### 概述

这是一份从移动开发初级工程师到高级技术专家的完整成长路线图，涵盖 iOS、Android、Flutter 三大技术方向。

### 阶段一：基础入门（0-12个月）

**必学技能：**
- [ ] 移动端 UX 设计基础（Material Design、HIG）
- [ ] 编程基础（OOP、数据结构）
- [ ] HTTP/REST API 与 JSON
- [ ] Git 版本控制

**推荐学习资源：**
- Google UX 设计证书课程
- Material Design 官方文档
- Apple 人机界面指南

**练手项目：**
1. 计算器应用
2. 天气应用（API 调用）
3. 新闻阅读器

### 阶段二：平台专精（12-24个月）

**iOS 路线：**
- [ ] Swift 语言（可选值、协议、泛型、并发）
- [ ] SwiftUI（状态管理、导航、动画）
- [ ] UIKit（视图控制器、Auto Layout）
- [ ] Core Data / SwiftData
- [ ] Combine 框架

**Android 路线：**
- [ ] Kotlin 语言（空安全、协程、Flow）
- [ ] Jetpack Compose（组件、状态、Material 3）
- [ ] Android 架构（ViewModel、Room、Hilt）
- [ ] Firebase 集成

**Flutter 路线：**
- [ ] Dart 语言（空安全、异步编程）
- [ ] Flutter Widget 系统
- [ ] 状态管理（Riverpod、BLoC）
- [ ] 平台通道（Platform Channels）

**练手项目：**
1. 社交媒体应用
2. 电商平台应用
3. 健身追踪应用

### 阶段三：进阶技能（18-36个月）

- [ ] 跨平台开发（React Native / Flutter）
- [ ] 架构模式（MVVM、Clean Architecture）
- [ ] 测试（单元测试、UI 测试、集成测试）
- [ ] 性能优化（内存、电池、启动时间）
- [ ] 离线支持（本地数据库、同步策略）
- [ ] CI/CD（Fastlane、GitHub Actions）

### 阶段四：高级移动开发（3-5年）

- [ ] 模块化架构
- [ ] 安全（证书固定、代码混淆、OWASP Mobile Top 10）
- [ ] 分析与监控（Crashlytics、Firebase Analytics）
- [ ] 无障碍访问（屏幕阅读器、动态字体）
- [ ] 应用商店优化（ASO）

### 阶段五：技术专家（5年以上）

- [ ] 移动技术战略（原生 vs 跨平台选型）
- [ ] SDK/库开发
- [ ] 前沿技术（AR/VR、设备端 ML）
- [ ] 组织影响力

### 薪资参考（人民币/年）

| 级别 | 经验 | 一线城市 | 二线城市 | 远程 |
|------|------|----------|----------|------|
| 初级 | 0-2年 | 15-25万 | 10-18万 | 12-20万 |
| 中级 | 2-4年 | 25-40万 | 18-30万 | 20-35万 |
| 高级 | 4-7年 | 40-65万 | 30-50万 | 35-55万 |
| 资深 | 7-10年 | 65-100万 | 45-70万 | 50-80万 |
| 专家 | 10年+ | 100-150万 | 60-100万 | 70-120万 |

*注：iOS 开发在国内市场薪资普遍比 Android 高 5-10%。*

---

*Last updated: 2024*
*Contributions welcome! See [CONTRIBUTING.md](../CONTRIBUTING.md)*
