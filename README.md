# awesome-kotlin

A curated list of awesome Kotlin frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
	* [Awesome Lists and Collections](#awesome-lists-and-collections)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Linters and Formatters](#linters-and-formatters)
	* [Debugging and Profiling](#debugging-and-profiling)
	* [Editor and IDE Support](#editor-and-ide-support)
* Web
	* [Web Frameworks](#web-frameworks)
	* [HTTP and Networking Clients](#http-and-networking-clients)
* Data and Storage
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
* Machine Learning and AI
	* [LLM and Inference](#llm-and-inference)
* Networking and Distributed
	* [Networking](#networking)
* User Interface
	* [Mobile](#mobile)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Game Development](#game-development)
	* [Image and Video](#image-and-video)
* Security
	* [Cryptography](#cryptography)
	* [Security Tools](#security-tools)
	* [Reverse Engineering](#reverse-engineering)
* Concurrency and Performance
	* [Concurrency and Parallelism](#concurrency-and-parallelism)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Logging and Configuration](#logging-and-configuration)
	* [Files and Operating System](#files-and-operating-system)
	* [Automation and Scripting](#automation-and-scripting)
	* [General Purpose Libraries](#general-purpose-libraries)
* Systems and Hardware
	* [Operating Systems and Kernels](#operating-systems-and-kernels)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [skydoves/android-developer-roadmap](https://github.com/skydoves/android-developer-roadmap) - 🗺 The Android Developer Roadmap offers comprehensive learning paths to help you understand Android ecosystems.
* [ArisGuimera/Android-Expert](https://github.com/ArisGuimera/Android-Expert) - Aprende a PROGRAMAR aplicaciones ANDROID en KOTLIN sin conocimientos previos
* [bennyhuo/Kotlin-Tutorials](https://github.com/bennyhuo/Kotlin-Tutorials) - 仓库持续记录以 Kotlin 为基础的视频内容的制作过程 *(archived)*
* [SmartToolFactory/Jetpack-Compose-Tutorials](https://github.com/SmartToolFactory/Jetpack-Compose-Tutorials) - 🚀🧨📝 Series of Tutorials to learn about Jetpack Compose with subjects Material Widgets, Layout, SubcomposeLayout, custom layouts, State, custom rememberable, recomposition, LaunchedEffect, side-effects, Gesture, Animation, Navigation, Canvas, UIs like whatsapp and others.
* [antoniolg/Kotlin-for-Android-Developers](https://github.com/antoniolg/Kotlin-for-Android-Developers) - Companion App for the book
* [SusionSuc/AdvancedAndroid](https://github.com/SusionSuc/AdvancedAndroid) - Android 进阶
* [crazyqiang/AndroidStudy](https://github.com/crazyqiang/AndroidStudy) - 🔥 Android学习知识点总结 Jetpack、MVVM、MVI、Kotlin、ViewPager2、JUC多线程等，欢迎star！
* [hussien89aa/KotlinUdemy](https://github.com/hussien89aa/KotlinUdemy) - Learn how to make online games, and apps for Android O, like Pokémon , twitter,Tic Tac Toe, and notepad using Kotlin
* [SimonSchubert/LinuxCommandLibrary](https://github.com/SimonSchubert/LinuxCommandLibrary) - 2M+ app downloads, 500k+ monthly website visitors, Linux basics, tips and formatted man pages
* [google-developer-training/android-kotlin-fundamentals-apps](https://github.com/google-developer-training/android-kotlin-fundamentals-apps) - android-kotlin-fundamentals-apps *(archived)*
* [android/codelab-android-compose](https://github.com/android/codelab-android-compose)
* [heimashi/kotlin_tips](https://github.com/heimashi/kotlin_tips) - [DEPRECATED] 用Kotlin去提高生产力:汇总Kotlin相对于Java的优势，以及怎么用Kotlin去简洁、务实、高效、安全开发的Tips
* [compose-museum/jetpack-compose-book](https://github.com/compose-museum/jetpack-compose-book) - *(archived)*
* [google-developer-training/advanced-android-testing](https://github.com/google-developer-training/advanced-android-testing) - Android Testing Codelab *(archived)*

### Examples and Exercises

* [android/architecture-samples](https://github.com/android/architecture-samples) - A collection of samples to discuss and showcase different architectural tools and patterns for Android apps.
* [android/compose-samples](https://github.com/android/compose-samples) - Official Jetpack Compose samples.
* [android/nowinandroid](https://github.com/android/nowinandroid) - A fully functional Android app built entirely with Kotlin and Jetpack Compose
* [android/sunflower](https://github.com/android/sunflower) - A gardening app illustrating Android development best practices with migrating a View-based app to Jetpack Compose. *(archived)*
* [android/uamp](https://github.com/android/uamp) - A sample audio app for Android *(archived)*
* [firebase/quickstart-android](https://github.com/firebase/quickstart-android) - Firebase Quickstart Samples for Android
* [skydoves/Pokedex](https://github.com/skydoves/Pokedex) - 🗡️ Pokedex demonstrates modern Android development with Hilt, Material Motion, Coroutines, Flow, Jetpack (Room, ViewModel) based on MVVM architecture.
* [chrisbanes/cheesesquare](https://github.com/chrisbanes/cheesesquare) - Demos the new Android Design library.
* [Gurupreet/ComposeCookBook](https://github.com/Gurupreet/ComposeCookBook) - A Collection on all Jetpack compose UI elements, Layouts, Widgets and Demo screens to see it's potential
* [igorwojda/android-showcase](https://github.com/igorwojda/android-showcase) - 💎 Android application following best practices: Kotlin, Coroutines, JetPack, Clean Architecture, Feature Modules, Tests, MVVM, DI, Static Analysis...
* [dbacinski/Design-Patterns-In-Kotlin](https://github.com/dbacinski/Design-Patterns-In-Kotlin) - Design Patterns implemented in Kotlin
* [android/camera-samples](https://github.com/android/camera-samples) - Multiple samples showing the best practices in camera APIs on Android.
* [android/topeka](https://github.com/android/topeka) - A fun to play quiz that showcases material design on Android *(archived)*
* [android10/Android-CleanArchitecture-Kotlin](https://github.com/android10/Android-CleanArchitecture-Kotlin) - This is a movies sample app in Kotlin, which is part of a serie of blog posts I have written about architecting android application using different approaches.
* [android/user-interface-samples](https://github.com/android/user-interface-samples) - Multiple samples showing the best practices in the user interface on Android. *(archived)*
* [googlesamples/mlkit](https://github.com/googlesamples/mlkit) - A collection of sample apps to demonstrate how to use Google's ML Kit APIs on Android and iOS
* [skydoves/chatgpt-android](https://github.com/skydoves/chatgpt-android) - 📲 ChatGPT Android demonstrates a Chatbot application using OpenAI's chat API on Android with Stream Chat SDK for Compose.
* [git-xuhao/KotlinMvp](https://github.com/git-xuhao/KotlinMvp) - :fire: 基于Kotlin+MVP+Retrofit+RxJava+Glide 等架构实现短视频类小项目，简约风格及详细注释，欢迎 star or fork！
* [bufferapp/android-clean-architecture-boilerplate](https://github.com/bufferapp/android-clean-architecture-boilerplate) - An android boilerplate project using clean architecture *(archived)*
* [gradle/kotlin-dsl-samples](https://github.com/gradle/kotlin-dsl-samples) - *(archived)*
* [Foso/Jetpack-Compose-Playground](https://github.com/Foso/Jetpack-Compose-Playground) - Community-driven collection of Jetpack Compose example code and tutorials :rocket: https://foso.github.io/compose
* [vinaygaba/Learn-Jetpack-Compose-By-Example](https://github.com/vinaygaba/Learn-Jetpack-Compose-By-Example) - 🚀 This project contains various examples that show how you would do things the "Jetpack Compose" way
* [joreilly/PeopleInSpace](https://github.com/joreilly/PeopleInSpace) - Kotlin Multiplatform sample with SwiftUI, Jetpack Compose, Compose for Wear, Compose for Desktop, and Compose for Web clients along with Ktor backend.
* [running-libo/Tiktok](https://github.com/running-libo/Tiktok) - 高仿抖音APP
* [LukasLechnerDev/Kotlin-Coroutines-and-Flow-UseCases-on-Android](https://github.com/LukasLechnerDev/Kotlin-Coroutines-and-Flow-UseCases-on-Android) - 🎓 Learning Kotlin Coroutines and Flows for Android by example. 🚀 Sample implementations for real-world Android use cases. 🛠 Unit tests included!
* [android/location-samples](https://github.com/android/location-samples) - Multiple samples showing the best practices in location APIs on Android. *(archived)*
* [Kotlin/kotlin-koans](https://github.com/Kotlin/kotlin-koans) - Kotlin workshop *(archived)*
* [touchlab/KaMPKit](https://github.com/touchlab/KaMPKit) - KaMP Kit by Touchlab. A collection of code & tools designed to get your mobile team started quickly w/Kotlin Multiplatform
* [vmadalin/android-modular-architecture](https://github.com/vmadalin/android-modular-architecture) - 📚 Sample Android Components Architecture on a modular word focused on the scalability, testability and maintainability written in Kotlin, following best practices using Jetpack.
* [android/gradle-recipes](https://github.com/android/gradle-recipes) - Ready-to-use recipes for common build customizations that showcase the Android Gradle plugin's public APIs and DSL.
* [PatilShreyas/Foodium](https://github.com/PatilShreyas/Foodium) - 🍲Foodium is a sample food blog Android application 📱 built to demonstrate the use of Modern Android development tools - (Kotlin, Coroutines, Flow, Dagger 2/Hilt, Architecture Components, MVVM, Room, Retrofit, Moshi, Material Components).
* [Kotlin/kmp-production-sample](https://github.com/Kotlin/kmp-production-sample) - This is an open-source, mobile, cross-platform application built with Kotlin Multiplatform Mobile. It's a simple RSS reader, and you can download it from the App Store and Google Play. It's been designed to demonstrate how KMM can be used in real production projects.
* [guolindev/coolweatherjetpack](https://github.com/guolindev/coolweatherjetpack) - 酷欧天气的Jetpack版本实现，采用了MVVM架构。
* [mouredev/Weekly-Challenge-2022-Kotlin](https://github.com/mouredev/Weekly-Challenge-2022-Kotlin) - Ejercicios de código semanales en 2022 de la comunidad MoureDev para practicar lógica en cualquier lenguaje de programación.
* [VIPyinzhiwei/Eyepetizer](https://github.com/VIPyinzhiwei/Eyepetizer) - 🔥基于 Kotlin 语言仿写「开眼 Eyepetizer」的一个短视频 Android 客户端项目，采用 Android Jetpack 组件 + Kotlin 协程实现的 MVVM 架构。
* [android/androidify](https://github.com/android/androidify) - Sample app for Androidify
* [cortinico/kotlin-android-template](https://github.com/cortinico/kotlin-android-template) - Android + Kotlin + Github Actions + ktlint + Detekt + Gradle Kotlin DSL + buildSrc = ❤️
* [qingmei2/MVVM-Architecture](https://github.com/qingmei2/MVVM-Architecture) - The practice of MVVM + Jetpack architecture in Android.
* [darryrzhong/Android-Compose-MVVM-App](https://github.com/darryrzhong/Android-Compose-MVVM-App) - 基于 Jetpack Compose 的仿开眼短视频 Android 开源项目 -开眼短视频(OpenEyes)
* [antoniolg/Bandhook-Kotlin](https://github.com/antoniolg/Bandhook-Kotlin) - A showcase music app for Android entirely written using Kotlin language *(archived)*
* [iceCola7/WanAndroid](https://github.com/iceCola7/WanAndroid) - 🔥项目采用 Kotlin 语言，基于 MVP + RxJava + Retrofit + Glide + EventBus 等架构设计，努力打造一款优秀的 [玩Android] 客户端
* [PatilShreyas/NotyKT](https://github.com/PatilShreyas/NotyKT) - 📒 NotyKT is a complete 💎Kotlin-stack (Backend + Android) 📱 application built to demonstrate the use of Modern development tools with best practices implementation🦸.
* [ArisGuimera/SimpleAndroidMVVM](https://github.com/ArisGuimera/SimpleAndroidMVVM) - Proyecto de ejemplo con Clean Architecture, MVVM, Retrofit, Corrutinas, Dagger Hilt y mucho más acompañado de tutoriales por escritos y en vídeo.
* [android/platform-samples](https://github.com/android/platform-samples) - A collection of samples of different Android OS platform APIs.
* [zhujiang521/PlayAndroid](https://github.com/zhujiang521/PlayAndroid) - 🔥🔥🔥 Kotlin + MVVM + LCE版玩安卓，暗黑模式、横竖屏、无网、弱网、无数据、加载失败等等各种情况，协程、Room、Hilt、DataStore、LiveData、Retrofit、屏幕适配、本地缓存、多语言切换、多 lib，你想要的我都有！！！
* [getActivity/AndroidProject-Kotlin](https://github.com/getActivity/AndroidProject-Kotlin) - Android 技术中台 Kotlin 版本，但愿人长久，搬砖不再有
* [nikhilpanju/FabFilter](https://github.com/nikhilpanju/FabFilter) - Android app to showcase complex UI/Animations with and without MotionLayout
* [android/databinding-samples](https://github.com/android/databinding-samples) - *(archived)*
* [amitshekhariitbhu/ridesharing-uber-lyft-app](https://github.com/amitshekhariitbhu/ridesharing-uber-lyft-app) - Ride-Sharing Uber Lyft Android App - Learn to build a ride-sharing Android Taxi Clone App like Uber, Lyft - Open-Source Project
* [android/storage-samples](https://github.com/android/storage-samples) - Multiple samples showing the best practices in storage APIs on Android. *(archived)*
* [LRH1993/Eyepetizer-in-Kotlin](https://github.com/LRH1993/Eyepetizer-in-Kotlin) - 使用Kotlin撸一款Eyepetizer，学习Kotlin语言
* [TheAlgorithms/Kotlin](https://github.com/TheAlgorithms/Kotlin) - All Algorithms implemented in Kotlin
* [ktorio/ktor-samples](https://github.com/ktorio/ktor-samples) - Sample projects for Ktor
* [byoutline/kickmaterial](https://github.com/byoutline/kickmaterial) - Crowdfunding app concept for Android. Created to showcase new trends in Android development with strong focus on Material Design.
* [hi-dhl/PokemonGo](https://github.com/hi-dhl/PokemonGo) - 神奇宝贝 (PokemonGo) 基于 Jetpack + MVVM + Repository 设计模式 + Data Mapper + Kotlin Flow 的实战项目，如果这个仓库对你有帮助，请仓库右上角帮我 star 一下，非常感谢。
* [JetBrains/compose-multiplatform-ios-android-template](https://github.com/JetBrains/compose-multiplatform-ios-android-template) - Compose Multiplatform iOS+Android Application project template *(archived)*
* [CarGuo/GSYGithubAppKotlin](https://github.com/CarGuo/GSYGithubAppKotlin) - Kotlin Android 超完整的开源项目，功能丰富，适合学习和日常使用。GSYGithubApp 系列的优势：我们目前已经拥有 Flutter、Weex、ReactNative、Kotlin View、Kotlin Jetpack Compose ，Compose MultiPlatform，Harmony ArkUI 七个版本，功能齐全，项目框架内技术涉及面广，完成度高，持续维护，配套文章，适合全面学习，对比参考。
* [mrcsxsiq/Kotlin-Pokedex](https://github.com/mrcsxsiq/Kotlin-Pokedex) - :cyclone: A Pokedex app using ViewModel, ViewBinding, LiveData, Room and Navigation
* [githubwing/GankClient-Kotlin](https://github.com/githubwing/GankClient-Kotlin) - gank.io kotlin实现的干货集中营Android客户端 Kotlin Dagger Databinding Rxjava Retrofit Okhttp3
* [skydoves/DisneyMotions](https://github.com/skydoves/DisneyMotions) - 🦁 A Disney app using transformation motions based on MVVM (ViewModel, Coroutines, Flow, Room, Repository, Koin) architecture.
* [hi-dhl/AndroidX-Jetpack-Practice](https://github.com/hi-dhl/AndroidX-Jetpack-Practice) - 本仓库致力于建立最全、最新的的 AndroidX Jetpack 相关组件的实践项目 以及组件对应的分析文章（持续更新中）如果对你有帮助，请在右上角 star 一下，感谢
* [lulululbj/wanandroid](https://github.com/lulululbj/wanandroid) - Jetpack MVVM For Wanandroid 最佳实践 ！
* [miaowmiaow/fragmject](https://github.com/miaowmiaow/fragmject) - fragmject is a learning project prepared for Kotlin and Jetpack Compose. | fragmject 是一个为初学者准备的上手项目。 通过对 Kotlin 和 Compose 的系统运用，实现的一个功能完备符合主流市场标准 App。 fragmject 没有复杂的业务和多余的封装， 完全依照 Android Developer 官方的写法。 代码简单，内容全面，快速上手，对理解其他项目设计思想和封装技巧也很有帮助。
* [android/performance-samples](https://github.com/android/performance-samples) - Samples to show APIs and best practices in Performance on Android
* [android/wear-os-samples](https://github.com/android/wear-os-samples) - Multiple samples showing best practices in app and watch face development on Wear OS.
* [android/nav3-recipes](https://github.com/android/nav3-recipes) - Implement common use cases with Jetpack Navigation 3
* [GetStream/whatsApp-clone-compose](https://github.com/GetStream/whatsApp-clone-compose) - 📱 WhatsApp clone project demonstrates modern Android development built with Jetpack Compose and Stream Chat/Video SDK for Compose.
* [android/media-samples](https://github.com/android/media-samples) - Multiple samples showing the best practices in media APIs on Android (audio, video, etc.).
* [nickbutcher/AdaptiveIconPlayground](https://github.com/nickbutcher/AdaptiveIconPlayground) - An Android app for experimenting with Adaptive Icons.
* [android/kotlin-multiplatform-samples](https://github.com/android/kotlin-multiplatform-samples) - Samples showcasing the Kotlin Multiplatform Jetpack libraries
* [zskingking/Jetpack-Mvvm](https://github.com/zskingking/Jetpack-Mvvm) - 使用Jetpack全家桶+Kotlin实现的Android社区App加音乐播放器。不写晦涩难懂的代码，尽量标清每一行注释，严格遵守六大基本原则，大量运用设计模式，此项目可快速帮你入手Kotlin、Jetpack。如果觉得对你有帮助，右上角点个star，事先谢过🍉🍉🍉
* [bufferapp/clean-architecture-components-boilerplate](https://github.com/bufferapp/clean-architecture-components-boilerplate) - A fork of our clean architecture boilerplate, this time using the Android Architecture Components
* [android/tv-samples](https://github.com/android/tv-samples) - Multiple samples showing best practices in app development on Android TV.
* [skydoves/MarvelHeroes](https://github.com/skydoves/MarvelHeroes) - ❤️ A sample Marvel heroes application based on MVVM (ViewModel, Coroutines, Room, Repository, Koin) architecture.
* [suming77/SumTea_Android](https://github.com/suming77/SumTea_Android) - 基于组件化+模块化+Kotlin+协程+Flow+Retrofit+Jetpack+MVVM+短视频架构实现的WanAndroid客户端
* [SEAbdulbasit/MusicApp-KMP](https://github.com/SEAbdulbasit/MusicApp-KMP) - This is a music player app built using Compose Multiplatform UI and KMP that works on Android, iOS, Desktop, and Web platforms.
* [Kotlin/kotlin-fullstack-sample](https://github.com/Kotlin/kotlin-fullstack-sample) - Kotlin Full-stack Application Example *(archived)*
* [Kotlin/kmp-basic-sample](https://github.com/Kotlin/kmp-basic-sample) - Example of Kotlin multiplatform project
* [skydoves/pokedex-compose](https://github.com/skydoves/pokedex-compose) - 🗡️ Pokedex Compose demonstrates modern Android development with Jetpack Compose, Hilt, Coroutines, Flow, Jetpack (Room, ViewModel), and Material Design based on MVVM architecture.
* [google-developer-training/android-kotlin-fundamentals-starter-apps](https://github.com/google-developer-training/android-kotlin-fundamentals-starter-apps) - android-kotlin-fundamentals-starter-apps *(archived)*
* [mCyp/Hoo](https://github.com/mCyp/Hoo) - 🚀 Android Jetpack系列组件实战案例，配上专栏学习更轻松~
* [android/snippets](https://github.com/android/snippets) - Main repository for snippets surfaced on developer.android.com.
* [Kotlin-Android-Open-Source/MVI-Coroutines-Flow](https://github.com/Kotlin-Android-Open-Source/MVI-Coroutines-Flow) - Play MVI with Kotlin Coroutines Flow | MVI pattern on Android using Kotlin Coroutines Flow | Dagger Hilt DI | Koin DI | SharedFlow | StateFlow | Arrow.kt Android Sample
* [nanchen2251/AiYaGirl](https://github.com/nanchen2251/AiYaGirl) - :fire: 爱吖妹纸（含 Kotlin 分支版本）——Retrofit + RxJava + MVP 架构 APP 体验代码家的干货集中营 Gank.io，福利多多，不容错过
* [yechaoa/MaterialDesign](https://github.com/yechaoa/MaterialDesign) - Material Design Samples。ConstraintLayout、MaterialButton、ShapeableImageView、TabLayout、SearchView...
* [Spikeysanju/Expenso](https://github.com/Spikeysanju/Expenso) - 📊 A Minimal Expense Tracker App built to demonstrate the use of modern android architecture component with MVVM Architecture
* [amanjeetsingh150/kotlin-android-examples](https://github.com/amanjeetsingh150/kotlin-android-examples) - :muscle: [Examples] Isolated applications purely on Kotlin, for all android devs out there
* [joreilly/Confetti](https://github.com/joreilly/Confetti) - KMP/CMP GraphQL based conference project with Jetpack Compose Android, Compose for Wear, and Compose Multiplatform Desktop, Web and iOS clients along with GraphQL backend.
* [igorwojda/kotlin-coding-challenges](https://github.com/igorwojda/kotlin-coding-challenges) - 🧩 Kotlin coding puzzle and solutions
* [android/security-samples](https://github.com/android/security-samples) - Multiple samples showing the best practices in security APIs on Android.
* [emqx/MQTT-Client-Examples](https://github.com/emqx/MQTT-Client-Examples) - MQTT Client Examples
* [googlesamples/android-custom-lint-rules](https://github.com/googlesamples/android-custom-lint-rules) - This sample demonstrates how to create a custom lint checks and corresponding lint tests
* [aliyun/alicloud-android-demo](https://github.com/aliyun/alicloud-android-demo)

### Awesome Lists and Collections

* [Heapy/awesome-kotlin](https://github.com/Heapy/awesome-kotlin) - A curated list of awesome Kotlin related stuff Inspired by awesome-java.
* [androiddevnotes/awesome-android-kotlin-apps](https://github.com/androiddevnotes/awesome-android-kotlin-apps) - 👓 A curated list of awesome android kotlin apps by open-source contributors.
* [jetpack-compose/jetpack-compose-awesome](https://github.com/jetpack-compose/jetpack-compose-awesome) - 📝 A curated list of awesome Jetpack Compose libraries, projects, articles and resources
* [androiddevnotes/awesome-android-learning-resources](https://github.com/androiddevnotes/awesome-android-learning-resources) - 👓 A curated list of awesome android learning resources for android app developers.
* [androiddevnotes/awesome-jetpack-compose-android-apps](https://github.com/androiddevnotes/awesome-jetpack-compose-android-apps) - 👓 A curated list of awesome Jetpack Compose android apps by open-source contributors.
* [androiddevnotes/awesome-jetpack-compose-learning-resources](https://github.com/androiddevnotes/awesome-jetpack-compose-learning-resources) - 👓 A continuously updated list of learning Jetpack Compose for Android apps.
* [adisonhuang/awesome-kotlin-android](https://github.com/adisonhuang/awesome-kotlin-android) - 🔥📱收集利用 Kotlin 进行 Android 开发的开源库，扩展，工具，开源项目，资料等高质量资源

## Language and Tooling

### Compilers and Interpreters

* [JetBrains/kotlin](https://github.com/JetBrains/kotlin) - The Kotlin Programming Language.
* [JetBrains/kotlin-native](https://github.com/JetBrains/kotlin-native) - Kotlin/Native infrastructure *(archived)*
* [square/kotlinpoet](https://github.com/square/kotlinpoet) - A Kotlin API for generating .kt source files.
* [google/ksp](https://github.com/google/ksp) - Kotlin Symbol Processing API
* [square/anvil](https://github.com/square/anvil) - A Kotlin compiler plugin to make dependency injection with Dagger 2 easier.
* [touchlab/SKIE](https://github.com/touchlab/SKIE) - SKIE - Swift Kotlin Interface Enhancer

### Build Systems

* [Triple-T/gradle-play-publisher](https://github.com/Triple-T/gradle-play-publisher) - GPP is Android's unofficial release automation Gradle Plugin. It can do anything from building, uploading, and then promoting your App Bundle or APK to publishing app listings and other metadata.
* [GradleUp/shadow](https://github.com/GradleUp/shadow) - Gradle plugin for creating fat/uber JARs, transforming files, relocating packages, and optimizing with R8/ProGuard. The Gradle counterpart to Maven Shade Plugin.
* [Kotlin/dokka](https://github.com/Kotlin/dokka) - API documentation engine for Kotlin
* [autonomousapps/dependency-analysis-gradle-plugin](https://github.com/autonomousapps/dependency-analysis-gradle-plugin) - Gradle plugin for JVM projects written in Java, Kotlin, Groovy, or Scala; and Android projects written in Java or Kotlin. Provides advice for managing dependencies and other applied plugins
* [vanniktech/gradle-dependency-graph-generator-plugin](https://github.com/vanniktech/gradle-dependency-graph-generator-plugin) - Gradle plugin that generates dependency graphs from your project.
* [JetBrains/intellij-platform-gradle-plugin](https://github.com/JetBrains/intellij-platform-gradle-plugin) - Gradle plugin for building plugins for JetBrains IDEs
* [JetBrains/compose-hot-reload](https://github.com/JetBrains/compose-hot-reload) - Compose Hot Reload: Make changes to your UI code in a Compose Multiplatform application, and see the results in real time. No restarts required. Compose Hot Reload runs your application on the JetBrains Runtime and intelligently reloads your code whenever it is changed.
* [google/secrets-gradle-plugin](https://github.com/google/secrets-gradle-plugin) - A Gradle plugin for providing your secrets to your Android project.
* [mozilla/rust-android-gradle](https://github.com/mozilla/rust-android-gradle)
* [qq549631030/AndroidJunkCode](https://github.com/qq549631030/AndroidJunkCode) - Android马甲包生成垃圾代码插件
* [spotify/ruler](https://github.com/spotify/ruler) - Gradle plugin which helps you analyze the size of your Android apps.
* [yshrsmz/BuildKonfig](https://github.com/yshrsmz/BuildKonfig) - BuildConfig for Kotlin Multiplatform Project
* [owenlongbo/McImage](https://github.com/owenlongbo/McImage) - Android Gradle Plugin -- Auto Check big image and compress image in building.
* [Leifzhang/AndroidAutoTrack](https://github.com/Leifzhang/AndroidAutoTrack) - Android Asm 插桩 教学

### Linters and Formatters

* [alibaba/p3c](https://github.com/alibaba/p3c) - Alibaba Java Coding Guidelines pmd implements and IDE plugin
* [ktlint/ktlint](https://github.com/ktlint/ktlint) - An anti-bikeshedding Kotlin linter with built-in formatter
* [LemonAppDev/konsist](https://github.com/LemonAppDev/konsist) - Konsist is a powerful static code analyzer tailored for Kotlin, focused on ensuring codebase consistency and adherence to coding conventions.
* [JLLeitschuh/ktlint-gradle](https://github.com/JLLeitschuh/ktlint-gradle) - A ktlint gradle plugin
* [skydoves/compose-stability-analyzer](https://github.com/skydoves/compose-stability-analyzer) - 🦄 Real-time analysis of Jetpack Compose composable functions' stability directly within Android Studio and IntelliJ.
* [twitter/compose-rules](https://github.com/twitter/compose-rules) - Static checks to aid with a healthy adoption of Compose
* [Kotlin/ktfmt](https://github.com/Kotlin/ktfmt) - A program that reformats Kotlin source code to comply with the common community standard for Kotlin code conventions.

### Debugging and Profiling

* [square/leakcanary](https://github.com/square/leakcanary) - A memory leak detection library for Android.
* [ACRA/acra](https://github.com/ACRA/acra) - Application Crash Reports for Android
* [ChuckerTeam/chucker](https://github.com/ChuckerTeam/chucker) - 🔎 An HTTP inspector for Android & OkHTTP (like Charles but on device)
* [zhengcx/MethodTraceMan](https://github.com/zhengcx/MethodTraceMan) - 用于快速找到高耗时方法，定位解决Android App卡顿问题。通过gradle plugin+ASM实现可配置范围的方法插桩来统计所有方法的耗时，并提供友好的界面展示，支持耗时筛选、线程筛选、方法名筛选等。(A Tool for Discovering High Time-consuming Methods for Android App)
* [getsentry/sentry-java](https://github.com/getsentry/sentry-java) - A Sentry SDK for Java, Android and other JVM languages.
* [bugsnag/bugsnag-android](https://github.com/bugsnag/bugsnag-android) - BugSnag crash monitoring and reporting tool for Android apps
* [guardian/toolargetool](https://github.com/guardian/toolargetool) - A tool to help you debug TransactionTooLargeExceptions on Android 7+
* [SusionSuc/rabbit-client](https://github.com/SusionSuc/rabbit-client) - 🐰 a simple and easy to use android apm framework (tools)
* [theapache64/rebugger](https://github.com/theapache64/rebugger) - A simple Compose Multiplatform library designed to print the reason for recomposition in your console/Logcat window."

### Editor and IDE Support

* [YiiGuxing/TranslationPlugin](https://github.com/YiiGuxing/TranslationPlugin) - Translation plugin for IntelliJ-based IDEs/Android Studio.
* [JetBrains/ideavim](https://github.com/JetBrains/ideavim) - IdeaVim – A Vim engine for JetBrains IDEs
* [izhangzhihao/intellij-rainbow-brackets](https://github.com/izhangzhihao/intellij-rainbow-brackets) - 🌈Rainbow Brackets for IntelliJ based IDEs/Android Studio/HUAWEI DevEco Studio/Fleet
* [intellij-rust/intellij-rust](https://github.com/intellij-rust/intellij-rust) - Rust plugin for the IntelliJ Platform
* [JetBrains/intellij-platform-plugin-template](https://github.com/JetBrains/intellij-platform-plugin-template) - Template repository for creating plugins for IntelliJ Platform
* [Kotlin/kotlin-lsp](https://github.com/Kotlin/kotlin-lsp) - Kotlin Language Server and plugin for Visual Studio Code
* [wuseal/JsonToKotlinClass](https://github.com/wuseal/JsonToKotlinClass) - 🚀 Plugin for Android Studio And IntelliJ Idea to generate Kotlin data class code from JSON text ( Json to Kotlin )
* [pbreault/adb-idea](https://github.com/pbreault/adb-idea) - A plugin for Android Studio and Intellij IDEA that speeds up your day to day android development.
* [fwcd/kotlin-language-server](https://github.com/fwcd/kotlin-language-server) - Kotlin code completion, diagnostics and more for any editor/IDE using the Language Server Protocol
* [EmmyLua/IntelliJ-EmmyLua](https://github.com/EmmyLua/IntelliJ-EmmyLua) - Lua IDE/Debugger Plugin for IntelliJ IDEA
* [tuchg/ChinesePinyin-CodeCompletionHelper](https://github.com/tuchg/ChinesePinyin-CodeCompletionHelper) - 让你的 JetBrains 系 IDE ( IDEA ,PyCharm,PhpStorm,WebStorm,AndroidStudio,GoLand等 )支持中文标识符以拼音/五笔等输入方式完成代码补全，享受和英文环境一致的中文智能编码体验，为代码表达提供更多选择，一种值得考虑的折中解决方案📏 *(archived)*
* [minecraft-dev/MinecraftDev](https://github.com/minecraft-dev/MinecraftDev) - Plugin for IntelliJ IDEA that gives special support for Minecraft modding projects.
* [acejump/AceJump](https://github.com/acejump/AceJump) - 🅰️ single character search, select, and jump
* [JetBrains/idea-gitignore](https://github.com/JetBrains/idea-gitignore) - .ignore support plugin for IntelliJ IDEA
* [wuyr/GoogleLibraryVersionQuerier](https://github.com/wuyr/GoogleLibraryVersionQuerier) - 一款Android Studio插件，帮助你快速添加依赖库和查询历史版本
* [dinbtechit/vscode-theme](https://github.com/dinbtechit/vscode-theme) - VSCode theme for all Jetbrains IDEs
* [JetBrains/android](https://github.com/JetBrains/android) - Android Plugin for IntelliJ IDEA. This repository is a subset of git://git.jetbrains.org/idea/android.git cut according to GitHub file size limitations.
* [intellij-solidity/intellij-solidity](https://github.com/intellij-solidity/intellij-solidity) - Solidity plugin for IntelliJ
* [vektah/CodeGlance](https://github.com/vektah/CodeGlance) - Intelij IDEA plugin for displaying a code mini-map similar to the one found in Sublime

## Web

### Web Frameworks

* [ktorio/ktor](https://github.com/ktorio/ktor) - Framework for quickly creating connected applications in Kotlin with minimal effort
* [javalin/javalin](https://github.com/javalin/javalin) - A simple and modern Java and Kotlin web framework
* [http4k/http4k](https://github.com/http4k/http4k) - The Functional toolkit for Kotlin HTTP applications. http4k provides a simple and uniform way to serve, consume, and test HTTP services.
* [varabyte/kobweb](https://github.com/varabyte/kobweb) - A modern framework for full stack web apps in Kotlin, built upon Compose HTML
* [rjaros/kvision](https://github.com/rjaros/kvision) - Object oriented web framework for Kotlin/JS

### HTTP and Networking Clients

* [lysine-dev/okhttp](https://github.com/lysine-dev/okhttp) - A meticulous HTTP client for the JVM, Android, and GraalVM.
* [kittinunf/fuel](https://github.com/kittinunf/fuel) - The easiest HTTP networking library for Kotlin/Android
* [ssseasonnn/RxDownload](https://github.com/ssseasonnn/RxDownload) - A multi-threaded download tool written with RxJava and Kotlin
* [liujingxing/rxhttp](https://github.com/liujingxing/rxhttp) - 🔥🔥🔥 Based on OkHttp encapsulation, support Kotlin Coroutines、RxJava2、RxJava3; 30s to get started.
* [gotev/android-upload-service](https://github.com/gotev/android-upload-service) - Easily upload files (Multipart/Binary/FTP out of the box) in the background with progress notification. Support for persistent upload requests, customizations and custom plugins.
* [Foso/Ktorfit](https://github.com/Foso/Ktorfit) - HTTP client generator / KSP plugin for Kotlin Multiplatform (Android, iOS, Js, Jvm, Native, WasmJs)) using KSP and Ktor clients inspired by Retrofit https://foso.github.io/Ktorfit
* [liangjingkanji/Net](https://github.com/liangjingkanji/Net) - [永久维护] Android 基于协程/OkHttp网络请求工具
* [JakeWharton/retrofit2-kotlin-coroutines-adapter](https://github.com/JakeWharton/retrofit2-kotlin-coroutines-adapter) - A Retrofit 2 adapter for Kotlin coroutine's Deferred type. *(archived)*
* [tonyofrancis/Fetch](https://github.com/tonyofrancis/Fetch) - The best file downloader library for Android
* [skydoves/sandwich](https://github.com/skydoves/sandwich) - 🥪 Sandwich is an adaptable and lightweight sealed API library designed for handling API responses and exceptions in Kotlin for Retrofit, Ktor, and Kotlin Multiplatform.
* [kordlib/kord](https://github.com/kordlib/kord) - Idiomatic Kotlin Wrapper for The Discord API
* [theapache64/retrosheet](https://github.com/theapache64/retrosheet) - 📃 Turn Google Spreadsheet to JSON endpoint (without any login/auth). Supported Platforms: Android, iOS, JVM and JS. Thanks to Kotlin Multiplatform 🙏🏼

## Data and Storage

### Database Clients and ORMs

* [JetBrains/Exposed](https://github.com/JetBrains/Exposed) - Kotlin SQL Framework
* [sqldelight/sqldelight](https://github.com/sqldelight/sqldelight) - SQLDelight - Generates typesafe Kotlin APIs from SQL
* [agrosner/DBFlow](https://github.com/agrosner/DBFlow) - A blazing fast, powerful, and very simple ORM android database library that writes database code for you.
* [kotlin-orm/ktorm](https://github.com/kotlin-orm/ktorm) - A lightweight ORM framework for Kotlin with strong-typed SQL DSL and sequence APIs.
* [jasync-sql/jasync-sql](https://github.com/jasync-sql/jasync-sql) - Java & Kotlin Async DataBase Driver for MySQL and PostgreSQL written in Kotlin
* [realm/realm-kotlin](https://github.com/realm/realm-kotlin) - Kotlin Multiplatform and Android SDK for the Realm Mobile Database: Build Better Apps Faster.

### Serialization and Formats

* [square/moshi](https://github.com/square/moshi) - A modern JSON library for Kotlin and Java.
* [Kotlin/kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization) - Kotlin multiplatform / multi-format serialization
* [square/wire](https://github.com/square/wire) - gRPC and protocol buffers for Android, Kotlin, Swift and Java.
* [cbeust/klaxon](https://github.com/cbeust/klaxon) - A JSON parser for Kotlin
* [FasterXML/jackson-module-kotlin](https://github.com/FasterXML/jackson-module-kotlin) - Module that adds support for serialization/deserialization of Kotlin (http://kotlinlang.org) classes and data classes.
* [JakeWharton/retrofit2-kotlinx-serialization-converter](https://github.com/JakeWharton/retrofit2-kotlinx-serialization-converter) - A Retrofit 2 Converter.Factory for Kotlin serialization. *(archived)*

## Machine Learning and AI

### LLM and Inference

* [google-ai-edge/gallery](https://github.com/google-ai-edge/gallery) - A gallery that showcases on-device ML/GenAI use cases and allows people to try and use models locally.
* [AAswordman/Operit](https://github.com/AAswordman/Operit) - The most powerful AI agent and AI chat software on Android/Operit是一款Android上能力最为强大、发展最久的AI Agent
* [rikkahub/rikkahub](https://github.com/rikkahub/rikkahub) - RikkaHub is an Android APP that supports for multiple LLM providers.
* [JetBrains/koog](https://github.com/JetBrains/koog) - Koog is a JVM (Java and Kotlin) framework for building predictable, fault-tolerant and enterprise-ready AI agents across all platforms – from backend services to Android and iOS, JVM, and even in-browser environments. Koog is based on our AI products expertise and provides proven solutions for complex LLM and AI problems
* [phodal/auto-dev](https://github.com/phodal/auto-dev) - 🧙‍AutoDev: the Multi-Agent coding development platform built on Kotlin Multiplatform.
* [embabel/embabel-agent](https://github.com/embabel/embabel-agent) - Agent framework for the JVM. Pronounced Em-BAY-bel /ɛmˈbeɪbəl/
* [xororz/local-dream](https://github.com/xororz/local-dream) - Run Stable Diffusion on Android Devices with Snapdragon NPU acceleration. Also supports CPU/GPU inference.
* [ahmedeltaher/Android-MVVM-Architecture-Android-Voice-AI-SDK](https://github.com/ahmedeltaher/Android-MVVM-Architecture-Android-Voice-AI-SDK) - Voice AI SDK is a reusable Android library that gives any app a full voice-driven AI conversation pipeline in minutes. Voice Assistant + Android Voide AI + SDK + MVVM + Kotlin
* [Turbo1123/roubao](https://github.com/Turbo1123/roubao) - Android Automation Tool Based on Vision-Language Models
* [carlrobertoh/ProxyAI](https://github.com/carlrobertoh/ProxyAI) - The leading open-source AI copilot for JetBrains. Connect to any model in any environment, and customize your coding experience in any way you like.
* [aallam/openai-kotlin](https://github.com/aallam/openai-kotlin) - OpenAI API client for Kotlin with multiplatform and coroutines capabilities.
* [openai/openai-java](https://github.com/openai/openai-java) - The official Java library for the OpenAI API
* [modelcontextprotocol/kotlin-sdk](https://github.com/modelcontextprotocol/kotlin-sdk) - The official Kotlin SDK for Model Context Protocol servers and clients. Maintained in collaboration with JetBrains
* [ModalityDance/PalmClaw](https://github.com/ModalityDance/PalmClaw) - [EMNLP 2026 Demo] "PalmClaw: A Native On-Device Agent Framework for Mobile Phones"
* [agents-io/PokeClaw](https://github.com/agents-io/PokeClaw) - PokeClaw (PocketClaw) — first on-device AI that controls your Android phone. Gemma 4, no cloud, no API key. Poke is short for Pocket.
* [yashab-cyber/opendroid](https://github.com/yashab-cyber/opendroid) - Your Open Autonomous Android Agent — A production-ready, self-planning AI assistant powered by local/remote LLMs and accessibility-driven screen automation.

## Networking and Distributed

### Networking

* [2dust/v2rayNG](https://github.com/2dust/v2rayNG) - A V2Ray client for Android, support Xray core and v2fly core
* [bannedbook/fanqiang](https://github.com/bannedbook/fanqiang) - 翻墙-科学上网
* [shadowsocks/shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android) - A shadowsocks client for Android
* [MatsuriDayo/NekoBoxForAndroid](https://github.com/MatsuriDayo/NekoBoxForAndroid) - NekoBox for Android / sing-box / universal proxy toolchain for Android
* [romanvht/ByeByeDPI](https://github.com/romanvht/ByeByeDPI) - Приложение локально запускает ByeDPI и перенаправляет весь трафик через него
* [Mygod/VPNHotspot](https://github.com/Mygod/VPNHotspot) - Share your VPN connection over hotspot or repeater! (root required)
* [SagerNet/SagerNet](https://github.com/SagerNet/SagerNet) - The universal proxy toolchain for Android *(archived)*
* [dovecoteescapee/ByeDPIAndroid](https://github.com/dovecoteescapee/ByeDPIAndroid) - App to bypass censorship on Android
* [celzero/rethink-app](https://github.com/celzero/rethink-app) - DNS over HTTPS / DNS over Tor / DNSCrypt client, WireGuard proxifier, firewall, and connection tracker for Android.
* [ProtonVPN/android-app](https://github.com/ProtonVPN/android-app) - Official ProtonVPN Android app
* [guardianproject/orbot-android](https://github.com/guardianproject/orbot-android) - The Github home of Orbot: Tor on Android (Also available on gitlab!)
* [Tinder/Scarlet](https://github.com/Tinder/Scarlet) - A Retrofit inspired WebSocket client for Kotlin, Java, and Android
* [wgtunnel/android](https://github.com/wgtunnel/android) - An advanced, open-source client for WireGuard and AmneziaWG on Android.
* [jitsi/jitsi-videobridge](https://github.com/jitsi/jitsi-videobridge) - Jitsi Videobridge is a WebRTC compatible video router or SFU that lets build highly scalable video conferencing infrastructure (i.e., up to hundreds of conferences per server).
* [xuhaoyang/ClashForAndroid](https://github.com/xuhaoyang/ClashForAndroid) - A rule-based tunnel for Android.
* [tailscale/tailscale-android](https://github.com/tailscale/tailscale-android) - Tailscale Android Client
* [madeye/proxydroid](https://github.com/madeye/proxydroid) - Global Proxy for Android
* [MatsuriDayo/Matsuri](https://github.com/MatsuriDayo/Matsuri) - Matsuri (茉莉) / V2Ray / universal proxy toolchain for Android / Fork of SagerNet *(archived)*
* [HMBSbige/ShadowsocksR-Android](https://github.com/HMBSbige/ShadowsocksR-Android) - 【自用】咕咕咕 *(archived)*
* [MortezaBashsiz/CFScanner](https://github.com/MortezaBashsiz/CFScanner) - Cloudflare scanner
* [xchacha20-poly1305/husi](https://github.com/xchacha20-poly1305/husi) - Husi is a non-professional proxy-set-based multiplatform proxy tool set.
* [yamada95/kitsunebi-android](https://github.com/yamada95/kitsunebi-android) - A fully-featured V2Ray client for Android. *(archived)*
* [WireGuard/wireguard-android](https://github.com/WireGuard/wireguard-android) - Mirror only. Official repository is at https://git.zx2c4.com/wireguard-android
* [xtclovver/RKNHardering](https://github.com/xtclovver/RKNHardering) - Обнаружние VPN конфигураторов на пользовательских устройствах с дальнейшей целью защиты от обнаружения
* [SagerNet/sing-box-for-android](https://github.com/SagerNet/sing-box-for-android) - Android client for sing-box
* [WhiteDNS/WhiteDNS-Android](https://github.com/WhiteDNS/WhiteDNS-Android) - Source-available Android DNS tunneling client with VPN and proxy modes, backed by MasterDNS & StormDNS.
* [2dust/v2flyNG](https://github.com/2dust/v2flyNG) - A V2Ray client for Android, support v2fly core
* [JuulLabs/kable](https://github.com/JuulLabs/kable) - Kotlin Asynchronous Bluetooth Low-Energy
* [amurcanov/proxy-turn-vk-android](https://github.com/amurcanov/proxy-turn-vk-android) - WireGuard‑туннель через DTLS‑медиарелей ВК TURN‑серверов: трафик проходит от клиента к вашему личному VPS‑серверу через промежуточные медиарелей‑серверы ВК. *(archived)*

## User Interface

### Mobile

* [CymChad/BaseRecyclerViewAdapterHelper](https://github.com/CymChad/BaseRecyclerViewAdapterHelper) - BRVAH:Powerful and flexible RecyclerAdapter
* [afollestad/material-dialogs](https://github.com/afollestad/material-dialogs) - 😍 A beautiful, fluid, and extensible dialogs API for Kotlin & Android. *(archived)*
* [square/picasso](https://github.com/square/picasso) - A powerful image downloading and caching library for Android
* [google/flexbox-layout](https://github.com/google/flexbox-layout) - Flexbox for Android *(archived)*
* [facebook/fresco](https://github.com/facebook/fresco) - An Android library for managing images and the memory they use.
* [Kotlin/anko](https://github.com/Kotlin/anko) - Pleasant Android application development *(archived)*
* [coil-kt/coil](https://github.com/coil-kt/coil) - Image loading for Android and Compose Multiplatform.
* [mikepenz/MaterialDrawer](https://github.com/mikepenz/MaterialDrawer) - The flexible, easy to use, all in one drawer library for your Android project. Now brand new with material 2 design.
* [wasabeef/recyclerview-animators](https://github.com/wasabeef/recyclerview-animators) - An Android Animation library which easily add itemanimator to RecyclerView items.
* [AppIntro/AppIntro](https://github.com/AppIntro/AppIntro) - Make a cool intro for your Android app.
* [JakeWharton/RxBinding](https://github.com/JakeWharton/RxBinding) - RxJava binding APIs for Android's UI widgets. *(archived)*
* [uber/RIBs](https://github.com/uber/RIBs) - Uber's cross-platform mobile architecture framework - Android Repository
* [google/accompanist](https://github.com/google/accompanist) - A collection of extension libraries for Jetpack Compose
* [facebook/litho](https://github.com/facebook/litho) - A declarative framework for building efficient UIs on Android.
* [TheWidlarzGroup/react-native-video](https://github.com/TheWidlarzGroup/react-native-video) - A <Video /> component for react-native
* [facebook/facebook-android-sdk](https://github.com/facebook/facebook-android-sdk) - Used to integrate Android apps with Facebook Platform.
* [androidx/androidx](https://github.com/androidx/androidx) - Development environment for Android Jetpack extension libraries under the androidx namespace. Synchronized with Android Jetpack's primary development branch on AOSP.
* [airbnb/mavericks](https://github.com/airbnb/mavericks) - Mavericks: Android on Autopilot
* [drakeet/MultiType](https://github.com/drakeet/MultiType) - Flexible multiple types for Android RecyclerView.
* [kizitonwose/Calendar](https://github.com/kizitonwose/Calendar) - A highly customizable calendar view and compose library for Android and Kotlin Multiplatform.
* [Tapadoo/Alerter](https://github.com/Tapadoo/Alerter) - An Android Alerting Library
* [mikepenz/Android-Iconics](https://github.com/mikepenz/Android-Iconics) - Android-Iconics - Use any icon font, or vector (.svg) as drawable in your application.
* [diogobernardino/williamchart](https://github.com/diogobernardino/williamchart) - Android Library to rapidly develop attractive and insightful charts in android applications.
* [firebase/FirebaseUI-Android](https://github.com/firebase/FirebaseUI-Android) - Optimized UI components for Firebase
* [mikepenz/AboutLibraries](https://github.com/mikepenz/AboutLibraries) - AboutLibraries automatically collects all dependencies and licenses of any gradle project (Kotlin MultiPlatform), and provides easy to integrate UI components for Android and Compose Multiplatform environments
* [airbnb/DeepLinkDispatch](https://github.com/airbnb/DeepLinkDispatch) - A simple, annotation-based library for making deep link handling better on Android
* [ChadCSong/ShineButton](https://github.com/ChadCSong/ShineButton) - This is a UI lib for Android. Effects like shining.
* [skydoves/Balloon](https://github.com/skydoves/Balloon) - :balloon: Modernized and sophisticated tooltips, fully customizable with an arrow and animations for Compose and Kotlin Multiplatform.
* [sharish/ShimmerRecyclerView](https://github.com/sharish/ShimmerRecyclerView)
* [mikepenz/FastAdapter](https://github.com/mikepenz/FastAdapter) - The bullet proof, fast and easy to use adapter library, which minimizes developing time to a fraction...
* [Kyant0/AndroidLiquidGlass](https://github.com/Kyant0/AndroidLiquidGlass) - Compose Multiplatform Liquid Glass effect
* [Yalantis/Context-Menu.Android](https://github.com/Yalantis/Context-Menu.Android) - You can easily add awesome animated context menu to your app.
* [RedApparat/Fotoapparat](https://github.com/RedApparat/Fotoapparat) - Making Camera for Android more friendly. 📸
* [PierfrancescoSoffritti/android-youtube-player](https://github.com/PierfrancescoSoffritti/android-youtube-player) - YouTube Player library for Android and Chromecast, stable and customizable.
* [TakuSemba/Spotlight](https://github.com/TakuSemba/Spotlight) - Android Library that lights items for tutorials or walk-throughs etc...
* [guolindev/PermissionX](https://github.com/guolindev/PermissionX) - An open source Android library that makes handling runtime permissions extremely easy.
* [googlemaps/android-maps-utils](https://github.com/googlemaps/android-maps-utils) - Maps SDK for Android Utility Library
* [tommybuonomo/dotsindicator](https://github.com/tommybuonomo/dotsindicator) - Dots indicators for Android ViewPager and Compose
* [hegaojian/JetpackMvvm](https://github.com/hegaojian/JetpackMvvm) - :chicken::basketball:JetpackMvvm 是一个基于 Jetpack 架构组件构建的 Android MVVM 快速开发框架，旨在帮助开发者快速搭建高质量、可维护、可扩展的应用。
* [princekin-f/EasyFloat](https://github.com/princekin-f/EasyFloat) - 🔥 EasyFloat：浮窗从未如此简单（Android可拖拽悬浮窗口，支持页面过滤、自定义动画，可设置单页面浮窗、前台浮窗、全局浮窗，浮窗权限按需自动申请...）
* [Tencent-TDS/KuiklyUI](https://github.com/Tencent-TDS/KuiklyUI) - A Kotlin Multiplatform UI framework from Tencent TDS — high-performance, one codebase for six platforms, with dynamic delivery.
* [DanielMartinus/Konfetti](https://github.com/DanielMartinus/Konfetti) - Celebrate more with this lightweight confetti particle system 🎊
* [raamcosta/compose-destinations](https://github.com/raamcosta/compose-destinations) - Annotation processing library for type-safe Jetpack Compose navigation with no boilerplate.
* [jenly1314/ZXingLite](https://github.com/jenly1314/ZXingLite) - 🔥 ZXing的精简极速版，优化扫码和生成二维码/条形码，内置闪光灯等功能。扫描风格支持：微信的线条样式，支付宝的网格样式。几句代码轻松拥有扫码功能 ，ZXingLite让集成扫码更简单。
* [patrykandpatrick/vico](https://github.com/patrykandpatrick/vico) - A powerful and extensible chart library for Compose Multiplatform.
* [adrielcafe/voyager](https://github.com/adrielcafe/voyager) - 🛸 A pragmatic navigation library for Compose Multiplatform
* [rnmapbox/maps](https://github.com/rnmapbox/maps) - A Mapbox react native module for creating custom maps
* [arkivanov/Decompose](https://github.com/arkivanov/Decompose) - Kotlin Multiplatform lifecycle-aware business logic components (aka BLoCs) with routing (navigation) and pluggable UI (Jetpack Compose, SwiftUI, JS React, etc.)
* [liangjingkanji/BRV](https://github.com/liangjingkanji/BRV) - [永久维护] Android 快速构建 RecyclerView, 比 BRVAH 更简单强大
* [MikeOrtiz/TouchImageView](https://github.com/MikeOrtiz/TouchImageView) - Adds touch functionality to Android ImageView.
* [zcweng/SwitchButton](https://github.com/zcweng/SwitchButton) - SwitchButton.An beautiful+lightweight+custom-style-easy switch widget for Android,minSdkVersion >= 11
* [DroidNinja/Android-FilePicker](https://github.com/DroidNinja/Android-FilePicker) - Photopicker and document picker for android
* [divkit/divkit](https://github.com/divkit/divkit) - DivKit is an open source Server-Driven UI (SDUI) framework. SDUI is a an emerging technique that leverage the server to build the user interfaces of their mobile app
* [nisrulz/sensey](https://github.com/nisrulz/sensey) - :zap: [Android Library] Play with sensor events & detect gestures in a breeze.
* [devaige/WheelPicker](https://github.com/devaige/WheelPicker) - Simple and fantastic wheel view in realistic effect for android.
* [worker8/TourGuide](https://github.com/worker8/TourGuide) - TourGuide is an Android library that aims to provide an easy way to add pointers with animations over a desired Android View
* [akexorcist/round-corner-progress-bar](https://github.com/akexorcist/round-corner-progress-bar) - [Android] Round Corner Progress Bar Library for Android
* [skydoves/landscapist](https://github.com/skydoves/landscapist) - 🌻 A pluggable, lightweight, highly optimized Jetpack Compose and Kotlin Multiplatform image loading library that fetches and displays network images.
* [terrakok/Cicerone](https://github.com/terrakok/Cicerone) - 🚦 Cicerone is a lightweight library that makes the navigation in an Android app easy.
* [ToxicBakery/ViewPagerTransforms](https://github.com/ToxicBakery/ViewPagerTransforms) - Library containing common animations needed for transforming ViewPager scrolling for Android v13+.
* [chrisbanes/haze](https://github.com/chrisbanes/haze) - Background blurring for Compose Multiplatform / Jetpack Compose
* [TakuSemba/MultiSnapRecyclerView](https://github.com/TakuSemba/MultiSnapRecyclerView) - Android library for multiple snapping of RecyclerView
* [azhon/AppUpdate](https://github.com/azhon/AppUpdate) - Android App update library. Android版本更新库，简单、轻量、可随意定制
* [skydoves/TransformationLayout](https://github.com/skydoves/TransformationLayout) - 🌠 Transform between two Views, Activities, and Fragments, or a View to a Fragment with container transform animations for Android.
* [panpf/sketch](https://github.com/panpf/sketch) - Image loading library designed for Compose Multiplatform and Android View. Supports loading Image, GIF, SVG, Video thumbnails from the network, local, resources, and photo albums.
* [tarek360/RichPath](https://github.com/tarek360/RichPath) - 💪 Rich Android Path. 🤡 Draw as you want. 🎉 Animate much as you can. *(archived)*
* [airbnb/Showkase](https://github.com/airbnb/Showkase) - 🔦 Showkase is an annotation-processor based Android library that helps you organize, discover, search and visualize Jetpack Compose UI elements
* [zagum/Android-SwitchIcon](https://github.com/zagum/Android-SwitchIcon) - Google launcher-style implementation of switch (enable/disable) icon
* [iielse/imageviewer](https://github.com/iielse/imageviewer) - A simple and customizable Android full-screen image viewer 一个简单且可自定义的Android全屏图像浏览器
* [TheFinestArtist/FinestWebView-Android](https://github.com/TheFinestArtist/FinestWebView-Android) - Beautiful and customizable Android Activity that shows web pages within an app.
* [margelo/react-native-blurhash](https://github.com/margelo/react-native-blurhash) - 🖼️ A library to show colorful blurry placeholders while your content loads.
* [lapism/search](https://github.com/lapism/search) - Material You Search component for Android, SearchView *(archived)*
* [JakeWharton/kotterknife](https://github.com/JakeWharton/kotterknife) - View "injection" library for Android. *(archived)*
* [garretyoder/Colorful](https://github.com/garretyoder/Colorful) - Android runtime theme library *(archived)*
* [saket/cascade](https://github.com/saket/cascade) - Nested popup menus with smooth height animations for Android
* [TonicArtos/SuperSLiM](https://github.com/TonicArtos/SuperSLiM) - A layout manager for the RecyclerView with interchangeable linear, grid, and staggered displays of views, all with configurable section headers including the sticky variety as specified in the material design docs.
* [ibrahimsn98/SmoothBottomBar](https://github.com/ibrahimsn98/SmoothBottomBar) - A lightweight Android material bottom navigation bar library
* [dev-labs-bg/transitioner](https://github.com/dev-labs-bg/transitioner) - A library for dynamic view-to-view transitions
* [stfalcon-studio/StfalconImageViewer](https://github.com/stfalcon-studio/StfalconImageViewer) - A simple and customizable Android full-screen image viewer with shared image transition support, "pinch to zoom" and "swipe to dismiss" gestures
* [cashapp/redwood](https://github.com/cashapp/redwood) - Multiplatform reactive UI for Android, iOS, and web using Kotlin and Jetpack Compose
* [faruktoptas/FancyShowCaseView](https://github.com/faruktoptas/FancyShowCaseView) - An easy-to-use customisable show case view with circular reveal animation.
* [mozilla-mobile/android-components](https://github.com/mozilla-mobile/android-components) - ⚠️ This project moved to a new repository. It is now developed and maintained at: https://github.com/mozilla-mobile/firefox-android *(archived)*
* [afollestad/drag-select-recyclerview](https://github.com/afollestad/drag-select-recyclerview) - 👇 Easy Google Photos style multi-selection for RecyclerViews, powered by Kotlin and AndroidX. *(archived)*
* [afollestad/aesthetic](https://github.com/afollestad/aesthetic) - [DEPRECATED] *(archived)*
* [saket/InboxRecyclerView](https://github.com/saket/InboxRecyclerView) - Build expandable descendant navigation, inspired by Google Inbox
* [leandroBorgesFerreira/LoadingButtonAndroid](https://github.com/leandroBorgesFerreira/LoadingButtonAndroid) - A button to substitute the ProgressDialog
* [lopspower/CircularImageView](https://github.com/lopspower/CircularImageView) - Create circular ImageView in Android in the simplest way possible
* [airbnb/paris](https://github.com/airbnb/paris) - Define and apply styles to Android views programmatically
* [MohamedRejeb/compose-rich-editor](https://github.com/MohamedRejeb/compose-rich-editor) - A Rich text editor library for both Jetpack Compose and Compose Multiplatform, fully customizable, supports HTML and Markdown.
* [slackhq/circuit](https://github.com/slackhq/circuit) - ⚡️ A Compose-driven architecture for Kotlin and Android applications.
* [czy1121/update](https://github.com/czy1121/update) - 清晰灵活简单易用的应用更新库
* [lopspower/CircularProgressBar](https://github.com/lopspower/CircularProgressBar) - Create circular ProgressBar in Android ⭕
* [jkwiecien/EasyImage](https://github.com/jkwiecien/EasyImage) - Library for picking pictures from gallery or camera
* [angcyo/DslTabLayout](https://github.com/angcyo/DslTabLayout) - :hearts: Android界最万能的TabLayout(不仅仅是TabLayout), 支持任意类型的item, 支持Drawable类型的指示器,智能开启滚动,支持横竖向布局等
* [yshrsmz/KeyboardVisibilityEvent](https://github.com/yshrsmz/KeyboardVisibilityEvent) - Android Library to handle software keyboard visibility change event.
* [aritraroy/Flashbar](https://github.com/aritraroy/Flashbar) - ⚡️A highly customizable, powerful and easy-to-use alerting library for Android.
* [yannecer/NCalendar](https://github.com/yannecer/NCalendar) - 一款安卓日历，仿miui，钉钉，华为的日历，万年历、365、周日历，月日历，月视图、周视图滑动切换，农历，节气，Andriod Calendar , MIUI Calendar,小米日历
* [rosenpin/fading-text-view](https://github.com/rosenpin/fading-text-view) - A TextView that changes its content automatically every few seconds
* [MohamedRejeb/Calf](https://github.com/MohamedRejeb/Calf) - Calf is a library that allows you to easily create adaptive UIs and access platform specific APIs with Compose Multiplatform (Adaptive UI, File Picker, WebView, Permissions...).
* [idisfkj/android-startup](https://github.com/idisfkj/android-startup) - 🔥The Android Startup library provides a straightforward, performant way to initialize components at the application startup. Both library developers and app developers can use Android Startup to streamline startup sequences and explicitly set the order of initialization.
* [GetStream/stream-chat-android](https://github.com/GetStream/stream-chat-android) - :speech_balloon: Android Chat SDK ➜ Stream Chat API. UI component libraries for chat apps. Kotlin & Jetpack Compose messaging SDK for Android chat
* [Yalantis/SearchFilter](https://github.com/Yalantis/SearchFilter) - Implementing Search Filter Animation in Kotlin for Quora Meets LinkedIn, Our App Design Concept
* [alexzhirkevich/compose-cupertino](https://github.com/alexzhirkevich/compose-cupertino) - Compose Multiplatform UI components for iOS (Cupertino Widgets)
* [gyf-dev/Cactus](https://github.com/gyf-dev/Cactus) - Android Keep Alive(安卓保活)，Cactus 集成双进程前台服务，JobScheduler，onePix(一像素)，WorkManager，无声音乐
* [vanniktech/Emoji](https://github.com/vanniktech/Emoji) - A library to add Emoji support to your Android / iOS / JVM Application
* [wching/Android-Indefinite-Pager-Indicator](https://github.com/wching/Android-Indefinite-Pager-Indicator) - A lightweight, plug-and-play indefinite pager indicator for RecyclerViews & ViewPagers.
* [Dhaval2404/ImagePicker](https://github.com/Dhaval2404/ImagePicker) - 📸Image Picker for Android, Pick an image from Gallery or Capture a new image with Camera
* [klinker24/Android-TextView-LinkBuilder](https://github.com/klinker24/Android-TextView-LinkBuilder) - Insanely easy way to define clickable links within a TextView.
* [Zackratos/UltimateBarX](https://github.com/Zackratos/UltimateBarX) - Make Android transparent statusbar and navigationbar easy.
* [skydoves/AndroidVeil](https://github.com/skydoves/AndroidVeil) - :performing_arts: An easy and flexible way to implement loading skeletons and shimmering effects on layouts for Android.
* [saket/telephoto](https://github.com/saket/telephoto) - Building blocks for designing media experiences in Compose UI
* [sephiroth74/android-target-tooltip](https://github.com/sephiroth74/android-target-tooltip) - Create Toast like tooltips, but targets can be specified, plus custom properties and features
* [stripe/stripe-android](https://github.com/stripe/stripe-android) - Stripe Android SDK
* [Spikeysanju/MotionToast](https://github.com/Spikeysanju/MotionToast) - 🌈 A Beautiful Motion Toast Library for Kotlin Android
* [cashapp/contour](https://github.com/cashapp/contour) - Layouts with lambdas 😎 *(archived)*
* [CanHub/Android-Image-Cropper](https://github.com/CanHub/Android-Image-Cropper) - Image Cropping Library for Android, optimised for Camera / Gallery.
* [Petterpx/FloatingX](https://github.com/Petterpx/FloatingX) - Android上强大的悬浮窗组件，支持 系统浮窗(需要权限)、应用内浮窗(无权限)、局部悬浮(View)，支持边缘吸附、回弹、自定义动画、位置保存、窗口化及分屏后位置修复等。Android without permission suspension window(App), support global(View), local suspension, support edge adsorption, rebound, custom animation, position saving, windowing and split-screen position repair.
* [ncapdevi/FragNav](https://github.com/ncapdevi/FragNav) - An Android library for managing multiple stacks of fragments
* [Droppers/AnimatedBottomBar](https://github.com/Droppers/AnimatedBottomBar) - A customizable and easy to use BottomBar navigation view with sleek animations, with support for ViewPager, ViewPager2, NavController, and badges.
* [Yalantis/JellyToolbar](https://github.com/Yalantis/JellyToolbar)
* [facebook/TextLayoutBuilder](https://github.com/facebook/TextLayoutBuilder) - An Android library that allows you to build text layouts more easily.
* [androidbroadcast/ViewBindingPropertyDelegate](https://github.com/androidbroadcast/ViewBindingPropertyDelegate) - Make work with Android View Binding simpler
* [sephiroth74/Material-BottomNavigation](https://github.com/sephiroth74/Material-BottomNavigation) - Bottom Navigation widget component inspired by the Google Material Design Guidelines at https://www.google.com/design/spec/components/bottom-navigation.html
* [jaredrummler/Cyanea](https://github.com/jaredrummler/Cyanea) - A theme engine for Android *(archived)*
* [oneHamidreza/MeowBottomNavigation](https://github.com/oneHamidreza/MeowBottomNavigation) - Android Meow Bottm Navigation
* [Ramotion/fluid-slider-android](https://github.com/Ramotion/fluid-slider-android) - :octocat:💧 A slider widget with a popup bubble displaying the precise value selected. Android library made by @Ramotion
* [igalata/Bubble-Picker](https://github.com/igalata/Bubble-Picker) - An easy-to-use animation which can be used for content picking for Android *(archived)*
* [Yalantis/Multi-Selection](https://github.com/Yalantis/Multi-Selection) - Multiselection Solution for Android in Kotlin
* [loopeer/shadow](https://github.com/loopeer/shadow) - Deprecated because of the performance not fine. Android custom shadow view, can replace your CardView
* [anastr/SpeedView](https://github.com/anastr/SpeedView) - Dynamic Speedometer and Gauge for Android. amazing, powerful, and multi shape :zap:
* [icerockdev/moko-resources](https://github.com/icerockdev/moko-resources) - Resources access for mobile (android & ios) Kotlin Multiplatform development
* [Calvin-LL/Reorderable](https://github.com/Calvin-LL/Reorderable) - Reorder items in Lists and Grids in Jetpack Compose and Compose Multiplatform with drag and drop.
* [orbit-mvi/orbit-mvi](https://github.com/orbit-mvi/orbit-mvi) - A simple MVI framework for Kotlin Multiplatform and Android
* [bitvale/Switcher](https://github.com/bitvale/Switcher) - Android implementation of switch animation from Oleg Frolov
* [robertlevonyan/material-chip-view](https://github.com/robertlevonyan/material-chip-view) - Material Chip view. Can be used as tags for categories, contacts or creating text clouds *(archived)*
* [HuolalaTech/hll-wp-therouter-android](https://github.com/HuolalaTech/hll-wp-therouter-android) - A framework for assisting in the renovation of Android componentization(帮助 App 进行组件化改造的动态路由框架)
* [Quyunshuo/AndroidBaseFrameMVVM](https://github.com/Quyunshuo/AndroidBaseFrameMVVM) - 基于 Jetpack + Kotlin 的 Android 组件化 MVVM 框架
* [googlemaps/android-maps-compose](https://github.com/googlemaps/android-maps-compose) - Jetpack Compose composables for the Maps SDK for Android
* [splitwise/TokenAutoComplete](https://github.com/splitwise/TokenAutoComplete) - Gmail style MultiAutoCompleteTextView for Android
* [badoo/MVICore](https://github.com/badoo/MVICore) - MVI framework with events, time-travel, and more
* [hi-manshu/charty](https://github.com/hi-manshu/charty) - Weave data into enchanting Jetpack Compose graphs—no potions required! 📜🔮
* [skydoves/Cloudy](https://github.com/skydoves/Cloudy) - ☁️ Kotlin Multiplatform blur and liquid glass effect library for Compose, with GPU-accelerated rendering and CPU fallback for older devices.
* [compose-miuix-ui/miuix](https://github.com/compose-miuix-ui/miuix) - A UI library for Compose Multiplatform
* [skydoves/PowerSpinner](https://github.com/skydoves/PowerSpinner) - 🌀 A lightweight dropdown popup spinner, fully customizable with an arrow and animations for Android.
* [bumble-tech/appyx](https://github.com/bumble-tech/appyx) - Model-driven navigation + UI components with gesture control for Compose Multiplatform
* [iammert/ReadableBottomBar](https://github.com/iammert/ReadableBottomBar) - Yet another material bottom bar library for Android
* [loper7/DateTimePicker](https://github.com/loper7/DateTimePicker) - ⭐🎉一个高颜值日期时间选择器；极简API，内置弹窗，支持农历日期显示，适配深色模式，可动态配置样式及主题，选择器支持完全自定义UI。
* [react-native-menu/menu](https://github.com/react-native-menu/menu) - UIMenu Component for React Native
* [composablehorizons/compose-unstyled](https://github.com/composablehorizons/compose-unstyled) - A renderless component library for Compose Multiplatform that handles accessibility, state, and UX logic without enforcing any visual styling.
* [PatilShreyas/Capturable](https://github.com/PatilShreyas/Capturable) - 🚀Jetpack Compose utility library for capturing Composable content and transforming it into Bitmap Image🖼️
* [cortinico/slidetoact](https://github.com/cortinico/slidetoact) - A simple 'Slide to Unlock' Material widget for Android, written in Kotlin 📱🎨🦄
* [iammert/MultiSearchView](https://github.com/iammert/MultiSearchView) - Yet another built-in animated search view for Android.
* [RedMadRobot/input-mask-android](https://github.com/RedMadRobot/input-mask-android) - User input masking library repo.
* [Kennyc1012/MultiStateView](https://github.com/Kennyc1012/MultiStateView) - Android View that displays different content based on its state
* [mobile-dev-inc/dadb](https://github.com/mobile-dev-inc/dadb) - A Kotlin/Java library to connect directly to an Android device without an adb binary or an ADB server
* [react-native-text-input-mask/react-native-text-input-mask](https://github.com/react-native-text-input-mask/react-native-text-input-mask) - Text input mask for React Native, Android and iOS *(archived)*
* [skydoves/Orbital](https://github.com/skydoves/Orbital) - 🪐 Jetpack Compose Multiplatform library that allows you to implement dynamic transition animations such as shared element transitions.
* [afreakyelf/Pdf-Viewer](https://github.com/afreakyelf/Pdf-Viewer) - A Lightweight PDF Viewer Android library which only occupies around 80kb while most of the Pdf viewer occupies up to 16MB space.
* [ImangazalievM/CircleMenu](https://github.com/ImangazalievM/CircleMenu) - CircleMenu is a simple, elegant menu with a circular layout.
* [qingmei2/RxImagePicker](https://github.com/qingmei2/RxImagePicker) - :rocket:RxJava2 and RxJava3 external support. Android flexible picture selector, provides the support for theme of Zhihu and WeChat (灵活的Android图片选择器，提供了知乎和微信主题的支持）.
* [easyandroidgroup/EasyAndroid](https://github.com/easyandroidgroup/EasyAndroid) - 一系列简单、轻量、方便的Android开发工具集合(持续更新中),包括Android动态权限、SharedPreferences、反射、日志、Toast、Bundle、MVP、线程池、Html、图文混排、蒙层引导、拍照、图库选择等
* [JetradarMobile/android-snowfall](https://github.com/JetradarMobile/android-snowfall) - Fully customizable implementation of "Snowfall View" on Android.
* [felipecsl/GifImageView](https://github.com/felipecsl/GifImageView) - Android ImageView that handles animated GIF images
* [javiersantos/MaterialStyledDialogs](https://github.com/javiersantos/MaterialStyledDialogs) - A library that shows a beautiful and customizable Material-based dialog with header. API 14+ required.
* [duanhong169/DrawableToolbox](https://github.com/duanhong169/DrawableToolbox) - 🛠️ The missing drawable toolbox for Android. Create drawables programmatically and get rid of the boring and always repeated drawable.xml files.
* [esafirm/android-image-picker](https://github.com/esafirm/android-image-picker) - Image Picker for Android 🤖 *(archived)*
* [zhongjhATC/AlbumCameraRecorder](https://github.com/zhongjhATC/AlbumCameraRecorder) - 🔥一个高效的多媒体支持操作库，可多方面的简单配置操作相册、拍照、录制、录音等功能。也支持配套使用的展示图片、视频、音频的九宫格功能。 （An efficient multimedia support operation library, can be a variety of simple configuration operation album, photo, recording, recording and other functions.Also support supporting the use of the display of pictures, video, audio of the nine grid function.）
* [AAChartModel/AAChartCore-Kotlin](https://github.com/AAChartModel/AAChartCore-Kotlin) - 📈📊⛰⛰⛰An elegant modern declarative data visualization chart framework for Android . Extremely powerful, supports line, spline, area, areaspline, column, bar, pie, scatter, angular gauges, arearange, areasplinerange, columnrange, bubble, box plot, error bars, funnel, waterfall and polar chart types.极其精美而又强大的 Android 数据可视化图表框架,支持柱状图、条形图、折线图、曲线图、折线填充图、曲线填充图、气泡图、扇形图、环形图、散点图、雷达图、混合图等各种类型的多达几十种的信息图图表,完全满足工作所需.
* [chrisbanes/insetter](https://github.com/chrisbanes/insetter) - Insetter is a library to help apps handle WindowInsets more easily *(archived)*
* [teprinciple/UpdateAppUtils](https://github.com/teprinciple/UpdateAppUtils) - 一行代码快速实现app版本更新
* [skydoves/FlexibleBottomSheet](https://github.com/skydoves/FlexibleBottomSheet) - 🐬 Advanced Compose Multiplatform bottom sheet for segmented sizing, non-modal type, and allows interaction behind the bottom sheet similar to Google Maps.
* [square/workflow-kotlin](https://github.com/square/workflow-kotlin) - A Swift and Kotlin library for making composable state machines, and UIs driven by those state machines.
* [natario1/ZoomLayout](https://github.com/natario1/ZoomLayout) - 2D zoom and pan behavior for View hierarchies, images, video streams, and much more, written in Kotlin for Android.
* [icerockdev/moko-mvvm](https://github.com/icerockdev/moko-mvvm) - Model-View-ViewModel architecture components for mobile (android & ios) Kotlin Multiplatform development
* [valentinilk/compose-shimmer](https://github.com/valentinilk/compose-shimmer) - A simple shimmer library for Jetpack Compose.
* [rosuH/AndroidFilePicker](https://github.com/rosuH/AndroidFilePicker) - FilePicker is a small and fast file selector library that is constantly evolving with the goal of rapid integration, high customization, and configurability~
* [Rogero0o/CatLoadingView](https://github.com/Rogero0o/CatLoadingView) - Android CatLoadingView
* [alexjlockwood/kyrie](https://github.com/alexjlockwood/kyrie) - 🍀 Animated Vector Drawables on steroids 🍀 *(archived)*
* [Mauker1/MaterialSearchView](https://github.com/Mauker1/MaterialSearchView) - Android Search View based on Material design guidelines.
* [oss-bandb/GraphView](https://github.com/oss-bandb/GraphView) - Android GraphView is used to display data in graph structures.
* [Pangu-Immortal/KeepAlivePerfect](https://github.com/Pangu-Immortal/KeepAlivePerfect) - 💰Android终极保活：Android4.1 到 Android16.0 完美的保活方案
* [aclassen/ComposeReorderable](https://github.com/aclassen/ComposeReorderable) - Enables reordering by drag and drop in Jetpack Compose (Desktop) LazyList & LazyGrid.
* [arkivanov/MVIKotlin](https://github.com/arkivanov/MVIKotlin) - Extendable MVI framework for Kotlin Multiplatform with powerful debugging tools (logging and time travel)
* [CRED-CLUB/synth-android](https://github.com/CRED-CLUB/synth-android) - Synth is CRED's inbuilt library for using Neumorphic components in your app.
* [fornewid/neumorphism](https://github.com/fornewid/neumorphism) - Try to Neumorphism in Android (Just experimental!! 🧪)
* [tommybuonomo/morph-bottom-navigation](https://github.com/tommybuonomo/morph-bottom-navigation) - This library represents a Bottom Navigation with an awesome morph effect on top of the selected item
* [KevinnZou/compose-webview-multiplatform](https://github.com/KevinnZou/compose-webview-multiplatform) - WebView for JetBrains Compose Multiplatform

### Applications and End User Tools

* [gedoor/legado](https://github.com/gedoor/legado) - Legado 3.0 Book Reader with powerful controls & full functions❤️阅读3.0, 阅读是一款可以自定义来源阅读网络内容的工具，为广大网络文学爱好者提供一种方便、快捷舒适的试读体验。
* [gkd-kit/gkd](https://github.com/gkd-kit/gkd) - 基于无障碍，高级选择器，订阅规则的自定义屏幕点击安卓应用 | An Android APP with custom screen tapping based on Accessibility, Advanced Selectors, and Subscription Rules
* [RikkaApps/Shizuku](https://github.com/RikkaApps/Shizuku) - Using system APIs directly with adb/root privileges from normal apps through a Java process started with app_process.
* [librepods-org/librepods](https://github.com/librepods-org/librepods) - AirPods liberated from Apple's ecosystem.
* [ReVanced/revanced-manager](https://github.com/ReVanced/revanced-manager) - 💊 Application to use ReVanced on Android
* [signalapp/Signal-Android](https://github.com/signalapp/Signal-Android) - A private messenger for Android.
* [JunkFood02/Seal](https://github.com/JunkFood02/Seal) - 🦭 Video/Audio Downloader for Android, based on yt-dlp
* [pppscn/SmsForwarder](https://github.com/pppscn/SmsForwarder) - 短信转发器——监控Android手机短信、来电、APP通知，并根据指定规则转发到其他手机：钉钉群自定义机器人、钉钉企业内机器人、企业微信群机器人、飞书机器人、企业微信应用消息、邮箱、bark、webhook、Telegram机器人、Server酱、PushPlus、手机短信等。包括主动控制服务端与客户端，让你轻松远程发短信、查短信、查通话、查话簿、查电量等。（V3.0 新增）PS.这个APK主要是学习与自用，如有BUG请提ISSUE，同时欢迎大家提PR指正
* [mihonapp/mihon](https://github.com/mihonapp/mihon) - Free and open source manga reader for Android
* [google/iosched](https://github.com/google/iosched) - The Google I/O Android App *(archived)*
* [open-ani/animeko](https://github.com/open-ani/animeko) - 集找番、追番、看番的一站式弹幕追番平台，云收藏同步 (Bangumi)，离线缓存，BitTorrent，弹幕云过滤。100% Kotlin/Compose Multiplatform
* [komi-store/komi-store](https://github.com/komi-store/komi-store) - 🩵 A free, open-source app store for developers' releases on GitHub, Codeberg & Forgejo — browse, discover, and install apps with one click. Formerly GitHub Store.
* [amir1376/ab-download-manager](https://github.com/amir1376/ab-download-manager) - A Download Manager that speeds up your downloads
* [nickbutcher/plaid](https://github.com/nickbutcher/plaid) - An Android app which provides design news & inspiration as well as being an example of implementing material design.
* [T8RIN/ImageToolbox](https://github.com/T8RIN/ImageToolbox) - 🖼️ Image Toolbox is a powerful app for advanced image manipulation. It offers dozens of features, from basic tools like crop and draw to filters, OCR, and a wide range of image processing options
* [thunderbird/thunderbird-android](https://github.com/thunderbird/thunderbird-android) - Thunderbird for Android – Open Source Email App for Android (fka K-9 Mail)
* [MetrolistGroup/Metrolist](https://github.com/MetrolistGroup/Metrolist) - YouTube Music client for Android
* [libre-tube/LibreTube](https://github.com/libre-tube/LibreTube) - An alternative frontend for YouTube, for Android.
* [ankidroid/Anki-Android](https://github.com/ankidroid/Anki-Android) - AnkiDroid: Anki flashcards on Android. Your secret trick to achieve superhuman information retention.
* [yujincheng08/BiliRoaming](https://github.com/yujincheng08/BiliRoaming) - 哔哩漫游，解除B站客户端番剧区域限制的Xposed模块，并且提供其他小功能。An Xposed module that unblocks bangumi area limit of BILIBILI with miscellaneous features. *(archived)*
* [breezy-weather/breezy-weather](https://github.com/breezy-weather/breezy-weather) - A feature-rich weather app with good visualizations and more than 50 sources.
* [maxrave-dev/SimpMusic](https://github.com/maxrave-dev/SimpMusic) - A cross-platform music app using YouTube Music for backend
* [Shabinder/SpotiFlyer](https://github.com/Shabinder/SpotiFlyer) - Kotlin Multiplatform Music Downloader, Supports Spotify / Gaana / Youtube Music / Jio Saavn / SoundCloud.
* [recloudstream/cloudstream](https://github.com/recloudstream/cloudstream) - Android app for streaming and downloading media.
* [iSoron/uhabits](https://github.com/iSoron/uhabits) - Loop Habit Tracker, a mobile app for creating and maintaining long-term positive habits
* [deniscerri/ytdlnis](https://github.com/deniscerri/ytdlnis) - Full-featured audio/video downloader for Android using yt-dlp
* [vfsfitvnm/ViMusic](https://github.com/vfsfitvnm/ViMusic) - An Android application for streaming music from YouTube Music *(archived)*
* [zhanghai/MaterialFiles](https://github.com/zhanghai/MaterialFiles) - Material Design file manager for Android
* [Ackites/Nrfr](https://github.com/Ackites/Nrfr) - 🌍 免 Root 的 SIM 卡国家码修改工具 | 解决国际漫游时的兼容性问题，帮助使用海外 SIM 卡获得更好的本地化体验，解锁运营商限制，突破区域限制
* [KotatsuApp/Kotatsu](https://github.com/KotatsuApp/Kotatsu) - Manga reader for Android *(archived)*
* [florisboard/florisboard](https://github.com/florisboard/florisboard) - An open-source keyboard for Android which respects your privacy. Currently in beta.
* [TeamVanced/VancedManager](https://github.com/TeamVanced/VancedManager) - Vanced Installer *(archived)*
* [MorpheApp/morphe-manager](https://github.com/MorpheApp/morphe-manager) - Morphe app patcher for Android
* [CeuiLiSA/Pixiv-Shaft](https://github.com/CeuiLiSA/Pixiv-Shaft) - Pixiv第三方Android客户端
* [aniyomiorg/aniyomi](https://github.com/aniyomiorg/aniyomi) - An app for manga and anime
* [permissionlesstech/bitchat-android](https://github.com/permissionlesstech/bitchat-android) - decentralized mesh chat
* [d4rken-org/sdmaid-se](https://github.com/d4rken-org/sdmaid-se) - SD Maid 2/SE is Android's most thorough cleaning tool.
* [ReadYouApp/ReadYou](https://github.com/ReadYouApp/ReadYou) - An Android RSS reader presented in Material You style.
* [Droid-ify/client](https://github.com/Droid-ify/client) - Clutterfree F-Droid client, [mirror] https://codeberg.org/droidify/client
* [XayahSuSuSu/Android-DataBackup](https://github.com/XayahSuSuSu/Android-DataBackup) - DataBackup for Android 7.0+
* [LibChecker/LibChecker](https://github.com/LibChecker/LibChecker) - An app to view libraries used in apps in your device.
* [plainhub/plain-app](https://github.com/plainhub/plain-app) - 🔥 PlainApp is an open-source app that lets you securely manage your phone from a web browser. Access files, media, contacts, SMS, calls, and more through a simple, easy-to-use interface on your desktop.
* [chrisbanes/tivi](https://github.com/chrisbanes/tivi) - Tivi is a TV show tracking Android app, which connects to trakt.tv *(archived)*
* [aistra0528/Hail](https://github.com/aistra0528/Hail) - Disable / Hide / Suspend / Uninstall Android apps without root.
* [gotson/komga](https://github.com/gotson/komga) - Media server for comics/mangas/BDs/magazines/eBooks with API, OPDS, Kobo Sync and KOReader Sync support
* [wxxsfxyzm/InstallerX-Revived](https://github.com/wxxsfxyzm/InstallerX-Revived) - More Expressive InstallerX !
* [PixelPlayerHQ/PixelPlayer](https://github.com/PixelPlayerHQ/PixelPlayer) - privacy-first Android music player built with Material 3 Expressive. Play offline, sync lyrics, fine-tune with equalizer presets, and cast to your devices.
* [shiaho777/web-to-app](https://github.com/shiaho777/web-to-app) - The most full featured web-to-app toolkit on Android, a complete APK workshop that runs entirely on your phone
* [TeamAmaze/AmazeFileManager](https://github.com/TeamAmaze/AmazeFileManager) - Material design file manager for Android
* [mozilla-mobile/fenix](https://github.com/mozilla-mobile/fenix) - ⚠️ Fenix (Firefox for Android) moved to a new repository. It is now developed and maintained as part of: https://github.com/mozilla-mobile/firefox-android *(archived)*
* [rukamori/ArchiveTune](https://github.com/rukamori/ArchiveTune) - 🌸 The Cutest Music Player With Support Local File and Youtube Music for Android!
* [HeliBorg/HeliBoard](https://github.com/HeliBorg/HeliBoard) - Customizable and privacy-conscious open-source keyboard
* [HapeLee/legado-with-MD3](https://github.com/HapeLee/legado-with-MD3) - 使用 Material Design 3 全新设计的阅读 3.0
* [z-huang/InnerTune](https://github.com/z-huang/InnerTune) - A Material 3 YouTube Music client for Android
* [samolego/Canta](https://github.com/samolego/Canta) - Uninstall any Android app without root (with power of Shizuku). Debloat your device as you wish, no PC required.
* [kickstarter/android-oss](https://github.com/kickstarter/android-oss) - Kickstarter for Android. Bring new ideas to life, anywhere.
* [capcom6/android-sms-gateway](https://github.com/capcom6/android-sms-gateway) - The SMS Gateway for Android™ app enables sending and receiving SMS messages through an API that can be accessed directly on the device or via a cloud server when direct device access is not possible.
* [fcitx5-android/fcitx5-android](https://github.com/fcitx5-android/fcitx5-android) - Fcitx5 input method framework and engines ported to Android
* [nextcloud/android](https://github.com/nextcloud/android) - 📱 Nextcloud Android app
* [tasks/tasks](https://github.com/tasks/tasks) - Bringing Astrid Tasks back from the dead
* [OuterTune/OuterTune](https://github.com/OuterTune/OuterTune) - A Material 3 Music Player for Android with local file & YouTube Music support. Forked from InnerTune
* [RetroMusicPlayer/RetroMusicPlayer](https://github.com/RetroMusicPlayer/RetroMusicPlayer) - Best Material You Design music player for Android
* [hxh19950701/WebViewTvLive](https://github.com/hxh19950701/WebViewTvLive) - A TV Live Streaming App developed using Tencent X5 WebView
* [MM2-0/Kvaesitso](https://github.com/MM2-0/Kvaesitso) - A search-focused Android launcher
* [NeoApplications/Neo-Store](https://github.com/NeoApplications/Neo-Store) - An F-Droid client with modern UI and an arsenal of extra features.
* [VREMSoftwareDevelopment/WiFiAnalyzer](https://github.com/VREMSoftwareDevelopment/WiFiAnalyzer) - Android application to analyze Wi-Fi signals.
* [muzei/muzei](https://github.com/muzei/muzei) - Muzei Live Wallpaper for Android
* [Aliucord/Aliucord](https://github.com/Aliucord/Aliucord) - A mod for the Discord Android App
* [duckduckgo/Android](https://github.com/duckduckgo/Android) - DuckDuckGo Android App
* [streetcomplete/StreetComplete](https://github.com/streetcomplete/StreetComplete) - Easy to use OpenStreetMap editor for Android
* [komikku-app/komikku](https://github.com/komikku-app/komikku) - Free and open source manga reader for Android
* [FooIbar/EhViewer](https://github.com/FooIbar/EhViewer) - EhViewer overhauled with Material Design 3 and more, forked from https://github.com/Ehviewer-Overhauled/Ehviewer
* [keiyoushi/extensions-source](https://github.com/keiyoushi/extensions-source) - Source code of extensions in https://github.com/keiyoushi/extensions
* [lizongying/my-tv-0](https://github.com/lizongying/my-tv-0) - 我的電視·〇 電視視頻播放軟件，可以自定義視頻源
* [osfans/trime](https://github.com/osfans/trime) - 同文安卓輸入法平臺3.x/Android-rime/Rime Input Method Engine for Android
* [tangshimin/MuJing](https://github.com/tangshimin/MuJing) - 一款通过电影、美剧或文档中的真实语境学习英语单词的应用，让您在原汁原味的情境中记忆词汇，提升学习效率。
* [moezbhatti/qksms](https://github.com/moezbhatti/qksms) - The most beautiful SMS messenger for Android
* [jay3-yy/BiliPai](https://github.com/jay3-yy/BiliPai) - 原生、纯净、可扩展 —— 重新定义你的 B 站体验
* [jellyfin/jellyfin-androidtv](https://github.com/jellyfin/jellyfin-androidtv) - Android TV Client for Jellyfin
* [jing332/tts-server-android](https://github.com/jing332/tts-server-android) - 这是一个Android系统TTS应用，内置微软演示接口，可自定义HTTP请求，可导入其他本地TTS引擎，以及根据中文双引号的简单旁白/对话识别朗读 ，还有自动重试，备用配置，文本替换等更多功能。
* [anilbeesetti/nextplayer](https://github.com/anilbeesetti/nextplayer) - An Android native video player
* [fumiama/copymanga](https://github.com/fumiama/copymanga) - 拷贝漫画的第三方APP，仅提供基础功能，更多丰富功能请移步官方版本
* [OxygenCobalt/Auxio](https://github.com/OxygenCobalt/Auxio) - A simple, rational music player for android
* [jarnedemeulemeester/findroid](https://github.com/jarnedemeulemeester/findroid) - Third-party native Jellyfin Android app
* [owncloud/android](https://github.com/owncloud/android) - :phone: The ownCloud Android App
* [zly2006/zhihu-plus-plus](https://github.com/zly2006/zhihu-plus-plus) - Zhihu++ | 知乎++: Ad-free, low cost, AI powered zhihu android 3rd-party client. 去广告、占用低、AI大模型的新时代知乎安卓端体验
* [KieronQuinn/TapTap](https://github.com/KieronQuinn/TapTap) - Port of the double tap on back of device feature from Android 12 to any Android 7.0+ device
* [SimpleMobileTools/Simple-Gallery](https://github.com/SimpleMobileTools/Simple-Gallery) - A premium app for managing and editing your photos, videos, GIFs without ads
* [easybangumiorg/EasyBangumi](https://github.com/easybangumiorg/EasyBangumi) - 纯纯看番，使用 Compose 开发的 Android 看番软件，支持多番剧源
* [videolan/vlc-android](https://github.com/videolan/vlc-android) - VLC for Android, Android TV and ChromeOS
* [HdShare/WAuxiliary_Public](https://github.com/HdShare/WAuxiliary_Public) - WeChat Auxiliary Public
* [rumboalla/apkupdater](https://github.com/rumboalla/apkupdater) - APKUpdater is an open source tool that simplifies the process of finding updates for your installed apps.
* [aaa1115910/bv](https://github.com/aaa1115910/bv) - 哔哩哔哩 的第三方 Android 应用。A third-party Android app for Bilibili.
* [home-assistant/android](https://github.com/home-assistant/android) - Home Assistant Companion for Android
* [tanujnotes/Olauncher](https://github.com/tanujnotes/Olauncher) - Minimal AF Launcher for Android. Reduce your screen time. Daily wallpapers.
* [iamr0s/Dhizuku](https://github.com/iamr0s/Dhizuku) - A tool that can share DeviceOwner permissions to other application.
* [BiliRoamingX/BiliRoamingX](https://github.com/BiliRoamingX/BiliRoamingX) - BiliRoamingX integrations and patches powered by ReVanced.
* [TermoraDev/termora](https://github.com/TermoraDev/termora) - Termora is a terminal emulator and SSH client for Windows, macOS and Linux.
* [element-hq/element-android](https://github.com/element-hq/element-android) - A Matrix collaboration client for Android.
* [mollyim/mollyim-android](https://github.com/mollyim/mollyim-android) - Enhanced and security-focused fork of Signal.
* [FossifyOrg/Gallery](https://github.com/FossifyOrg/Gallery) - Browse your memories without any interruptions with this photo and video gallery
* [EhViewer-NekoInverter/EhViewer](https://github.com/EhViewer-NekoInverter/EhViewer) - 🥥 A fork of EhViewer, feature requests are not accepted. Forked from https://gitlab.com/NekoInverter/EhViewer
* [GuoXiCheng/SKIP](https://github.com/GuoXiCheng/SKIP) - 自动跳过APP开屏广告
* [SimpleMobileTools/Simple-Calendar](https://github.com/SimpleMobileTools/Simple-Calendar) - A simple calendar with events, tasks, customizable colors, widgets and no ads.
* [gurecn/YuyanIme](https://github.com/gurecn/YuyanIme) - 语燕输入法-一款基于Rime定制开发的九键、全拼、双拼、手写、火星文等方案、支持悬浮、单手、数字行等键盘模式的中文输入法
* [Nain57/Smart-AutoClicker](https://github.com/Nain57/Smart-AutoClicker) - An open-source auto clicker on images for Android
* [mpv-android/mpv-android](https://github.com/mpv-android/mpv-android) - Video player for Android based on libmpv ↦ #mpv-android @ irc.libera.chat
* [JetBrains/kotlinconf-app](https://github.com/JetBrains/kotlinconf-app) - The official KotlinConf application
* [brahmkshatriya/echo](https://github.com/brahmkshatriya/echo) - Just a music player.
* [KieronQuinn/Smartspacer](https://github.com/KieronQuinn/Smartspacer) - Smartspacer is a customisable widget for Android, but with a difference: It can upgrade the built in At a Glance on Pixels - without root!
* [etchdroid/etchdroid](https://github.com/etchdroid/etchdroid) - An application to write OS images to USB drives, on Android, no root required.
* [connectbot/connectbot](https://github.com/connectbot/connectbot) - ConnectBot is the first SSH client for Android.
* [cwuom/NeriPlayer](https://github.com/cwuom/NeriPlayer) - A native Android audio player that combines multi-source streaming, local control, rich lyrics, and self-hosted sync. / ✨ 一个把多源在线播放、本地管理、歌词体验和自建同步做进原生 Android 的音频播放器 🎵
* [LSPosed/CorePatch](https://github.com/LSPosed/CorePatch) - Disable signature verification For Android
* [YenalyLiew/Han1meViewer](https://github.com/YenalyLiew/Han1meViewer) - [Deprecated] Thanks for your support!
* [zacharee/InstallWithOptions](https://github.com/zacharee/InstallWithOptions) - Simple-ish app using Shizuku to install APKs on-device with advanced options
* [frknkrc44/HMA-OSS](https://github.com/frknkrc44/HMA-OSS) - A Zygisk module to hide your app list, settings, package installers and more. It is a fork of Hide My Applist project, but LSPosed dependency is replaced with Zygisk.
* [Ivy-Apps/ivy-wallet](https://github.com/Ivy-Apps/ivy-wallet) - Ivy Wallet is an open-source money manager app for Android, no longer maintained. You can fork the code or download the final version from Google Play. *(archived)*
* [Mahmud0808/Iconify](https://github.com/Mahmud0808/Iconify) - Iconify lets you customize your Android 12+ device easily. Change icons, colors, shapes, and even the notification panel for a personalized look that suits your style.
* [wordpress-mobile/WordPress-Android](https://github.com/wordpress-mobile/WordPress-Android) - WordPress for Android
* [PaulWoitaschek/Voice](https://github.com/PaulWoitaschek/Voice) - Minimalistic audiobook player
* [PranshulGG/WeatherMaster](https://github.com/PranshulGG/WeatherMaster) - A Weather app for android with multiple sources 🌦🌞☔
* [f-droid/fdroidclient](https://github.com/f-droid/fdroidclient) - Android client application.
* [spacecowboy/Feeder](https://github.com/spacecowboy/Feeder) - Android feed reader app
* [kyujin-cho/pixel-volte-patch](https://github.com/kyujin-cho/pixel-volte-patch) - Pixel IMS: Rootless replacement for Tensor Pixel VoLTE patch
* [wikimedia/apps-android-wikipedia](https://github.com/wikimedia/apps-android-wikipedia) - 📱The official Wikipedia app for Android!
* [sameerasw/essentials](https://github.com/sameerasw/essentials) - Essential tools and mods for Android nerds
* [mahlernim/google-timeline-visualizer](https://github.com/mahlernim/google-timeline-visualizer) - Visualize your year in travel using your Google Location History (Timeline) data
* [CYQawa/YunX](https://github.com/CYQawa/YunX) - ✨一个安卓网盘解析下载app✨
* [whyorean/AuroraStore](https://github.com/whyorean/AuroraStore)
* [NexAlloy/NexAlloy](https://github.com/NexAlloy/NexAlloy) - ChsBuffer's LSPosed module, powered by Morphe, ReVanced, and beyond. (formerly ReVanced Xposed)
* [10miaomiao/bilimiao2](https://github.com/10miaomiao/bilimiao2) - bilimiao 2.x
* [chenxiaolong/BCR](https://github.com/chenxiaolong/BCR) - A Basic Call Recorder for rooted Android devices
* [damontecres/Wholphin](https://github.com/damontecres/Wholphin) - An OSS Android TV client for Jellyfin
* [bitfireAT/davx5-ose](https://github.com/bitfireAT/davx5-ose) - DAVx⁵ is an open-source CalDAV/CardDAV suite and sync app for Android. You can also access your online files (WebDAV) with it.
* [kylecorry31/Trail-Sense](https://github.com/kylecorry31/Trail-Sense) - An Android app that uses your phone's sensors to assist with wilderness treks or survival situations.
* [wangchenyan/ponymusic](https://github.com/wangchenyan/ponymusic) - An Android online music player like NetEase Cloud Music, based on Media3 and ExoPlayer
* [caiyonglong/MusicLake](https://github.com/caiyonglong/MusicLake) - MediaPlayer、Exoplayer音乐播放器，可播在线音乐，qq音乐，百度音乐，虾米音乐，网易云音乐，YouTuBe
* [Automattic/pocket-casts-android](https://github.com/Automattic/pocket-casts-android) - Pocket Casts Android 🎧
* [vivizzz007/vivi-music](https://github.com/vivizzz007/vivi-music) - Vivi-Music is an expressive Material 3–based YouTube Music client for Android.
* [orgzly/orgzly-android](https://github.com/orgzly/orgzly-android) - Outliner for taking notes and managing to-do lists
* [IacobIonut01/ReFra](https://github.com/IacobIonut01/ReFra) - Media Gallery app for Android made with Jetpack Compose
* [nekomangaorg/Neko](https://github.com/nekomangaorg/Neko) - Unofficial MangaDex Reader for Android 8+
* [jellyfin/jellyfin-android](https://github.com/jellyfin/jellyfin-android) - Android Client for Jellyfin
* [sam1am/anyapk](https://github.com/sam1am/anyapk) - Install any apk on the device you own.
* [TwidereProject/Twidere-Android](https://github.com/TwidereProject/Twidere-Android)
* [Luoyacheng/legado-E](https://github.com/Luoyacheng/legado-E) - 阅读Sigma是legado的继承，保持开源免费，延续开源精神。
* [NuvioMedia/NuvioTV](https://github.com/NuvioMedia/NuvioTV) - Official Nuvio Android TV Repository
* [keymapperorg/KeyMapper](https://github.com/keymapperorg/KeyMapper) - An Android app to remap the buttons on your devices
* [android-password-store/Android-Password-Store](https://github.com/android-password-store/Android-Password-Store) - Android application compatible with ZX2C4's Pass command line application *(archived)*
* [cat3399/blbl](https://github.com/cat3399/blbl) - 一个使用原生Android开发的哔哩哔哩安卓客户端，支持触摸、遥控，以及安卓5 *(archived)*
* [Ccixyj/JBusDriver](https://github.com/Ccixyj/JBusDriver) - 这是去幼儿园的班车(滑稽
* [CrossPaste/crosspaste-desktop](https://github.com/CrossPaste/crosspaste-desktop) - Cross-device clipboard sync for macOS, Windows & Linux — end-to-end encrypted, LAN-only, no cloud. OCR, CLI and MCP server built in.
* [tuskyapp/Tusky](https://github.com/tuskyapp/Tusky) - An Android client for the microblogging server Mastodon *(archived)*
* [oliexdev/openScale](https://github.com/oliexdev/openScale) - Open-source weight and body metrics tracker, with support for Bluetooth scales
* [dkrivoruchko/ScreenStream](https://github.com/dkrivoruchko/ScreenStream) - ScreenStream Android App
* [legendsayantan/ShizuTools](https://github.com/legendsayantan/ShizuTools) - Contains many tools to control android system via shizuku.
* [marlboro-advance/mpvEx](https://github.com/marlboro-advance/mpvEx) - A beautiful media player for android, based on mpv-android and built with Jetpack Compose. Forked from mpvKt
* [KieronQuinn/AmbientMusicMod](https://github.com/KieronQuinn/AmbientMusicMod) - Port of Now Playing from Pixels to other Android devices
* [seemoo-lab/AirGuard](https://github.com/seemoo-lab/AirGuard) - Protect yourself from being tracked 🌍 by AirTags 🏷 and Find My accessories 📍
* [wdsqjq/FengYunWeather](https://github.com/wdsqjq/FengYunWeather) - 风云天气是Android 平台开源天气 App，采用Kotlin、Room、OKHttp3、 协程等框架实现。
* [Mahmud0808/ColorBlendr](https://github.com/Mahmud0808/ColorBlendr) - An Android app for customizing Material You colors on devices with Android 12+. It lets you tweak accent colors, background saturation, and more for a personalized look.
* [fossasia/susi_android](https://github.com/fossasia/susi_android) - SUSI.AI Android App https://play.google.com/apps/testing/ai.susi *(archived)*
* [ByronNote/MinimalistWeather](https://github.com/ByronNote/MinimalistWeather) - 一款基于 Kotlin、Jetpack Compose 与 Clean Architecture 构建的现代 Android 天气应用，支持动态天气场景、全球城市搜索、空气质量、24 小时与 7 日预报，数据来自 Open-Meteo。
* [anthonycr/Lightning-Browser](https://github.com/anthonycr/Lightning-Browser) - A lightweight Android browser with modern navigation
* [andreknieriem/open-headunit](https://github.com/andreknieriem/open-headunit) - Headunit App for displaying Android Auto
* [msasikanth/twine](https://github.com/msasikanth/twine) - Twine: A multiplatform RSS reader built using Kotlin and Compose
* [tytydraco/LADB](https://github.com/tytydraco/LADB) - A local ADB shell for Android!
* [barbeau/gpstest](https://github.com/barbeau/gpstest) - The #1 open-source Android GNSS/GPS test program
* [lihenggui/blocker](https://github.com/lihenggui/blocker) - Utilize an integrated firewall to manage application components.
* [quran/quran_android](https://github.com/quran/quran_android) - a quran reading application for android
* [corona-warn-app/cwa-app-android](https://github.com/corona-warn-app/cwa-app-android) - Native Android app using the Apple/Google exposure notification API. The CWA development ends on May 31, 2023. You still can warn other users until April 30, 2023. More information: *(archived)*
* [element-hq/element-x-android](https://github.com/element-hq/element-x-android) - Android Matrix messenger application using the Matrix Rust Sdk and Jetpack Compose
* [markusfisch/BinaryEye](https://github.com/markusfisch/BinaryEye) - Yet another barcode scanner for Android
* [Fate-Grand-Automata/FGA](https://github.com/Fate-Grand-Automata/FGA) - Auto-battle app for F/GO Android
* [DP-Hridayan/aShellYou](https://github.com/DP-Hridayan/aShellYou) - A material you designed app for your ADB needs
* [Xed-Editor/Xed-Editor](https://github.com/Xed-Editor/Xed-Editor) - Advanced Text Editor for Android
* [FoedusProgramme/Gramophone](https://github.com/FoedusProgramme/Gramophone) - A sane music player built with media3 and material design library that is following android's standard strictly.
* [VegaBobo/DSU-Sideloader](https://github.com/VegaBobo/DSU-Sideloader) - A simple app made to help users easily install GSIs via DSU's Android feature.
* [kawaiiDango/pano-scrobbler](https://github.com/kawaiiDango/pano-scrobbler) - Feature rich scrobbler for Windows, Linux & Android. Supports Last.fm, ListenBrainz, Libre.fm & Pleroma. With regex edits, charts & Discord Rich Presence on PC.
* [flipperdevices/Flipper-Android-App](https://github.com/flipperdevices/Flipper-Android-App) - Android Mobile app to rule all Flipper's family
* [accrescent/accrescent](https://github.com/accrescent/accrescent) - A novel Android app store focused on security, privacy, and usability
* [AhmetCanArslan/ShizuWall](https://github.com/AhmetCanArslan/ShizuWall) - Lightweight, no vpn firewall solution for Android 11+
* [A-EDev/Flow](https://github.com/A-EDev/Flow) - A modern, feature-rich YouTube and YouTube Music client with local recommendation for Android built with Jetpack Compose
* [hefengbao/jingmo](https://github.com/hefengbao/jingmo) - 『京墨』开源的中华文化阅读 APP，诗（词）文（名句）、汉字、成语、词语、歇后语、绕口令、传统节日、传统色、节气、人物等。
* [mhss1/MyBrain](https://github.com/mhss1/MyBrain) - All-in-one productivity app and AI assistant with Tasks, Notes, Calendar, Diary and Bookmarks.
* [OmGodse/Notally](https://github.com/OmGodse/Notally) - A beautiful notes app
* [MMRLApp/MMRL](https://github.com/MMRLApp/MMRL) - A app for managing, sharing, and exploring Magisk modules across repositories
* [FossifyOrg/Calendar](https://github.com/FossifyOrg/Calendar) - A simple calendar with events, customizable widgets and no ads.
* [UweTrottmann/SeriesGuide](https://github.com/UweTrottmann/SeriesGuide) - Track your favorite TV shows and movies with this Android app
* [yjeanrenaud/yj_nearbyglasses](https://github.com/yjeanrenaud/yj_nearbyglasses) - attempting to detect smart glasses nearby and warn you
* [prajwalch/TorrentSearch](https://github.com/prajwalch/TorrentSearch) - An Android app for searching torrents across multiple providers - fast, detailed, and packed with actions.
* [dmzz-yyhyy/LightNovelReader](https://github.com/dmzz-yyhyy/LightNovelReader) - 一款基于Compose的多数据源轻小说阅读器。支持epub导出，自定义背景样式，本地书架和更新提醒等功能。
* [LinkSheet/LinkSheet](https://github.com/LinkSheet/LinkSheet) - Link handling for modern Android
* [ZacSweers/CatchUp](https://github.com/ZacSweers/CatchUp) - An app for catching up on things.
* [LawnchairLauncher/lawnicons](https://github.com/LawnchairLauncher/lawnicons) - Monochrome outlined brand icons for Android launchers.
* [mozilla-mobile/focus-android](https://github.com/mozilla-mobile/focus-android) - ⚠️ Firefox Focus (Android) moved to a new repository. It is now developed and maintained as part of: https://github.com/mozilla-mobile/firefox-android *(archived)*
* [JakeWharton/SdkSearch](https://github.com/JakeWharton/SdkSearch) - An Android app and Chrome extension for searching the Android SDK documentation. *(archived)*
* [pass-with-high-score/blockads-android](https://github.com/pass-with-high-score/blockads-android) - Block ads system-wide on Android using local VPN-based DNS filtering. No root needed. No data collection.
* [plateaukao/einkbro](https://github.com/plateaukao/einkbro) - A small, fast web browser based on Android WebView. It's tailored for E-Ink devices but also works great on normal android devices.
* [fossasia/open-event-attendee-android](https://github.com/fossasia/open-event-attendee-android) - Open Event Attendee Android General App https://github.com/fossasia/open-event-android/blob/apk/open-event-dev-app-playStore-debug.apk *(archived)*
* [telegram-sms/telegram-sms](https://github.com/telegram-sms/telegram-sms) - An SMS-forwarding Robot Running on Your Android Device.
* [ActivityLauncher/ActivityLauncher](https://github.com/ActivityLauncher/ActivityLauncher) - Activity launcher creates shortcuts for any installed app and hidden activities to launch them with ease
* [Hamza417/Inure](https://github.com/Hamza417/Inure) - An elegant and beautiful premium Android app manager with Root and Shizuku support, a built-in terminal, analytics, virustotal, debloat, stats and various other features with a custom theme engine, developed with purely custom UI design and reproducible build.
* [adrcotfas/goodtime](https://github.com/adrcotfas/goodtime) - A productivity app that combines pomodoro timers and flow techniques to boost focus and efficiency.
* [ingbyr/vdm](https://github.com/ingbyr/vdm) - GUI for command-line video downloader (youtube-dl annie) *(archived)*
* [rosuH/EasyWatermark](https://github.com/rosuH/EasyWatermark) - 🔒 🖼 Securely, easily add a watermark to your sensitive photos. 安全、简单地为你的敏感照片添加水印，防止被人泄露、利用
* [tyron12233/CodeAssist](https://github.com/tyron12233/CodeAssist) - An IDE for building Android applicatons on Android.
* [enricocid/Music-Player-GO](https://github.com/enricocid/Music-Player-GO) - 🎶🎼 Very slim music player 👨‍🎤 100% made in Italy 🍕🌳🌞🍝🌄 *(archived)*
* [null2264/yokai](https://github.com/null2264/yokai) - Free and open source manga reader for Android
* [massivemadness/Squircle-CE](https://github.com/massivemadness/Squircle-CE) - 👨‍💻 Squircle CE is a fast and free multi-language code editor for Android
* [ptrpaws/Oculess](https://github.com/ptrpaws/Oculess) - Removes account requirements and telemetry from Oculus Quest devices
* [meganz/android](https://github.com/meganz/android) - MEGA Android App
* [iamr0s/InstallerX](https://github.com/iamr0s/InstallerX) - A modern and functional Android app installer. (You know some birds are not meant to be caged, their feathers are just too bright.) *(archived)*
* [yaoxieyoulei/mytv-android](https://github.com/yaoxieyoulei/mytv-android) - 使用Android原生开发的视频播放软件 *(archived)*
* [saket/press](https://github.com/saket/press) - Cross-platform markdown editor written in Kotlin Multiplatform (work in progress) *(archived)*
* [termux/termux-styling](https://github.com/termux/termux-styling) - Termux add-on app for customizing the terminal font and color theme.
* [ZalithLauncher/ZalithLauncher2](https://github.com/ZalithLauncher/ZalithLauncher2) - A Minecraft: Java Edition Launcher for Android
* [sky-map-team/stardroid](https://github.com/sky-map-team/stardroid) - Sky Map (formerly Google Sky Map, open sourced in 2012)
* [aj3423/SpamBlocker](https://github.com/aj3423/SpamBlocker) - Android Call/SMS blocker.
* [meshtastic/Meshtastic-Android](https://github.com/meshtastic/Meshtastic-Android) - Android application for Meshtastic
* [seedvault-app/seedvault](https://github.com/seedvault-app/seedvault) - A backup application for the Android Open Source Project.
* [mozilla-mobile/firefox-android](https://github.com/mozilla-mobile/firefox-android) - :warning: This repository hosts the Firefox for Android (Fenix), Focus for Android, and Mozilla Android Components projects. It is now developed and maintained as part of Mozilla Central. See the announcement here: https://github.com/mozilla-mobile/firefox-android/wiki#upcoming-migration-to-mozilla-central. ” *(archived)*
* [rRemix/APlayer](https://github.com/rRemix/APlayer) - Android Music Player
* [LagradOst/QuickNovel](https://github.com/LagradOst/QuickNovel) - Android app for downloading novels
* [HabitRPG/habitica-android](https://github.com/HabitRPG/habitica-android) - Native Android app for Habitica
* [tuanchauict/MonoSketch](https://github.com/tuanchauict/MonoSketch) - An ASCII graph drawing app
* [Waboodoo/HTTP-Shortcuts](https://github.com/Waboodoo/HTTP-Shortcuts) - Android app to create home screen shortcuts that trigger arbitrary HTTP requests and more
* [futo-org/grayjay-android](https://github.com/futo-org/grayjay-android) - Read-only mirror of Grayjay repo for issue tracking
* [feelfreelinux/octo4a](https://github.com/feelfreelinux/octo4a) - Use your old Android device as an OctoPrint server.
* [FossifyOrg/File-Manager](https://github.com/FossifyOrg/File-Manager) - Easy app for managing your files without ads, respecting your privacy & security
* [owntracks/android](https://github.com/owntracks/android) - OwnTracks Android App
* [zacharee/Tweaker](https://github.com/zacharee/Tweaker)
* [ProtonMail/proton-mail-android](https://github.com/ProtonMail/proton-mail-android) - Proton Mail Android app *(archived)*
* [Dev4Mod/WaEnhancer](https://github.com/Dev4Mod/WaEnhancer) - WhatsApp tools for Android
* [truefedex/tv-bro](https://github.com/truefedex/tv-bro) - Simple web browser for android optimized to use with TV remote
* [zyrouge/symphony](https://github.com/zyrouge/symphony) - 🎵 Lightweight, elegant music player for Android 9+.
* [ryfineZ/carrier-ims-for-pixel](https://github.com/ryfineZ/carrier-ims-for-pixel) - Carrier IMS for Pixel (TurboIMS): multilingual (中文/English) pixel ims / ims / carrierconfig / volte / vowifi / 5G+ toolkit for Google Pixel.
* [15dd/wenku8reader](https://github.com/15dd/wenku8reader) - 第三方轻小说文库app *(archived)*
* [xyoye/DanDanPlayForAndroid](https://github.com/xyoye/DanDanPlayForAndroid) - 弹弹play 概念版，弹弹play系列应用安卓平台上的实现，是一个提供了视频播放（本地+局域网）和弹幕加载（在线+本地）功能的本地播放器
* [Myzel394/Alibi](https://github.com/Myzel394/Alibi) - Use your phone as a dashcam and save the last 30 minutes when you need them.
* [KieronQuinn/DarQ](https://github.com/KieronQuinn/DarQ) - DarQ provides a per-app selectable force dark option for Android 10 and above *(archived)*
* [igorescodro/alkaa](https://github.com/igorescodro/alkaa) - Kotlin multiplatform app to manage your tasks
* [Lucchetto/SuperImage](https://github.com/Lucchetto/SuperImage) - Sharpen your low-resolution pictures with the power of AI upscaling *(archived)*
* [BaltiApps/Pixelify-Google-Photos](https://github.com/BaltiApps/Pixelify-Google-Photos) - Pixelify GPhotos
* [parallelcc/MiCTS](https://github.com/parallelcc/MiCTS) - Trigger Circle to Search on any Android 9–16 device
* [vitorpamplona/amethyst](https://github.com/vitorpamplona/amethyst) - Nostr client for Android
* [zacharee/Bifrost](https://github.com/zacharee/Bifrost) - Cross-platform tool for downloading Samsung mobile device firmware.
* [SimpleMobileTools/Simple-File-Manager](https://github.com/SimpleMobileTools/Simple-File-Manager) - Easy app for managing your files without ads, respecting your privacy & security
* [FossifyOrg/Messages](https://github.com/FossifyOrg/Messages) - An easy and quick way of managing SMS and MMS messages without ads.
* [dessalines/thumb-key](https://github.com/dessalines/thumb-key) - A privacy-conscious Android keyboard made for your thumbs
* [you-apps/TranslateYou](https://github.com/you-apps/TranslateYou) - Privacy focused translator app built with MD3
* [allgood/OpenNoteScanner](https://github.com/allgood/OpenNoteScanner) - Android application for scanning and manipulating handwritten notes and documents.
* [KieronQuinn/uTag](https://github.com/KieronQuinn/uTag) - Use Samsung Galaxy SmartTags on any Android device
* [naman14/TimberX](https://github.com/naman14/TimberX) - Material theme music player that works across all form factors (phones, wear, auto, cast, assistant) and uses latest tools (Kotlin, Architecture components, Room, Databinding)
* [clementwzk/OpenCalc](https://github.com/clementwzk/OpenCalc) - A simple and beautiful calculator for Android downloaded more than 300k times
* [DimensionDev/Flare](https://github.com/DimensionDev/Flare) - Browse Mastodon, Bluesky, X, Misskey, Nostr, Pixiv, Fanbox and RSS all in one app. One timeline, all your accounts, cross-post everywhere.
* [helloklf/vtools](https://github.com/helloklf/vtools) - 一个集高级重启、应用安装自动点击、CPU调频等多项功能于一体的工具箱。
* [Pool-Of-Tears/Myne](https://github.com/Pool-Of-Tears/Myne) - An android app to download & read ebooks from Project Gutenberg, built with Jetpack Compose.
* [Aliothmoon/MAA-Meow](https://github.com/Aliothmoon/MAA-Meow) - 《明日方舟》小助手Android版，全日常一键长草！| A one-click tool for the daily tasks of Arknights, supporting all clients.
* [kitsumed/ShizuCallRecorder](https://github.com/kitsumed/ShizuCallRecorder) - ShizuCallRecorder empowers ADB through Shizuku to record phone calls on non-rooted device!
* [twofas/2fas-android](https://github.com/twofas/2fas-android) - Source code for 2FAS Auth Android app
* [salvogiangri/KnoxPatch](https://github.com/salvogiangri/KnoxPatch) - LSPosed module to get Samsung apps/features working again in your rooted Galaxy device.
* [DicioTeam/dicio-android](https://github.com/DicioTeam/dicio-android) - Dicio assistant app for Android
* [rt-bishop/Look4Sat](https://github.com/rt-bishop/Look4Sat) - Satellite tracker and pass predictor for Android, inspired by Gpredict
* [kiwix/kiwix-android](https://github.com/kiwix/kiwix-android) - Kiwix for Android
* [trakt/showly](https://github.com/trakt/showly) - Showly is a modern and slick Movies and TV Shows manager.
* [Mangi-11/Eta](https://github.com/Mangi-11/Eta) - Android 系统级 AI Agent——越过沙盒，让模型访问底层API、屏幕、终端与你的数据
* [Moriafly/DsoMusic](https://github.com/Moriafly/DsoMusic) - Kotlin 开发的美观安卓音乐软件，音源：网易云音乐、QQ 音乐、酷我音乐、Bilibili *(archived)*
* [cyb3rko/flashdim](https://github.com/cyb3rko/flashdim) - Modern flashlight app with dim functionality on Android 13+
* [KDE/kdeconnect-android](https://github.com/KDE/kdeconnect-android) - Native Android port of the KDE Connect Qt app
* [nsh07/Tomato](https://github.com/nsh07/Tomato) - Minimalist, data-oriented pomodoro timer for Android and Desktop based on Material 3 Expressive
* [pass-with-high-score/universal-installer](https://github.com/pass-with-high-score/universal-installer) - A modern Android app for installing and managing APK packages with split APK support, silent install via Shizuku, and VirusTotal malware scanning.
* [sayaka-sh/spmp](https://github.com/sayaka-sh/spmp) - SpMp has been succeeded by Kanon, see README --- A YouTube Music client with a focus on customisation of colours and song metadata. Built with Compose Multiplatform for Android and desktop.
* [lanlinju/Animius](https://github.com/lanlinju/Animius) - 一个简洁的播放动漫的App，支持弹幕，多数据源等，使用Jetpack Compose进行开发
* [fahrez182/AxManager](https://github.com/fahrez182/AxManager) - AxManager is an Android application designed to provide deeper control over apps and the system.
* [WSTxda/SwitchAI](https://github.com/WSTxda/SwitchAI) - Easily select, start, and manage your preferred AI digital assistants on Android.
* [axel358/smartdock](https://github.com/axel358/smartdock) - A user-friendly desktop mode launcher that offers a modern and customizable user interface
* [WrBug/DeveloperHelper](https://github.com/WrBug/DeveloperHelper) - 📌易开发是一款帮助开发人员快速开发的工具，功能包括界面分析，页面信息，加固脱壳，支持Android9.0
* [roro2239/Stellar](https://github.com/roro2239/Stellar) - Another Shizuku impl
* [sakana164/mytv-android](https://github.com/sakana164/mytv-android) - 使用Android原生开发的电视直播软件 *(archived)*
* [Jasonzhu1207/ZenConverter](https://github.com/Jasonzhu1207/ZenConverter) - Local Android file converter built with Kotlin and Jetpack Compose. Convert files on device, with no ads, accounts, or upload-based fallback.
* [MatteCarra/AccA](https://github.com/MatteCarra/AccA) - Acc app allows to edit acc config file and add a tile to start and stop acc deamon
* [SimpleMobileTools/Simple-Music-Player](https://github.com/SimpleMobileTools/Simple-Music-Player) - A clean music player with a customizable widget, stylish interface and no ads.
* [Acclorite/book-story](https://github.com/Acclorite/book-story) - Book's Story — Material You eBook reader built with Jetpack Compose. Free & Open source & Ad-free, with extensive customization options and support for multiple file formats.
* [BinTianqi/OwnDroid](https://github.com/BinTianqi/OwnDroid) - 使用安卓Device owner特权管理你的设备。Use Android Device owner privilege to manage your device.
* [GrapheneOS/Camera](https://github.com/GrapheneOS/Camera) - Modern camera app focused on privacy and security with QR & barcode scanning.
* [Raival-e/Prism-File-Explorer](https://github.com/Raival-e/Prism-File-Explorer) - A modern, feature-rich, and lightweight file manager for Android, built entirely with Kotlin and Jetpack Compose.
* [BobbyESP/Spowlo](https://github.com/BobbyESP/Spowlo) - A Spotify songs downloader for Android made with Jetpack Compose, Material You and the spotDL Python library *(archived)*
* [jocmp/capyreader](https://github.com/jocmp/capyreader) - A smallish Android RSS reader
* [Tosencen/XMSLEEP](https://github.com/Tosencen/XMSLEEP) - 一款白噪音应用送给你，祝您牛掰，有的是钱
* [xdtianyu/CallerInfo](https://github.com/xdtianyu/CallerInfo) - 来电信息 - 一个获取号码归属地和其他信息（诈骗、骚扰等）的开源 Android 应用
* [DUpdateSystem/UpgradeAll](https://github.com/DUpdateSystem/UpgradeAll) - Check updates for Android apps, Magisk modules and more!
* [capntrips/KernelFlasher](https://github.com/capntrips/KernelFlasher) - Kernel Flasher is an Android app to flash, backup, and restore kernels. *(archived)*
* [curbox-app/curbox-android](https://github.com/curbox-app/curbox-android) - Free Open Source App & Website Blocker
* [DroidKaigi/conference-app-2018](https://github.com/DroidKaigi/conference-app-2018) - The Official Conference App for DroidKaigi 2018 Tokyo
* [horsemail/yourtv](https://github.com/horsemail/yourtv) - 安卓电视直播APK：IPTV/網頁視頻支持X5，可自定義源(支持webview://格式)，IPTV支持畫中畫和熄屏播放。 Android TV Live APK: IPTV/web video supports X5, customizable sources (support webview:// format), IPTV supports picture-in-picture and off-screen playback.
* [FossifyOrg/Phone](https://github.com/FossifyOrg/Phone) - A handy phone call manager with phonebook, number blocking and multi-SIM support
* [abdallahmehiz/mpvKt](https://github.com/abdallahmehiz/mpvKt) - A media player for android, based on mpv-android and built with Jetpack Compose. *(archived)*
* [MenosGrante/Rekado](https://github.com/MenosGrante/Rekado) - Payload launcher and serial number checker for Nintendo Switch
* [AudileTeam/Audile](https://github.com/AudileTeam/Audile) - An open-source Android app for music recognition that integrates AudD, ACRCloud, and Shazam to perform song identification.
* [sdex/ActivityManager](https://github.com/sdex/ActivityManager) - Launch any application activity
* [LemmyNet/jerboa](https://github.com/LemmyNet/jerboa) - A native Android app for Lemmy
* [F0x1d/LogFox](https://github.com/F0x1d/LogFox) - Yet another LogCat reader for Android
* [MateriiApps/OpenCord](https://github.com/MateriiApps/OpenCord) - An open-source Material You implementation of the Discord Android app *(archived)*
* [KieronQuinn/PixelLauncherMods](https://github.com/KieronQuinn/PixelLauncherMods) - A root app that enables you to add a number of features to the stock Pixel Launcher, without needing Xposed
* [BelledonneCommunications/linphone-android](https://github.com/BelledonneCommunications/linphone-android) - Linphone.org mirror for linphone-android (https://gitlab.linphone.org/BC/public/linphone-android)
* [Jman-Github/Universal-ReVanced-Manager](https://github.com/Jman-Github/Universal-ReVanced-Manager) - 💊 An Android application to use ReVanced, Morphe and AmpleReVanced on that has extra features the official manager doesn't have
* [twireapp/Twire](https://github.com/twireapp/Twire) - Twire is an alternative and open source Twitch client for Android
* [ligi/SurvivalManual](https://github.com/ligi/SurvivalManual) - Libre Survival Manual for Android with offline in mind
* [samyak2403/RepoStore](https://github.com/samyak2403/RepoStore) - Explore apps published on GitHub, view release details, and install APKs instantly — all in one place. Developed using pure Kotlin, optimized for modern Android devices.
* [Bartuzen/qBitController](https://github.com/Bartuzen/qBitController) - Control qBittorrent from any device
* [Lambada10/SongSync](https://github.com/Lambada10/SongSync) - Android app to download lyrics for songs in your music library.
* [hushenghao/AndroidEasterEggs](https://github.com/hushenghao/AndroidEasterEggs) - Android Easter Egg Collections
* [ShiftHackZ/Stable-Diffusion-KMP](https://github.com/ShiftHackZ/Stable-Diffusion-KMP) - Stable Diffusion AI client app for Android and iOS
* [SkyD666/PodAura](https://github.com/SkyD666/PodAura) - All-in-on podcast app for RSS, media dl & play. MVI arch, Material You style. ⭐️ Star to support!
* [ultranity/Pix-EzViewer](https://github.com/ultranity/Pix-EzViewer) - 一个支持免代理直连+多种额外特性功能优化的第三方 Pixiv android 客户端 | A third-party Pixiv Android client with modern design and many other enhancements
* [oxyroid/M3UAndroid](https://github.com/oxyroid/M3UAndroid) - a clean, practical, ad-free IPTV app
* [SimonSchubert/Kai](https://github.com/SimonSchubert/Kai) - OpenClaw alternative in your pocket
* [horizontalsystems/unstoppable-wallet-android](https://github.com/horizontalsystems/unstoppable-wallet-android) - A powerful non-custodial multi-wallet for Bitcoin, Ethereum, Binance Smart Chain, Avalanche, Solana and other blockchains. Non-custodial crypto and NFT storage, onchain decentralized exchange, institutional grade analytics for cryptcurrency and NFT markets, extensive privacy controls and human oriented design. Implemented on Kotlin.
* [dead8309/Kizzy](https://github.com/dead8309/Kizzy) - A Discord Rich Presence manager for Android fully written in Kotlin. Made with jetpack compose and material3
* [Androidacy/MagiskModuleManager](https://github.com/Androidacy/MagiskModuleManager) - Previously known as Fox's Magisk Module Manager (FoxMMM), this app helps users find, install "Magisk Modules" - powerful little zips/apps for your device that plug into the Magisk framework.
* [Taewan-P/gpt_mobile](https://github.com/Taewan-P/gpt_mobile) - Chat app for Android that supports answers from multiple LLMs at once. Bring your own API key AI client. Supports OpenAI, Anthropic, Google, and Ollama. Designed with Material3 & Compose.
* [eprendre/tingshu](https://github.com/eprendre/tingshu) - 一款可在线播放多个免费听书站点的安卓app
* [nordicsemi/Android-nRF-Toolbox](https://github.com/nordicsemi/Android-nRF-Toolbox) - The nRF Toolbox is a container app that stores your Nordic Semiconductor apps for Bluetooth Low Energy in one location.
* [Anthonyy232/Paperize](https://github.com/Anthonyy232/Paperize) - Paperize is a modern fully offline dynamic wallpaper changer application built for Android using Kotlin, Jetpack Compose, and Material 3
* [prof18/feed-flow](https://github.com/prof18/feed-flow) - FeedFlow is a minimalistic RSS Reader available on Android, iOS, macOS, Windows and Linux. Built with Kotlin Multiplatform, Jetpack Compose and SwiftUI.
* [sogonov/anubis](https://github.com/sogonov/anubis) - Android app manager with VPN integration. Manages groups of apps by freezing/unfreezing them based on VPN connection state.
* [DavidVentura/offline-translator](https://github.com/DavidVentura/offline-translator) - Use Firefox Translation Models for on-device translation on Android
* [Aryan-Raj3112/episteme](https://github.com/Aryan-Raj3112/episteme) - A multi-platform document and e-book reader.
* [GlassHaven/Haven](https://github.com/GlassHaven/Haven) - Free SSH, VNC, RDP & SFTP client for Android
* [Razeeman/Android-SimpleTimeTracker](https://github.com/Razeeman/Android-SimpleTimeTracker) - Simple app that tracks time.
* [T31n/Geto](https://github.com/T31n/Geto) - Apply device settings to your apps.
* [suqi8/OShin](https://github.com/suqi8/OShin) - 一个专为ColorOS系统设计的辅助模块
* [LegadoTeam/legado](https://github.com/LegadoTeam/legado) - Legado 3.0 Book Reader with powerful controls
* [cryptomator/android](https://github.com/cryptomator/android) - Cryptomator for Android
* [fankes/TSBattery](https://github.com/fankes/TSBattery) - A new way to save your battery avoid cancer apps hacker it.
* [RyensX/MediaBox](https://github.com/RyensX/MediaBox) - 全能媒体容器，插件化网罗天下媒体，畅快浏览视频、漫画和任何你想要的媒体数据。A universal media container, aggregating media through plugins to browse videos, comics and any media data you want.
* [you-apps/WallYou](https://github.com/you-apps/WallYou) - Privacy focused wallpaper app built with MD3
* [bggRGjQaUbCoE/c001apk](https://github.com/bggRGjQaUbCoE/c001apk) - fake coolapk *(archived)*
* [stream-rec/stream-rec](https://github.com/stream-rec/stream-rec) - Automatic streaming record tool. Live stream and bullet comments recorder. 虎牙/抖音/斗鱼/Twitch/PandaTV/微博直播，弹幕自动录制 *(archived)*
* [m-i-n-a-r/birday](https://github.com/m-i-n-a-r/birday) - 🎉 A beautiful Kotlin app to remember birthdays and events without having to open Facebook, set alarms or rely on Google Calendar
* [Block-Network/StatusBarLyric](https://github.com/Block-Network/StatusBarLyric) - [Xposed] Status Bar Lyric / 状态栏歌词 *(archived)*
* [commons-app/apps-android-commons](https://github.com/commons-app/apps-android-commons) - The Wikimedia Commons Android app allows users to upload pictures from their Android phone/tablet to Wikimedia Commons
* [mtotschnig/MyExpenses](https://github.com/mtotschnig/MyExpenses) - GPL licenced Android Expense Tracking App
* [mudkipme/MoeMemosAndroid](https://github.com/mudkipme/MoeMemosAndroid) - An app to help you capture thoughts and ideas
* [ycngmn/Nobook](https://github.com/ycngmn/Nobook) - Ad-free facebook lite for Android. *(archived)*
* [solkin/appteka-android](https://github.com/solkin/appteka-android) - 💊 Appteka is an alternative store for Android
* [grote/Transportr](https://github.com/grote/Transportr) - Free Public Transport Assistant without Ads or Tracking
* [nightscout/AndroidAPS](https://github.com/nightscout/AndroidAPS) - Opensource automated insulin delivery system (closed loop)
* [dominostars/playtranslate](https://github.com/dominostars/playtranslate) - Real-time screen translation app for Android for both language learners and casual gamers
* [shub39/Grit](https://github.com/shub39/Grit) - 🔨 A Simple todo list and habit tracker for Android
* [nikhilvishwakarma00/Velune](https://github.com/nikhilvishwakarma00/Velune) - A premium ad-free YouTube Music client for Android. Built with Kotlin & Jetpack Compose.
* [ldlywt/IdeaMemo](https://github.com/ldlywt/IdeaMemo) - A Beautiful Memo App written with Jetpack Compose. 开源Android闪念笔记App。
* [knighthat/Kreate](https://github.com/knighthat/Kreate) - A multilingual YouTube Music frontend for Android, prioritize performance
* [gujjwal00/avnc](https://github.com/gujjwal00/avnc) - VNC Client for Android
* [torlando-tech/columba](https://github.com/torlando-tech/columba) - Native Android messaging app using Bluetooth LE, TCP, or RNode (LoRa) over LXMF and Reticulum
* [touchlab/DroidconKotlin](https://github.com/touchlab/DroidconKotlin) - Kotlin Multiplatfom app for Droidcon Events
* [GuhDoy/TiebaTS](https://github.com/GuhDoy/TiebaTS) - 提供修改百度贴吧底栏等个性化功能。An Xposed module for Baidu Tieba with personalized functions. *(archived)*
* [JingMatrix/ChromeXt](https://github.com/JingMatrix/ChromeXt) - UserScript and DevTools supports for Chromium based and WebView based browsers
* [WirelessAlien/ZipXtract](https://github.com/WirelessAlien/ZipXtract) - A fully open source app to extract rar, zip, tar, bz2, gz, 7z, xz, jar and z etc (encrypted .zip & .7z supported)
* [d4rken-org/capod](https://github.com/d4rken-org/capod) - A companion app for AirPods on Android.
* [tejado/android-usb-gadget](https://github.com/tejado/android-usb-gadget) - Convert your Android phone to any USB device you like! USB Gadget Tool allows you to create and activate USB device roles, like a mouse or a keyboard. 🛠🛡📱
* [orgzly-revived/orgzly-android-revived](https://github.com/orgzly-revived/orgzly-android-revived) - Outliner for taking notes and managing to-do lists
* [binwiederhier/ntfy-android](https://github.com/binwiederhier/ntfy-android) - Android app for ntfy.sh
* [LyraVoid/FolkPatch](https://github.com/LyraVoid/FolkPatch) - Root access to the kernel can be achieved simply by patching the Boot partition for reflashing. This solution is based on a non-parallel extended branch of APatch, with a primary focus on UI/UX design
* [TonnyL/PaperPlane](https://github.com/TonnyL/PaperPlane) - 📚 PaperPlane - An Android reading app, including articles from Zhihu Daily, Guokr Handpick and Douban Moment.
* [xiaoyvyv/bangumi](https://github.com/xiaoyvyv/bangumi) - Bangumi for CMP - A full-featured unofficial compose-multiplatform application for the bangumi.tv
* [MRepoApp/MRepo](https://github.com/MRepoApp/MRepo) - A modules manager for Magisk, KernelSU and APatch *(archived)*
* [chr233/PureNGA](https://github.com/chr233/PureNGA) - NGA 去广告Xposed模块 支持 Lspatch
* [caydey/ffshare](https://github.com/caydey/ffshare) - An android app to compress image, video and audio files through ffmpeg before sharing them
* [jackdark425/aigroupapp](https://github.com/jackdark425/aigroupapp) - AI Group is a powerful mobile intelligent assistant application that integrates multiple large language models (LLMs) and AI services, providing you with a convenient intelligent interaction experience.
* [AllanWang/Frost-for-Facebook](https://github.com/AllanWang/Frost-for-Facebook) - An extensive and functional third party app for Facebook *(archived)*
* [demantz/RFAnalyzer](https://github.com/demantz/RFAnalyzer) - Analyze RF signals on Android with HackRF, RTL-SDR, Airspy (HF+) and HydraSDR
* [Tobi823/ffupdater](https://github.com/Tobi823/ffupdater) - FFUpdater: Updater for privacy friendly browser
* [gameyfin/gameyfin](https://github.com/gameyfin/gameyfin) - Manage your video games.
* [lukaspieper/Gcam-Services-Provider](https://github.com/lukaspieper/Gcam-Services-Provider) - App faking only the absolute necessary Apis to use Gcam without Play Services
* [rawnaldclark/Stash](https://github.com/rawnaldclark/Stash) - Your Spotify + YouTube Music library & daily mixes. Free and open source forever.
* [sosauce/Chocola](https://github.com/sosauce/Chocola) - 🍫 Chocola is a cute and powerful offline music player for Android!
* [kamgurgul/cpu-info](https://github.com/kamgurgul/cpu-info) - CPU Info is a multiplatform application which provides information about device hardware and software
* [Chooloo/koler](https://github.com/Chooloo/koler) - Just a phone app.
* [theothernt/AerialViews](https://github.com/theothernt/AerialViews) - A screensaver for Android TV devices including Google TV, Nvidia Shield, and Fire TV. Inspired by Apple TV's video screensaver.
* [estkme-group/openeuicc](https://github.com/estkme-group/openeuicc) - Mirror of OpenEUICC, a fully open-source LPA implementation for Android
* [Kin69/EasyNotes](https://github.com/Kin69/EasyNotes) - EasyNotes: Jetpack Compose MVVM for seamless note-taking. Effortless creation, editing, and organization.
* [acidicoala/Koalageddon2](https://github.com/acidicoala/Koalageddon2) - Legit DLC Unlocker for Steamworks, Epic Online Services, and Ubisoft Connect *(archived)*
* [vhqtvn/VHEditor-Android](https://github.com/vhqtvn/VHEditor-Android) - Run Code-server on Android
* [komikku-app/anikku](https://github.com/komikku-app/anikku) - Free and open source anime watcher for Android
* [karasevm/PrivateDNSAndroid](https://github.com/karasevm/PrivateDNSAndroid) - Quick settings tile to switch active private DNS server
* [trynoice/android-app](https://github.com/trynoice/android-app) - The Android app for Noice.
* [GrapheneOS/PdfViewer](https://github.com/GrapheneOS/PdfViewer) - Simple Android PDF viewer based on pdf.js and content providers. The app doesn't require any permissions. The PDF stream is fed into the sandboxed WebView without giving it access to content or files. CSP is used to enforce that the JavaScript and styling properties within the WebView are entirely static.
* [shub39/Rush](https://github.com/shub39/Rush) - ✨ App to search, save and share lyrics like spotify!
* [afollestad/photo-affix](https://github.com/afollestad/photo-affix) - 📷 Stitch your photos together vertically or horizontally easily! *(archived)*
* [Dimowner/AudioRecorder](https://github.com/Dimowner/AudioRecorder) - Audio Recording Android application
* [Arturo254/OpenTune](https://github.com/Arturo254/OpenTune) - Un cliente de YouTube Music con Material Design 3, para Android
* [Dr-TSNG/Hide-My-Applist](https://github.com/Dr-TSNG/Hide-My-Applist) - An Xposed module to intercept applist detections
* [Dr-TSNG/TwiFucker](https://github.com/Dr-TSNG/TwiFucker) - Yet Another Adkiller for Twitter

## Graphics and Media

### Game Development

* [yairm210/Unciv](https://github.com/yairm210/Unciv) - Open-source Android/Desktop remake of Civ V
* [utkarshdalal/GameNative](https://github.com/utkarshdalal/GameNative) - Native PC gaming with Steam, Epic, GOG and Amazon integrations on Android
* [AlmasB/FXGL](https://github.com/AlmasB/FXGL) - Java / JavaFX / Kotlin Game Library (Engine)
* [Swordfish90/Lemuroid](https://github.com/Swordfish90/Lemuroid) - All in one emulator on Android!
* [korlibs/korge](https://github.com/korlibs/korge) - Korge is a Multiplatform Game Engine written in Kotlin for JVM, Web, Android and iOS.
* [CCBlueX/LiquidBounce](https://github.com/CCBlueX/LiquidBounce) - A free Minecraft hacked client (utility mod) for Fabric
* [git-goods/gitanimals](https://github.com/git-goods/gitanimals) - 🐣 깃허브 활동으로 펫을 키우세요 / Have pet in your github
* [rafaelvcaetano/melonDS-android](https://github.com/rafaelvcaetano/melonDS-android) - Android port of melonDS
* [libktx/ktx](https://github.com/libktx/ktx) - Kotlin extensions for the libGDX game framework
* [Skytils/SkytilsMod](https://github.com/Skytils/SkytilsMod) - Skytils is a Hypixel Skyblock mod! Be careful, malicious copies are distributed across GitHub. Confirm on discord.gg/skytils (807302538558308352)
* [RPCSX/rpcsx-ui-android](https://github.com/RPCSX/rpcsx-ui-android)
* [Bixilon/Minosoft](https://github.com/Bixilon/Minosoft) - An open source Minecraft reimplementation written from scratch. Mirror of https://gitlab.bixilon.de/bixilon/minosoft
* [RPCS3-Android/rpcs3-android](https://github.com/RPCS3-Android/rpcs3-android) - *(archived)*

### Image and Video

* [zetbaitsu/Compressor](https://github.com/zetbaitsu/Compressor) - An android image compression library.
* [burhanrashid52/PhotoEditor](https://github.com/burhanrashid52/PhotoEditor) - A Photo Editor library with simple, easy support for image editing using paints,text,filters,emoji and Sticker like stories.
* [pedroSG94/RootEncoder](https://github.com/pedroSG94/RootEncoder) - RootEncoder for Android (rtmp-rtsp-stream-client-java) is a stream encoder to push video/audio to media servers using protocols RTMP, RTSP, SRT and UDP with all code written in Java/Kotlin
* [brianwernick/ExoMedia](https://github.com/brianwernick/ExoMedia) - An Android ExoPlayer wrapper to simplify Audio and Video implementations
* [sumimakito/AwesomeQRCode](https://github.com/sumimakito/AwesomeQRCode) - An awesome QR code generator for Android.
* [yausername/youtubedl-android](https://github.com/yausername/youtubedl-android) - youtube-dl for android
* [numandev1/react-native-compressor](https://github.com/numandev1/react-native-compressor) - 🗜️Compress Image, Video, and Audio same like Whatsapp 🚀✨

## Security

### Cryptography

* [bitwarden/android](https://github.com/bitwarden/android) - Bitwarden mobile apps (Password Manager and Authenticator) for Android.
* [Kunzisoft/KeePassDX](https://github.com/Kunzisoft/KeePassDX) - Lightweight vault and password manager for Android, KeePassDX allows editing encrypted data in a single file in KeePass format and fill in the forms in a secure way.
* [oblador/react-native-keychain](https://github.com/oblador/react-native-keychain) - :key: Keychain Access for React Native
* [AChep/keyguard-app](https://github.com/AChep/keyguard-app) - A password manager that supports Bitwarden platform and KeePass (KDBX) files. It autofills your logins, supports passkeys, works offline, and runs a Watchtower that finds leaked and reused passwords and other issues.
* [Leon406/ToolsFx](https://github.com/Leon406/ToolsFx) - 跨平台密码学工具箱。包含编解码，编码转换，加解密， 哈希，MAC，签名，大数运算，压缩，二维码功能，CTF等功能。

### Security Tools

* [simondankelmann/Bluetooth-LE-Spam](https://github.com/simondankelmann/Bluetooth-LE-Spam)
* [allenymt/PrivacySentry](https://github.com/allenymt/PrivacySentry) - Android隐私合规整改检测工具，注解+Asm修改字节码的检测方案
* [oss-review-toolkit/ort](https://github.com/oss-review-toolkit/ort) - A suite of tools to automate software compliance checks.
* [doyensec/inql](https://github.com/doyensec/inql) - InQL is a robust, open-source Burp Suite extension for advanced GraphQL testing, offering intuitive vulnerability detection, customizable scans, and seamless Burp integration.
* [PortSwigger/turbo-intruder](https://github.com/PortSwigger/turbo-intruder) - Turbo Intruder is a Burp Suite extension for sending large numbers of HTTP requests and analyzing the results.
* [bytedance/appshark](https://github.com/bytedance/appshark) - Appshark is a static taint analysis platform to scan vulnerabilities in an Android app.
* [BLE-Research-Group/MetaRadar](https://github.com/BLE-Research-Group/MetaRadar) - A tool for BLE environment monitoring. Find and track Bluetooth devices around, create custom filters, get notified when the BLE fingerprint you are looking for is around.
* [six2dez/burp-ai-agent](https://github.com/six2dez/burp-ai-agent) - Burp Suite extension that adds built-in MCP tooling, AI-assisted analysis, privacy controls, passive and active scanning and more
* [reveny/Android-Native-Root-Detector](https://github.com/reveny/Android-Native-Root-Detector) - A tool to detect root on android
* [beakthoven/TrickyStoreOSS](https://github.com/beakthoven/TrickyStoreOSS) - Open source alternative to proprietary Tricky Store module
* [xihan123/SignHook](https://github.com/xihan123/SignHook) - 这是一个简单的签名校验通杀模块
* [littleWhiteDuck/SimpleHook](https://github.com/littleWhiteDuck/SimpleHook) - SimpleHook
* [BuSung-dev/Root-My-Galaxy](https://github.com/BuSung-dev/Root-My-Galaxy) - KSU installer for supported Samsung Galaxy firmware with CVE-2026-43499
* [soupslurpr/AppVerifier](https://github.com/soupslurpr/AppVerifier) - Verify apps easily.
* [JunioJsv/mtk-easy-su](https://github.com/JunioJsv/mtk-easy-su) - Get bootless root access with few clicks.
* [PortSwigger/mcp-server](https://github.com/PortSwigger/mcp-server) - MCP Server for Burp
* [bszapp/android-wifi-pojie](https://github.com/bszapp/android-wifi-pojie) - Android使用密码本暴力破解wifi密码工具
* [liujingxing/XmlClassGuard](https://github.com/liujingxing/XmlClassGuard) - 一个可混淆4大组件，自定义View等任意类的插件，上架Google Play的利器
* [Exodus-Privacy/exodus-android-app](https://github.com/Exodus-Privacy/exodus-android-app) - εxodus Android application
* [Dr-TSNG/ApplistDetector](https://github.com/Dr-TSNG/ApplistDetector) - A library to detect suspicious apps like Magisk

### Reverse Engineering

* [ReVanced/revanced-patches-template](https://github.com/ReVanced/revanced-patches-template) - 👋🧩Template repository for ReVanced Patches
* [ReVanced/revanced-patcher](https://github.com/ReVanced/revanced-patcher) - 💉 ReVanced Patcher used to patch Android applications
* [ingokegel/jclasslib](https://github.com/ingokegel/jclasslib) - jclasslib bytecode editor is a tool that visualizes all aspects of compiled Java class files and the contained bytecode.
* [HighCapable/YukiHookAPI](https://github.com/HighCapable/YukiHookAPI) - ⛱️ An efficient Hook API and Xposed Module solution built in Kotlin.
* [Gh0u1L5/WechatMagician](https://github.com/Gh0u1L5/WechatMagician) - WechatMagician is a Xposed module written in Kotlin, that allows you to completely control your Wechat.
* [Gh0u1L5/WechatSpellbook](https://github.com/Gh0u1L5/WechatSpellbook) - Wechat Spellbook 是一个使用Kotlin编写的开源微信插件框架，底层需要 Xposed 或 VirtualXposed 等Hooking框架的支持，而顶层可以轻松对接Java、Kotlin、Scala等JVM系语言。让程序员能够在几分钟内编写出简单的微信插件，随意揉捏微信的内部逻辑。
* [theapache64/stackzy](https://github.com/theapache64/stackzy) - 💻 A cross-platform desktop application to identify libraries used inside an android application ⚡
* [LuckyPray/DexKit](https://github.com/LuckyPray/DexKit) - An easy-to-use, high-performance dex deobfuscation library.

## Concurrency and Performance

### Concurrency and Parallelism

* [Kotlin/kotlinx.coroutines](https://github.com/Kotlin/kotlinx.coroutines) - Library support for Kotlin coroutines
* [ReactiveX/RxKotlin](https://github.com/ReactiveX/RxKotlin) - RxJava bindings for Kotlin
* [cashapp/molecule](https://github.com/cashapp/molecule) - Build a StateFlow stream using Jetpack Compose
* [rickclephas/KMP-NativeCoroutines](https://github.com/rickclephas/KMP-NativeCoroutines) - Library to use Kotlin Coroutines from Swift code in KMP apps
* [badoo/Reaktive](https://github.com/badoo/Reaktive) - Kotlin multi-platform implementation of Reactive Extensions
* [Kotlin/kotlinx-atomicfu](https://github.com/Kotlin/kotlinx-atomicfu) - The idiomatic way to use atomic operations in Kotlin

## Testing and Quality

### Testing

* [mobile-dev-inc/Maestro](https://github.com/mobile-dev-inc/Maestro) - Painless E2E Automation for Mobile and Web
* [mockk/mockk](https://github.com/mockk/mockk) - mocking library for Kotlin
* [kotest/kotest](https://github.com/kotest/kotest) - Powerful, elegant and flexible test framework for Kotlin with assertions, property testing and data driven tests.
* [mockito/mockito-kotlin](https://github.com/mockito/mockito-kotlin) - Using Mockito with Kotlin
* [cashapp/turbine](https://github.com/cashapp/turbine) - A testing library for kotlinx.coroutines Flow
* [cashapp/paparazzi](https://github.com/cashapp/paparazzi) - Render your Android screens without a physical device or emulator
* [spekframework/spek](https://github.com/spekframework/spek) - A specification framework for Kotlin
* [KasperskyLab/Kaspresso](https://github.com/KasperskyLab/Kaspresso) - Android UI test framework
* [AdevintaSpain/Barista](https://github.com/AdevintaSpain/Barista) - :coffee: The one who serves a great Espresso
* [Kotlin/kotlinx-kover](https://github.com/Kotlin/kotlinx-kover)
* [pedrovgs/Shot](https://github.com/pedrovgs/Shot) - Screenshot testing library for Android
* [adobe/S3Mock](https://github.com/adobe/S3Mock) - A mock implementation of the AWS S3 API startable as Docker image, TestContainer, JUnit Jupiter extension or TestNG listener
* [pact-foundation/pact-jvm](https://github.com/pact-foundation/pact-jvm) - JVM version of Pact. Enables consumer driven contract testing, providing a mock service and DSL for the consumer project, and interaction playback and verification for the service provider project.
* [agoda-com/Kakao](https://github.com/agoda-com/Kakao) - This repo is no longer supported. Please visit a https://github.com/KakaoCup/Kakao *(archived)*
* [takahirom/roborazzi](https://github.com/takahirom/roborazzi) - Make JVM Android integration test visible 🤖📸

## Utilities

### Logging and Configuration

* [JakeWharton/timber](https://github.com/JakeWharton/timber) - A logger with a small, extensible API which provides utility on top of Android's normal Log class.
* [oshai/kotlin-logging](https://github.com/oshai/kotlin-logging) - Lightweight Multiplatform logging framework for Kotlin. A convenient and performant logging facade.
* [russhwolf/multiplatform-settings](https://github.com/russhwolf/multiplatform-settings) - A Kotlin Multiplatform library for saving simple key-value data
* [ihsanbal/LoggingInterceptor](https://github.com/ihsanbal/LoggingInterceptor) - An OkHttp interceptor which has pretty logger for request and response. +Mock support
* [sksamuel/hoplite](https://github.com/sksamuel/hoplite) - A boilerplate-free Kotlin config library for loading configuration files as data classes
* [touchlab/Kermit](https://github.com/touchlab/Kermit) - Kermit by Touchlab is a Kotlin Multiplatform centralized logging utility.
* [AAkira/Napier](https://github.com/AAkira/Napier) - Logging library for Kotlin Multiplatform

### Files and Operating System

* [lysine-dev/okio](https://github.com/lysine-dev/okio) - A modern I/O library for Android, Java, and Kotlin Multiplatform.
* [Kotlin/kotlinx-io](https://github.com/Kotlin/kotlinx-io) - Kotlin multiplatform I/O library
* [vinceglb/FileKit](https://github.com/vinceglb/FileKit) - Pick and save Files, Medias and Folder for Kotlin Multiplatform / KMP and Compose Multiplatform / CMP
* [javakam/FileOperator](https://github.com/javakam/FileOperator) - 🔥 涵盖了Android系统文件的创建/删除/复制/打开文件(目录)、获取文件(目录)大小、获取常用目录、获取文件名称及后缀、获取MimeType以及MediaStore和SAF的相关操作等常用功能，并且也处理了获取文件Uri/Path的兼容问题、图片压缩和文件选择等功能。
* [magnusja/libaums](https://github.com/magnusja/libaums) - Open source library to access USB Mass Storage devices on Android without rooting your device
* [google/modernstorage](https://github.com/google/modernstorage) - ModernStorage is a group of libraries that provide an abstraction layer over storage on Android to simplify its interactions *(archived)*

### Automation and Scripting

* [mamoe/mirai](https://github.com/mamoe/mirai) - 高效率 QQ 机器人支持库
* [gallonyin/worktool](https://github.com/gallonyin/worktool) - 一款安全稳定的Android无障碍服务工具，支持控制企微/微信来运行的无人值守群管理企业微信机器人
* [kscripting/kscript](https://github.com/kscripting/kscript) - Scripting enhancements for Kotlin
* [AndroidCoderPeng/DailyTask](https://github.com/AndroidCoderPeng/DailyTask) - 自动打卡（无人值守方案，非目标应用数据修改方案！）
* [RookieTree/DaMaiHelper](https://github.com/RookieTree/DaMaiHelper) - 大麦抢票辅助
* [project-mirai/mirai-api-http](https://github.com/project-mirai/mirai-api-http) - Mirai HTTP API (console) plugin
* [LuckyPray/XAutoDaily](https://github.com/LuckyPray/XAutoDaily) - 一个基于QQ的全自动签到模块
* [ChaoMixian/vFlow](https://github.com/ChaoMixian/vFlow) - vFlow 是一款为 Android 平台设计的、强大且高度可扩展的自动化工具。它允许你通过图形化界面，将一系列“动作模块”自由组合成强大的“工作流”，从而自动完成各种日常的、重复性的屏幕操作任务。
* [mamoe/mirai-console](https://github.com/mamoe/mirai-console) - mirai 的高效率 QQ 机器人控制台 *(archived)*
* [xjunz/AutoTask](https://github.com/xjunz/AutoTask) - An automation assistant app supporting both Shizuku and AccessibilityService.
* [Skykai521/DingDongHelper](https://github.com/Skykai521/DingDongHelper) - 叮咚买菜抢菜插件

### General Purpose Libraries

* [Tamsiree/RxTool](https://github.com/Tamsiree/RxTool) - Android开发人员不得不收集的工具类集合 | 支付宝支付 | 微信支付（统一下单） | 微信分享 | Zip4j压缩（支持分卷压缩与加密） | 一键集成UCrop选择圆形头像 | 一键集成二维码和条形码的扫描与生成 | 常用Dialog | WebView的封装可播放视频 | 仿斗鱼滑动验证码 | Toast封装 | 震动 | GPS | Location定位 | 图片缩放 | Exif 图片添加地理位置信息（经纬度） | 蛛网等级 | 颜色选择器 | ArcGis | VTPK | 编译运行一下说不定会找到惊喜
* [InsertKoinIO/koin](https://github.com/InsertKoinIO/koin) - Koin - a pragmatic lightweight dependency injection framework for Kotlin & Kotlin Multiplatform
* [arrow-kt/arrow](https://github.com/arrow-kt/arrow) - The perfect companion for your Kotlin journey - Inspired by functional, data-oriented and concurrent programming
* [kosi-libs/Kodein](https://github.com/kosi-libs/Kodein) - Painless Kotlin Dependency Injection
* [LouisCAD/Splitties](https://github.com/LouisCAD/Splitties) - A collection of hand-crafted extensions for your Kotlin projects.
* [evant/kotlin-inject](https://github.com/evant/kotlin-inject) - Dependency injection lib for kotlin
* [Kotlin/kotlinx.collections.immutable](https://github.com/Kotlin/kotlinx.collections.immutable) - Immutable persistent collections for Kotlin
* [ZacSweers/metro](https://github.com/ZacSweers/metro) - A multiplatform, compile-time dependency injection framework for Kotlin
* [michaelbull/kotlin-result](https://github.com/michaelbull/kotlin-result) - A multiplatform Result monad for modelling success or failure operations.

## Systems and Hardware

### Operating Systems and Kernels

* [topjohnwu/Magisk](https://github.com/topjohnwu/Magisk) - The Magic Mask for Android
* [tiann/KernelSU](https://github.com/tiann/KernelSU) - A Kernel based root solution for Android
* [JingMatrix/Vector](https://github.com/JingMatrix/Vector) - Modern Xposed Framework
* [bmax121/APatch](https://github.com/bmax121/APatch) - The patching of Android kernel and Android system
* [SukiSU-Ultra/SukiSU-Ultra](https://github.com/SukiSU-Ultra/SukiSU-Ultra) - Kernel-based Android Root Solution & KPM
* [KernelSU-Next/KernelSU-Next](https://github.com/KernelSU-Next/KernelSU-Next) - An advanced Kernel based root solution for Android
* [Cateners/tiny_container](https://github.com/Cateners/tiny_container) - Click-to-run debian 13 with desktop environment on android!
* [orailnoor/DroidDesk](https://github.com/orailnoor/DroidDesk) - DroidDesk turns your Android phone into a real Linux desktop using Termux, Termux X11, TUR, and Proot. Run VS Code, Firefox, LibreOffice, Blender, and more with X11 or VNC support for monitor setup.
* [ExTV/Podroid](https://github.com/ExTV/Podroid) - A rootless Android app that boots Alpine Linux: run containers (Podman/Docker/LXC) and GUI desktop apps.
* [ravindu644/Droidspaces-OSS](https://github.com/ravindu644/Droidspaces-OSS) - A lightweight, LXC-like container runtime for Android and Linux. Run full Linux distributions natively with zero performance penalty
* [ReSukiSU/ReSukiSU](https://github.com/ReSukiSU/ReSukiSU) - A KernelSU based root solution for Android

## Other

* [JetBrains/compose-multiplatform](https://github.com/JetBrains/compose-multiplatform) - Compose Multiplatform, a modern UI framework for Kotlin that makes building performant and beautiful user interfaces easy and enjoyable.
* [iamgio/quarkdown](https://github.com/iamgio/quarkdown) - 🪐 Markdown with superpowers: from ideas to papers, presentations, websites, books, and knowledge bases.
* [ethereum-lists/chains](https://github.com/ethereum-lists/chains) - provides metadata for chains
* [detekt/detekt](https://github.com/detekt/detekt) - Static code analysis for Kotlin
* [sourcerer-io/sourcerer-app](https://github.com/sourcerer-io/sourcerer-app) - 🦄 Sourcerer app makes a visual profile from your GitHub and git repositories.
* [react-native-async-storage/async-storage](https://github.com/react-native-async-storage/async-storage) - An asynchronous, persistent, key-value storage system for React Native.
* [didi/booster](https://github.com/didi/booster) - 🚀Optimizer for mobile applications
* [corda/corda](https://github.com/corda/corda) - Corda is an open source blockchain project, designed for business from the start. Only Corda allows you to build interoperable blockchain networks that transact in strict privacy. Corda's smart contract technology allows businesses to transact directly, with value.
* [apollographql/apollo-kotlin](https://github.com/apollographql/apollo-kotlin) - :rocket: A strongly-typed, caching GraphQL client for the JVM, Android, and Kotlin multiplatform.
* [edvin/tornadofx](https://github.com/edvin/tornadofx) - Lightweight JavaFX Framework for Kotlin *(archived)*
* [NuvioMedia/NuvioMobile](https://github.com/NuvioMedia/NuvioMobile) - Official Nuvio Mobile Repository
* [MobileNativeFoundation/Store](https://github.com/MobileNativeFoundation/Store) - A library for reading and writing data that lives in network, disk, and memory.
* [Netflix/dgs-framework](https://github.com/Netflix/dgs-framework) - GraphQL for Java with Spring Boot made easy.
* [svga/SVGAPlayer-Android](https://github.com/svga/SVGAPlayer-Android) - Similar to Lottie. Render After Effects / Animate CC (Flash) animations natively on Android and iOS, Web. 使用 SVGAPlayer 在 Android、iOS、Web中播放 After Effects / Animate CC (Flash) 动画。 *(archived)*
* [ajalt/clikt](https://github.com/ajalt/clikt) - Multiplatform command line interface parsing for Kotlin
* [Kotlin/kotlinx-datetime](https://github.com/Kotlin/kotlinx-datetime) - KotlinX multiplatform date/time library
* [JetpackDuba/Gitnuro](https://github.com/JetpackDuba/Gitnuro) - A FOSS Git multiplatform client for newbies and pros
* [JakeWharton/mosaic](https://github.com/JakeWharton/mosaic) - Build terminal UI in Kotlin using Jetpack Compose
* [TencentBlueKing/bk-ci](https://github.com/TencentBlueKing/bk-ci) - 蓝鲸持续集成平台(蓝盾)
* [googlemaps-samples/android-samples](https://github.com/googlemaps-samples/android-samples) - Samples demonstrating how to use Maps SDK for Android
* [JakeWharton/diffuse](https://github.com/JakeWharton/diffuse) - Diffuse is a tool for diffing APKs, AABs, AARs, and JARs
* [JetBrains/skiko](https://github.com/JetBrains/skiko) - Kotlin Multiplatform bindings to Skia
* [lavalink-devs/Lavalink](https://github.com/lavalink-devs/Lavalink) - Standalone audio sending node based on Lavaplayer.
* [intellij-elixir/intellij-elixir](https://github.com/intellij-elixir/intellij-elixir) - Elixir plugin for JetBrain's IntelliJ Platform (including Rubymine)
* [dzikoysk/reposilite](https://github.com/dzikoysk/reposilite) - Lightweight and easy-to-use repository management software dedicated for the Maven-based artifacts in the JVM ecosystem 📦
* [dindin0497/HearIt](https://github.com/dindin0497/HearIt)
* [ExpediaGroup/graphql-kotlin](https://github.com/ExpediaGroup/graphql-kotlin) - Libraries for running GraphQL in Kotlin
* [sanogueralorenzo/sanogueralorenzo.github.io](https://github.com/sanogueralorenzo/sanogueralorenzo.github.io)
* [JetBrains/lets-plot](https://github.com/JetBrains/lets-plot) - Multiplatform plotting library based on the Grammar of Graphics
* [Kotlin/kotlinx.html](https://github.com/Kotlin/kotlinx.html) - Kotlin DSL for HTML
* [vanniktech/gradle-maven-publish-plugin](https://github.com/vanniktech/gradle-maven-publish-plugin) - A Gradle plugin that publishes your Android and Kotlin libraries, including sources and javadoc, to Maven Central or any other Nexus instance.
* [GitLiveApp/firebase-kotlin-sdk](https://github.com/GitLiveApp/firebase-kotlin-sdk) - A Kotlin-first SDK for Firebase
* [orbit/orbit](https://github.com/orbit/orbit) - Orbit - Virtual actor framework for building distributed systems
* [Splitties/refreshVersions](https://github.com/Splitties/refreshVersions) - Life is too short to google for dependencies and versions
* [ReVanced/revanced-cli](https://github.com/ReVanced/revanced-cli) - 💻 Command-line application to use ReVanced
* [JetBrains/kotlin-wrappers](https://github.com/JetBrains/kotlin-wrappers) - Kotlin wrappers for popular JavaScript libraries
* [nekocode/create-android-kotlin-app](https://github.com/nekocode/create-android-kotlin-app) - Create kotlin android project with one line of command.
* [Kotlin/kotlindl](https://github.com/Kotlin/kotlindl) - High-level Deep Learning Framework written in Kotlin and inspired by Keras
* [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler) - 每天自动爬取测活（google ping）公开节点。 🚀 免费节点,🚀免费订阅 (若不进行二次开发,请不要fork)
* [NuvioMedia/NuvioDesktop](https://github.com/NuvioMedia/NuvioDesktop) - ⚠️ Alpha Software - Testers Only
* [instacart/truetime-android](https://github.com/instacart/truetime-android) - Android NTP time library. Get the true current time impervious to device clock time changes
* [MLReef/mlreef](https://github.com/MLReef/mlreef) - The collaboration workspace for Machine Learning
* [EspoirX/StarrySky](https://github.com/EspoirX/StarrySky) - 🔥A Powerful and Streamline MusicLibrary(一个丰富的音乐播放封装库,支持多种音频格式,完美解决你的问题。)
* [Numbersf/Action-Build](https://github.com/Numbersf/Action-Build) - Build SukiSU-Ultra/KernelSU/KernelSU-Next/ReSukiSU Kernels For All OnePlus QCOM & MTK Devices (GKI2.0), Supporting SUSFS, KPM, ZRAM and more feats.
* [Chuloo/mural](https://github.com/Chuloo/mural) - The language app you eventually delete. A native iPhone companion for learning through conversation.
* [sceneview/sceneview](https://github.com/sceneview/sceneview) - AI-first 3D & AR SDK for Android (Jetpack Compose + Filament), Apple (SwiftUI + RealityKit) and the web. Opens glTF/GLB, 3MF, STL, OBJ and PLY on Android and USDZ on Apple, at real size in AR. An assistant reads llms.txt and writes code that compiles first try; also an MCP server and a ChatGPT/Codex plugin.
* [grpc/grpc-kotlin](https://github.com/grpc/grpc-kotlin) - Kotlin gRPC implementation. HTTP/2 based RPC
* [kushagrasinghx/BitChord](https://github.com/kushagrasinghx/BitChord) - BitChord - A modern YouTube music client with clean aesthetics inspired from Apple Music
* [JetBrains/projector-server](https://github.com/JetBrains/projector-server) - Server-side library for running Swing applications remotely *(archived)*
* [ajalt/mordant](https://github.com/ajalt/mordant) - Multiplatform text styling for Kotlin command-line applications
* [EchoMusicApp/Echo-Music](https://github.com/EchoMusicApp/Echo-Music) - An YouTube Music Client
* [Kotlin/kotlin-jupyter](https://github.com/Kotlin/kotlin-jupyter) - Kotlin kernel for Jupyter/IPython
* [termux/termux-gui](https://github.com/termux/termux-gui) - A plugin for Termux to use native Android GUI components from CLI applications.
* [jenly1314/MLKit](https://github.com/jenly1314/MLKit) - 🌝 MLKit是一个强大易用的工具包。通过ML Kit您可以很轻松的实现文字识别、条码识别、图像标记、人脸检测、对象检测等功能。
* [JetBrains/kotless](https://github.com/JetBrains/kotless) - Kotlin Serverless Framework
* [platonai/Browser4](https://github.com/platonai/Browser4) - Browser4 — an AI-native browser engine for autonomous agents, intelligent extraction, and large-scale web automation.
* [hoo-dles/morphe-patches](https://github.com/hoo-dles/morphe-patches) - 🍃 Patches for Morphe
* [HuangZhuoRui/LocationSpoofer](https://github.com/HuangZhuoRui/LocationSpoofer) - 虚拟定位软件，主要是定位，集成了 WiFi、蓝牙、基站等方案，主要有定点模拟和路线模拟。非全局方案，需要单独 hook 对应的软件(因为不想单独去适配各大手机厂商的系统)，
* [mikepenz/multiplatform-markdown-renderer](https://github.com/mikepenz/multiplatform-markdown-renderer) - Markdown renderer for Kotlin Multiplatform Projects (Android, iOS, Desktop), using Compose.
* [HmnDev-Tech/shevery](https://github.com/HmnDev-Tech/shevery) - Shevery - Modernized Android manager with Jetpack Compose, Material 3, and compatibility enhancements.
* [Kotlin/kotlinx-rpc](https://github.com/Kotlin/kotlinx-rpc) - Add asynchronous RPC services to your multiplatform applications.
* [Kotlin/dataframe](https://github.com/Kotlin/dataframe) - Kotlin DataFrame: typesafe in-memory structured data processing for JVM
* [ssalggnikool/Navic](https://github.com/ssalggnikool/Navic) - Subsonic music streaming app for Android and iOS
* [software-mansion/enriched-markdown](https://github.com/software-mansion/enriched-markdown) - Multiplatform Markdown-Based Rich Text Solution
* [Replica0110/Lyrico](https://github.com/Replica0110/Lyrico) - 一个开源的 Android 音乐标签编辑器，支持标签搜索与编辑，并提供逐字歌词支持。灵感来源于 LDDC 和音乐标签。
* [thejaustin/ShizukuPlus](https://github.com/thejaustin/ShizukuPlus) - An enhanced fork of Shizuku — adds Root/ADB/Dhizuku unification, a Plus API suite, and OneUI/Android 16+ compatibility fixes, while staying fully compatible with existing Shizuku apps.
* [bxx2004/FUNGA](https://github.com/bxx2004/FUNGA) - This is a database project.
* [Monica-Pass/Monica](https://github.com/Monica-Pass/Monica) - Monica Pass，Password Management, 2FA Generator
* [eltavine/Duck-Detector-Refactoring](https://github.com/eltavine/Duck-Detector-Refactoring) - Android environment integrity inspection tool for root, hook, bootloader, SELinux, virtualization, and attestation signals
