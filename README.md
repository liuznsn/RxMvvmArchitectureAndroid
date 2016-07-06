# Android MVVM Architecture

## Code style

[android best practices](https://github.com/futurice/android-best-practices)

[google android code style](https://source.android.com/source/code-style.html)

[android project and code guidelines](https://github.com/ribot/android-guidelines/blob/master/project_and_code_guidelines.md)

[CodePath Android Cliffnotes](https://github.com/codepath/android_guides/wiki)

## MVVM
The architecture of our ios apps is based on the [MVVM] (https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93viewmodel)

* __View (UI layer)__: This is where view, Activities, Fragments and other standard Android components, also handles user interactions and inputs. The View is rather synchronized with the viewmodel, active and contains behaviors, events and data binding information.

* __ViewModel__: The viewmodel in MVVM is responsible for presentation separation and exposes methods and commands to manage the state of a view and manipulate the model.

* __Model (Data Layer)__:this is responsible for retrieving, saving, caching and massaging data. It can communicate with local databases and other data stores as well as with restful APIs or third party SDKs.



![MVVM](http://tech.vg.no/files/2015/07/mvvm.png)

![MVVM](https://cdn-images-1.medium.com/max/800/1*WfT-BCzN0ZAGzdE30oea1g.png)

![MVVM](https://github.com/fabioCollini/mv2m/blob/master/mv2m-class-diagram.png)

## Dependencies

- [RxAndroid](https://github.com/ReactiveX/RxAndroid):RxJava bindings for Android
- [RxBinding](https://github.com/JakeWharton/RxBinding): RxJava binding APIs for Android's UI widgets.
- [Butterknife](http://jakewharton.github.io/butterknife/):Bind Android views and callbacks to fields and methods. 
- [Retrofit](https://github.com/square/retrofit):Type-safe HTTP client for Android and Java by Square, Inc.
- [Gson](https://github.com/google/gson):A Java serialization/deserialization library that can convert Java Objects into JSON and back.
- [Retrofit Adapters](https://github.com/square/retrofit/tree/master/retrofit-adapters):
- [Logging Interceptor](https://github.com/square/okhttp/tree/master/okhttp-logging-interceptor):An OkHttp interceptor which logs HTTP request and response data.
- [Picasso](https://github.com/square/picasso):A powerful image downloading and caching library for Android
- [RxGroups](https://github.com/airbnb/RxGroups):Easily group RxJava Observables together and tie them to your Android Activity lifecycle
- [Glide](https://github.com/bumptech/glide):An image loading and caching library for Android focused on smooth scrolling
- [leakcanary](https://github.com/square/leakcanary):A memory leak detection library for Android and Java.


## Android Studio Plugin

- [Android Code Styles] (https://github.com/ogaclejapan/android-code-styles)
- [ButterKnifeZelezny] (https://github.com/avast/android-butterknife-zelezny)
- [GsonFormat] (https://github.com/zzz40500/GsonFormat):Generate gson objects from JSON Schema

## Testing

![MVVM](https://github.com/liuznsn/RxMvvmArchitectureAndroid/blob/master/MVVM_TDD.png)

- https://medium.com/@hiBrianLee/writing-testable-android-mvvm-app-part-4-e2f83fc21d71#.25v48essn


## Reference

- https://github.com/ffgiraldez/rx-mvvm-android
- http://www.slideshare.net/fabio_collini/data-binding-in-action-using-mvvm-pattern
- https://github.com/fabioCollini/mv2m
- https://github.com/ivacf/archi
- https://github.com/erikcaffrey/People-MVVM
- https://github.com/googlesamples/android-architecture
- https://github.com/hitherejoe/MVVM_Hacker_News
- https://github.com/reark/reark
