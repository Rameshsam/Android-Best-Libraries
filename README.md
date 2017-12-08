# Android Best Libraries 2017


1. Matisse
This is a beautiful local images and videos selector. Main functionalities:
Selecting images including JPEG, PNG, GIF and videos including MPEG, MP4,
applying custom themes, including two built-in ones,
different image loaders,
defining custom filter rules,
fully operational within Activities and Fragments.
You can find more in the lib’s wiki.

zhihu/Matisse

Matisse - :fireworks: A well-designed local image and video selector for Android
github.com	
2. Spruce Android Animation Library
Spruce is a lightweight animation library that helps choreograph the animations on the screen. With so many different animation libraries out there, developers need to make sure that each view is animating at the appropriate time. Spruce can help designers request complex multi-view animations and not have the developers cringe at the prototype.

willowtreeapps/spruce-android

spruce-android - Spruce Animation Library
github.com	
3. MaterialChipsInput
Chips were presented in Material Design. They
represent complex entities in small blocks, such as a contact. A chip may contain entities such as a photo, text, rules, an icon, or a contact.
MaterialChipsInput is an implementation of that component for Android. The library provides two views : ChipsInput and ChipView.

pchmn/MaterialChipsInput

MaterialChipsInput - Implementation of Material Design Chips component for Android
github.com	
4. Grav
This library allows to create multiple animations based on points. Take a look — how smooth and beautiful animations you can make quite easily. README contains a lot of examples so you might check it here.

glomadrian/Grav

Grav - Configurable animations based on points
github.com	
5. Litho
Litho is not a library, it is a framework. A really powerful framework to build UI in a declarative way. It was developed by Facebook devs, so even if you do not want to try it, still it is worthy to observe and follow a development process.

Main features include:
using a declarative API to define UI components. You simply describe the layout for your UI based on a set of immutable inputs and the framework takes care of the rest.
Asynchronous layout: Litho can measure and layout your UI ahead of time without blocking the UI thread.
View flattening: Litho uses Yoga for layout and automatically reduces the number of ViewGroups that your UI contains.
Fine-grained recycling: Any component such as a text or image can be recycled and reused anywhere in the UI.
facebook/litho

litho - A declarative framework for building efficient UIs on Android.
github.com	
6. Adaptable Bottom Navigation
Some time ago Google updated Material Design guideline, and introduced bottom navigation bars, as one of several good UI patters to follow in our apps. They also added the implementation to the Design Support Library.

Adaptable Bottom Navigation can easily replace BottomNavigationView from Support Library. It is implemented in the way how ViewPager and TabLayout work. This is a short explanation from Buffer team:
As mentioned, when using the Bottom Navigation View from the Android Support Library, there can be a lot of boilerplate code for the switching of views. Because of this, we took inspiration from the TabLayout setupWithViewPager() method and created a custom ViewSwapper component that can be attached to a Bottom Navigation View to simplify the management of view display.
You can read more on Github. There is a quite comprehensive documentation and explanation why it was implemented (tip: clean architecture 🚀 ).

bufferapp/AdaptableBottomNavigation

AdaptableBottomNavigation - A simpler way for implementing the Bottom Navigation View on Android
github.com	
7. PatternLockView
This library allows you to implement pattern locking mechanism in your app easily and quickly. It is very easy to use and there are plenty of customization options available to change the functionality and look-and-feel of this view to match your needs.
It also supports RxJava 2 view bindings, so if you are a fan of reactive programming (just like me), you can get a stream of updates as the user draws the pattern.
The README is full of examples, so it is easy to start with the library.

aritraroy/PatternLockView

PatternLockView - An easy-to-use, customizable and Material Design ready Pattern Lock view for Android
github.com	
8. Isometric
This is a library which helps to draw isometric shapes. In my opinion, it is one of the coolest libraries in that list, as it reminds me of Monument Valley game. 
The library supports drawing multiple shapes, paths and complex structures, like the example below.

FabianTerhorst/Isometric

Isometric drawing library for Android
github.com	
9. UltraViewPager
We can treat this library as a ViewPager extension that encapsulates many features, mainly to provide a unified solution for multi-page switching scenarios.

