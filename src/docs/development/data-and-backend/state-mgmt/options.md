---
title: List of state management approaches
title: 状态 (State) 管理参考
prev:
  title: Simple app state management
  title: 简单的共享 (app) 状态管理
  path: /docs/development/data-and-backend/state-mgmt/simple
---

State management is a complex topic. If you feel that some of your questions
haven't been answered, or that the approach described on these pages
is not viable for your use cases, you are probably right.

状态管理是一个复杂的议题。你可能遇到此教程暂未解答的问题，或者与此教程结果不符的现象。

Learn more at the following links, many of which have been contributed
by the Flutter community:

通过下面的链接了解更多的信息，其中有很多信息都是由 Flutter 社区提供。

## General overview

## 概览

* [Build reactive mobile apps with Flutter](https://www.youtube.com/watch?v=RS36gBEp8OI&feature=youtu.be),
  a video from Google I/O 2018, and an
  [accompanying article]({{site.flutter-medium}}/build-reactive-mobile-apps-in-flutter-companion-article-13950959e381)

  [使用 Flutter 构建响应式移动应用](https://www.bilibili.com/video/av55808989/)，视频来自 Google I/O 2018，以及一篇 [随附文章]({{site.flutter-medium}}/build-reactive-mobile-apps-in-flutter-companion-article-13950959e381)

* [Flutter Architecture Samples](http://fluttersamples.com/), by Brian Egan

  由Brian Egan 提供的 [Flutter 架构示例](http://fluttersamples.com/)

## setState

* [Adding interactivity to your Flutter app](/docs/development/ui/interactive),
  a Flutter tutorial

  [给你的 Flutter app 添加交互](/docs/development/ui/interactive)，Flutter 教程

* [Basic state management in Google Flutter]({{site.medium}}/@agungsurya/basic-state-management-in-google-flutter-6ee73608f96d),
  by Agung Surya

  由 Agung Surya 提供的 [Google Flutter 中的基本状态管理]({{site.medium}}/@agungsurya/basic-state-management-in-google-flutter-6ee73608f96d)

## InheritedWidget &amp; InheritedModel 

* [InheritedWidget docs](https://api.flutter.dev/flutter/widgets/InheritedWidget-class.html)

  [InheritedWidget 文档](https://api.flutter.dev/flutter/widgets/InheritedWidget-class.html)

* [Managing Flutter Application State With InheritedWidgets]({{site.flutter-medium}}/managing-flutter-application-state-with-inheritedwidgets-1140452befe1),
  by Hans Muller

  由 Hans Muller 提供的 [使用 InheritedWidgets 管理 Flutter 应用状态]({{site.flutter-medium}}/managing-flutter-application-state-with-inheritedwidgets-1140452befe1)

* [Inheriting Widgets](https://medium.com/@mehmetf_71205/inheriting-widgets-b7ac56dbbeb1),
  by Mehmet Fidanboylu

  由 Mehmet Fidanboylu 提供的 [Inheriting Widgets](https://medium.com/@mehmetf_71205/inheriting-widgets-b7ac56dbbeb1)

* [Using Flutter Inherited Widgets
  Effectively](https://ericwindmill.com/articles/inherited_widget/),
  by Eric Windmill

  由 Eric Windmill 提供的 [有效的使用 Flutter Inherited Widgets](https://ericwindmill.com/posts/using-flutter-inherited-widgets-effectively/)

* [Widget - State - Context -
  InheritedWidget](https://www.didierboelens.com/2018/06/widget---state---context---inheritedwidget/),
  by Didier Bolelens

  由 Didier Bolelens 提供的 [Widget - State - Context - InheritedWidget](https://www.didierboelens.com/2018/06/widget---state---context---inheritedwidget/)

## Provider &amp; Scoped Model

* [Provider package]({{site.pub-pkg}}/provider)

* [Scoped Model package]({{site.pub-pkg}}/scoped_model)

* [Simple State Management]({{site.url}}/docs/development/data-and-backend/state-mgmt/simple),
  the previous page in this section

  本节的上一页，[简单的状态管理]({{site.url}}/docs/development/data-and-backend/state-mgmt/simple)

* [You might not need Redux: The Flutter edition](https://proandroiddev.com/you-might-not-need-redux-the-flutter-edition-9c11eba006d7), by Ryan Edge

  由 Ryan Edge 提供的 [你可能不需要 Redux：Flutter 版](https://proandroiddev.com/you-might-not-need-redux-the-flutter-edition-9c11eba006d7)

* [Managing state with the scoped model pattern in Dart's Flutter
  framework](https://www.youtube.com/watch?v=-MCeWP3rgI0),
  a video by Tensor Programming

  由 Tensor Programming 提供的视频 [在基于 Dart 的 Flutter 框架中使用 Scoped Model 模式管理状态](https://www.youtube.com/watch?v=-MCeWP3rgI0)

* [Flutter: Inherited Widget and Scoped Model Explained,
  part 1](https://www.youtube.com/watch?v=j-27MZwRbFw),
  a video by MTechViral

  由 MTechViral 提供的视频 [Flutter：Inherited Widget 和 Scoped Model 详解，第一部分](https://www.youtube.com/watch?v=j-27MZwRbFw)

* [Flutter state management&mdash;scoped
  model](https://www.youtube.com/watch?v=Oql5bU-Uvso)

  [Flutter 的状态管理&mdash;Scoped Model](https://www.youtube.com/watch?v=Oql5bU-Uvso)

## Redux

* [Animation Management with Redux and Flutter](https://www.youtube.com/watch?v=9ZkLtr0Fbgk), a video from DartConf 2018 [Accompanying article on Medium]({{site.flutter-medium}}/animation-management-with-flutter-and-flux-redux-94729e6585fa)

  [使用 Redux 和 Flutter 进行动画管理](https://www.youtube.com/watch?v=9ZkLtr0Fbgk)，视频来自 DartConf 2018，[媒体文章]({{site.flutter-medium}}/animation-management-with-flutter-and-flux-redux-94729e6585fa)

* [Flutter Redux package]({{site.pub-pkg}}/flutter_redux) on the [Pub site]({{site.pub}})

  [Pub site]({{site.pub}}) 上的 [Flutter Redux package]({{site.pub-pkg}}/flutter_redux) 

* [Introduction to Redux in Flutter](https://blog.novoda.com/introduction-to-redux-in-flutter/), by Xavi Rigau

  由 Xavi Rigau 提供的 [Flutter Redux 简介](https://blog.novoda.com/introduction-to-redux-in-flutter/)

* [Flutter + Redux&mdash;How to make a shopping list app](https://hackernoon.com/flutter-redux-how-to-make-shopping-list-app-1cd315e79b65),
  by Paulina Szklarska on Hackernoon

  Paulina Szklarska 在 Hackernoon 上的 [Flutter + Redux&mdash;如何开发一款购物列表应用](https://hackernoon.com/flutter-redux-how-to-make-shopping-list-app-1cd315e79b65)

* [Building a TODO application (CRUD) in Flutter with Redux&mdash;Part 1](https://www.youtube.com/watch?v=Wj216eSBBWs),
  a video by Tensor Programming

  由 Tensor Programming 提供的视频 [Flutter 中使用 Redux 构建一个 TODO 应用（CRUD）&mdash;第一部分](https://www.youtube.com/watch?v=Wj216eSBBWs)

* [Flutter Redux Thunk, an example]({{site.medium}}/flutterpub/flutter-redux-thunk-27c2f2b80a3b),
  by Jack Wong

  由 Jack Wong 提供的 [Flutter Redux Thunk，示例]({{site.medium}}/flutterpub/flutter-redux-thunk-27c2f2b80a3b)

* [Building a (large) Flutter app with Redux](https://hillelcoren.com/2018/06/01/building-a-large-flutter-app-with-redux/),
  by Hillel Coren

  由 Hillel Coren 提供的 [使用 Redux 构建一个（大型）Flutter app](https://hillelcoren.com/2018/06/01/building-a-large-flutter-app-with-redux/)

* [Fish-Redux - An assembled flutter application framework based on Redux](https://github.com/alibaba/fish-redux/),
  by Alibaba

  由阿里巴巴提供的 [Fish-Redux - 基于 Redux 的集成 Flutter 应用框架](https://github.com/alibaba/fish-redux/)

## BLoC / Rx

* [Architect your Flutter project using BLoC pattern]({{site.medium}}/flutterpub/architecting-your-flutter-project-bd04e144a8f1),
  by Sagar Suri

  由 Sagar Suri 提供的 [使用 BLoC 模式构建你的 Flutter 工程]({{site.medium}}/flutterpub/architecting-your-flutter-project-bd04e144a8f1)

* [Bloc Library](https://felangel.github.io/bloc), by Felix Angelov

  由 Felix Angelov 提供的 [Bloc Library](https://felangel.github.io/bloc)

* [Reactive Programming - Streams - BLoC - Practical Use Cases](https://www.didierboelens.com/2018/12/reactive-programming---streams---bloc---practical-use-cases), by Didier Boelens

  由 Didier Boelens 提供的 [Reactive Programming - Streams - BLoC - Practical Use Cases](https://www.didierboelens.com/2018/12/reactive-programming---streams---bloc---practical-use-cases)

## MobX

* [MobX.dart, Hassle free state-management for your Dart and Flutter apps](https://github.com/mobxjs/mobx.dart)

  [MobX.dart，为你的 Dart 和 Flutter 应用提供无忧的状态管理](https://github.com/mobxjs/mobx.dart)

* [Getting started with MobX.dart](https://mobx.pub/getting-started)

  [MobX.dart 入门](https://mobx.pub/getting-started)

* [Flutter: State Management with Mobx](https://developer.school/posts/flutter-state-management-with-mobx/) by Paul Halliday

  由 Paul Halliday 提供的 [Flutter：使用 Mobx 进行状态管理](https://developer.school/posts/flutter-state-management-with-mobx/)

## Provider

* [Getting Started with Provider](https://developer.school/posts/flutter-provider-and-bloc-in-5-minutes/) by Paul Halliday

  由 Paul Halliday 提供的 [Provider 入门](https://developer.school/posts/flutter-provider-and-bloc-in-5-minutes/)