UltraViewPager supports:
horizontal scrolling and vertical scrolling,
multi views in one ViewPager
switching views circularly. For example, if there are 3 views to display in a ViewPager, it should switch back to the first view after the third view,
auto-scrolling feature (implemented timer using Handler),
setting max-height and max-width,
setting the aspect ratio,
indicating the view we are currently (circle and icon),
built-in two kinds of page transition animations.
This library has a good documentation as well.
alibaba/UltraViewPager

UltraViewPager is an extension for ViewPager to provide multiple features in a single ViewPager.
github.com	
10. InfiniteCards
This library helps to implement UI cards and then switch them with a nice animation.

BakerJQ/Android-InfiniteCards

Android-InfiniteCards - An infinite card switching UI for Android, support custom animation 可自定义动效的卡片切换视图
github.com	
11. SlidingRootNav
This is a library which we can consider as a DrawerLayout-like ViewGroup, where a drawer is hidden under the content view, and then can be shifted to make the drawer visible. REAMDE is quite comprehensive and it is worthy to check for sure.

yarolegovich/SlidingRootNav

SlidingRootNav - DrawerLayout-like ViewGroup, where a "drawer" is hidden under the content view, which can be shifted…
github.com	
12. PasscodeView
It is just a view where you can type your password. But fancy one!

hanks-zyh/PasscodeView

Material Design PasscodeView for Android.
github.com	
13. MusicWave
This library allows to represent sound as a gradient colored visualisation.

akshay2211/MusicWave

With MusicWave represent your Sound in a gradient colored Visualization
github.com	
14. ShadowImageView
This library helps you to add more meaningful shadow to your images. According to README, it is
More exquisite shadow effect, used in some special scene to enhance the user experience.
Also, it is easy to use.

yingLanNull/ShadowImageView

ShadowImageView - 🔥可以根据图片内容变阴影颜色，更加细腻的阴影效果 It can change color according to the picture, more delicate shadow effect
github.com	
15. PolygonDrawingUtil
This is an efficient Android utility class for drawing regular polygons on a Canvas. We can specify:
Number of sides (≥ 3),
center coordinates,
outer radius (center to vertex),
corner rounding radius,
polygon rotation,
fill/stroke Paint.

stkent/PolygonDrawingUtil

PolygonDrawingUtil - An efficient Android utility class for drawing regular polygons on a Canvas.
github.com	
16. Tiny
This is a second framework on that list. It is responsible for image compression and it is quite powerful. Also, it
uses asynchronous thread pool to compress image, and will hand out the result in the main thread when compression is completed.

Effects of compression
Sunzxyong/Tiny

Tiny - an image compression framework.
github.com	
17. ParticleTextView
This library provides a custom TextView widget, which can create text from particles using a variety of animation effects and configuration properties.

Yasic/ParticleTextView

ParticleTextView - 一个用粒子动画显示文字的 Android 自定义 View
github.com	
18. CropIwa
This is a highly configurable widget for image cropping. The library has a modular architecture, which makes it highly configurable. For the info on how to configure CropIwaViewrefer to the wiki on Github.

steelkiwi/cropiwa

cropiwa - 📐 Configurable Custom Crop widget for Android
github.com	
19. Project Condom
This is a thin library to wrap the naked Context in your Android project before passing it to the 3rd-party SDK. It is designed to prevent the 3rd-party SDK from common unwanted behaviors which may harm the user experience of your app.
And here is the explanation:
Massive launch of processes in other apps (common in 3rd-party push SDKs), causing slow app starting and notable lagging on low to middle-end devices. This behavior has chain reaction effects among apps with similar SDKs, greatly aggravating the overall device performance.
oasisfeng/condom

condom - 一个超轻超薄的Android工具库，阻止三方SDK中常见的有害行为，而不影响应用自身的功能。（例如严重影响用户体验的『链式唤醒』）
github.com	
20. AppMethodOrder
This library allows you to trace all functions calls order. The project is well documented and you can find detailed manuals how to use it. The only constraint is that, it is written in Chinese, but you can always click Translate to English in your browser and enjoy this great project.

zjw-swun/AppMethodOrder

AppMethodOrder - 一个能让你了解所有函数调用顺序以及函数耗时的Android库（无需侵入式代码）
github.com	
21. Android DebugKit
This is an interesting library. It allows you to create and use special hovering debug tool, to trigger actions defined by you in an application. These actions can be obviously triggered in runtime, so it may be used for instance during feedback writing or testing a phone screen. 
The library uses Builder pattern. It is easy to use and in README, there is one example of the usage.

hulab/debugkit

debugkit - Ever hid debug functions in your UI? Here is now a clean way to do it!
github.com	
22. Aesthetic
This a fresh library and still in beta, but it does a really cool thing — it changes your theme dynamically with Rx support! According to the author, this is
A fast and easy to use plug-and-play dynamic theme engine. Powered by Rx, for Android apps.
The documentation is really good, comprehensive and definitely worthy to check out.

afollestad/aesthetic

aesthetic - [BETA] A fast and easy to use plug-and-play dynamic theme engine. Powered by Rx, for Android apps.
github.com	
23. EasyCalendar
This is an easy custom calendar widget. Main features include:
Custom layout for title,
custom layout for date,
show or hide divider for date,
show or hide overflow date,
listen to date’s view be clicked.
The documentation is comprehensive and the library is easy to use.

shichaohui/EasyCalendar

Quickly customize the calendar UI. You can use EasyCalendar to quickly get the calendar style UI.
github.com	
24. SimpleRatingBar
This library provides two rating bars:
BaseRatingBar — without any animation,
ScaleRatingBar — with a progressive and scale animation.
You can see them in a gif below:

ome450901/SimpleRatingBar

SimpleRatingBar - A simple RatingBar with scale animation
github.com	
25. Magellan
This library is advertised as the simplest navigation library for Android, but you need to check if it is worthy for you to use it. 
Main features:
Navigation is as simple as calling goTo(screen) method,
you get full control of the backstack,
transitions are automatically handled for you.
It has comprehensive wiki with all explanations needed.

wealthfront/magellan

magellan - The simplest navigation library for Android.
github.com	
26. ViewPagerAnimator
ViewPagerAnimator is a new lightweight, yet powerful ViewPager animation library for Android. it is designed to animate arbitrary values as the user navigates between pages within a ViewPager, and will precisely follow the motion of h[is|er] finger. Although the library itself may be of use to some, the main purpose of publishing this library is to demonstrate some wonderful API subtleties which really come to the fore when using Java 8 extensions which are coming our way soon. Sample projects for both Java 7 and Java 8 are provided.
It is written by Mark Allison and you can get more info on his Styling Android blog.

StylingAndroid/ViewPagerAnimator

ViewPagerAnimator - A lightweight, yet powerful ViewPager animation library for Android
github.com	
27. BlockCanaryEx
This is a library, which facilitates finding heavy methods in your code when your app blocked. It is based on BlockCanary.

seiginonakama/BlockCanaryEx

BlockCanaryEx — make performance bottleneck detection easily when app blocked
github.com	
28. PaletteImageView
This is quite cool library. It adds a shadows to your images, but the color of shadow is in a dominant image color.

Documentation is quite poor but I think the code is self-explanatory.
DingMouRen/PaletteImageView

PaletteImageView - 为图片添加阴影，阴影颜色来源于图片的主色
github.com	
29. RecyclerRefreshLayout
This is a refresh animation that opens a camera shutter. In my opinion it is really worthy to check, especially in README there is a mathematical analysis, how to achieve this effect!

dinuscxj/ShootRefreshView

ShootRefreshView - It's an refresh animation that opens the shutter
github.com	
30. SlimAdapter
This is an approach to write an Adapter without ViewHolder. Key features include:
No ViewHolders,
no reflection,
fluent & simple API,
multi-typeable adapter,
Kotlin support,
Simple DiffUtil support.

MEiDIK/SlimAdapter

SlimAdapter - A slim & clean & typeable Adapter without# VIEWHOLDER
github.com	
That’s it
