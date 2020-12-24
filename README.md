<!--
*** Bu dökümantasyon MOBILION için hazırlanmıştır.
*** doc version: 1.0.0
*** author @gorkem.kara @bugra.yetkin
*** Android DevOps Team
-->

<p align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <center><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Android_logo_2019.svg/1374px-Android_logo_2019.svg.png" width="100" height="100" alt="Android" align="center" style="display: block;margin: 0 auto;"></center>
  </a>
  <h3 align="center">ANDROID BASE PROJECT</h3>
  <p align="center">
    Mobilion'da Android Devops'un hazırladığı MVVM yapısı
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="https://developer.android.com/topic/libraries/architecture/images/final-architecture.png" alt="mvvm-architecture" >
  </a>
</p>



<details open="close" style="margin-left:50px;margin-top:100px;margin-bottom:100px">
  <summary>Base Project</summary>
  <ul>
  <li>
      <details>
  <summary>Base Yapı</summary>
  <ul>
    <li>
      <a href="#android-manifest">AndroidManifest</a>
    </li>
    <li>
      <a href="#package">Package</a>
        <details>
        <summary>base</summary>
      <ul>
                <li>
                <a href="#adapter">Adapter</a>
                    <ul>
                        <li><a href="#base-diff-util">BaseDiffUtil</a></li>
                        <li><a href="#base-recycler-view-adapter">BaseRecyclerViewAdapter</a></li>
                        <li><a href="#base-recycler-view-filter-adapter">BaseRecyclerViewFilterAdapter</a></li>
                        <li><a href="#base-spinner-adapter">BaseSpinnerAdapter</a></li>
                        <li><a href="#base-view-binding-recyclerview-adapter">BaseViewBindingRecyclerViewAdapter</a></li>
                        <li><a href="#base-view-binding-recyclerview-filter-adapter">BaseViewBindingRecyclerViewFilterAdapter</a></li>
                        <li><a href="#base-view-binding-recyclerview-input-adapter">BaseViewBindingRecyclerViewInputAdapter</a></li>
                    </ul>
                </li>
                <li>
                <a href="#alarm">Alarm</a>
                    <ul>
                        <li><a href="#alarm-manager-management">AlarmManagerManagement</a></li>
                        <li><a href="#base-alarm-receiver">BaseAlarmReceiver</a></li>
                    </ul>
                </li>
                <li>
                <a href="#base-binding">Binding</a>
                    <ul>
                        <li><a href="#base-adapter-bindings">AdapterBindings</a></li>
                        <li><a href="#base-view-bindings">ViewBindings</a></li>
                    </ul>
                </li>
                <li>
                <a href="#dialog">Dialog</a>
                    <ul>
                        <li><a href="#base-binding-dialog">BaseBindingDialog</a></li>
                        <li><a href="#base-botttom-sheet-dialog">BaseBottomSheetDialog</a></li>
                        <li><a href="#base-dialog">BaseDialog</a></li>
                        <li><a href="#binding-popup-window">BindingPopupWindow</a></li>
                    </ul>
                </li>
                <li><a href="#base-activity">BaseActivity</a></li>
                <li><a href="#base-application">BaseApplication</a></li>
                <li><a href="#base-filter">BaseFilter</a></li>
                <li><a href="#base-fragment">BaseFragment</a></li>
                <li><a href="#base-model">BaseModel</a></li>
                <li><a href="#base-view-model">BaseViewModel</a></li>
                <li><a href="#live-coroutines-view-model">LiveCoroutinesViewModel</a></li>
            </ul>
        </details>
        <details>
        <summary>data</summary>
            <ul>
                <li><a href="#data-model">Model</a></li>
                <li><a href="#data-repository">Repository</a></li>
                <li><a href="#data-source">Source</a></li>
            </ul>
        </details>
        <details>
        <summary>network</summary>
            <ul>
                <li><a href="#network-module">NetworkModule</a></li>
            </ul>
        </details>
       <details>
        <summary>ui</summary>
            <ul>
                <li><a href="#ui-ui">UI</a></li>
            </ul>
        </details>
        <details>
        <summary>utils</summary>
            <ul>
                <details>
                <summary>connectivity</summary>
                    <ul>
                        <li><a href="#utils-connectivity">Connectivity</a></li>
                    </ul>
                </details>
                <details>
                <summary>extension</summary>
                    <ul>
                        <li><a href="#extension-activity-extension">ActivityExtension</a></li>
                        <li><a href="#extension-fragment-extension">FragmentExtension</a></li>
                        <li><a href="#extension-view-extension">ViewExtension</a></li>
                    </ul>
                </details>
                <details>
                <summary>general</summary>
                    <ul>
                        <li><a href="#general-bitmap-utils">BitmapUtils</a></li>
                        <li><a href="#general-control-utils">ControlUtils</a></li>
                        <li><a href="#general-control-file-to-base64-listener">CovertFileToBase64Listener</a></li>
                        <li><a href="#general-date-utils">DateUtils</a></li>
                        <li><a href="#general-file-utils">FileUtils</a></li>
                        <li><a href="#general-language-utils">LanguageUtil</a></li>
                        <li><a href="#general-media-utils">MediaUtils</a></li>
                        <li><a href="#general-project-constants">ProjectConstants</a></li>
                        <li><a href="#general-size-utils">SizeUtils</a></li>
                        <li><a href="#general-version-utils">VersionUtils</a></li>
                    </ul>
                </details>
                <details>
                <summary>locale</summary>
                    <ul>
                        <li><a href="#locale-background-location-service">BackgroundLocationService</a></li>
                        <li><a href="#locale-locale-manager">LocaleManager</a></li>
                        <li><a href="#locale-location-listener">LocationListener</a></li>
                        <li><a href="#locale-location-service">LocationService</a></li>
                    </ul>
                </details>
                <details>
                <summary>recycler</summary>
                    <ul>
                        <li><a href="#recycler-reyclerview-paginator">RecyclerViewPaginator</a></li>
                    </ul>
                </details>
                <details>
                <summary>security</summary>
                </details>
                <details>
                <summary>whatIf</summary>
                    <ul>
                        <li><a href="#whatif-whatif">WhatIf</a></li>
                        <li><a href="#whatif-whatifarray">WhatIfArray</a></li>
                        <li><a href="#whatif-whatifcollections">WhatIfCollections</a></li>
                        <li><a href="#whatif-whatifinlineinly">WhatIfInlineOnly</a></li>
                        <li><a href="#whatif-whatifstring">WhatIfString</a></li>
                    </ul>
                </details>
                <li><a href="#appconstants">AppConstants</a></li>
                <li><a href="#appextentions">AppExtentions</a></li>
                <li><a href="#handylog">HandyLog</a></li>
                <li><a href="#lifecycle-delegate">LifecycleDelegate</a></li>
                <li><a href="#my-context-wrapper">MyContextWrapper</a></li>
                <li><a href="#my-live-data">MyLiveData</a></li>
            </ul>
        </details>
        <ul><li><a href="#main-application">MainApplication</a></li></ul>
    </li>
    <details>
     <summary>res</summary>
      <ul>
        <details>
         <summary>anim</summary>
          <ul>
            <li><a href="#scale_in">scale_in</a></li>
            <li><a href="#scale_out">scale_out</a></li>
          </ul>
        </details>
        <details>
         <summary>drawable</summary>
        </details>
        <details>
         <summary>layout</summary>
        </details>
        <details>
         <summary>mipmap</summary>
        </details>
        <details>
         <summary>values</summary>
          <ul>
            <li><a href="#values-colors">colors</a></li>
            <li><a href="#values-strings">strings</a></li>
            <li><a href="#values-styles">styles</a></li>
        </details>
        <details>
         <summary>xml</summary>
          <ul>
            <li><a href="#xml-network-security-config">network_security_config</a></li>
        </details>
      </ul>
    </details>
    <li>
      <a href="#package">buildSrc</a>
        <details>
        <summary>java</summary>
      <ul>
        <li><a href="#buildsrc-dependencies">Dependencies</a></li>
      </ul>
        </details>
    </li>
  </ul>
</details>
    </li>
  <li>
      <details>
  <summary>Kütüphaneler</summary>
  <ul>
    <li>
      <a href="#kotlin">Kotlin</a>
      <ul>
        <li><a href="#kotlin-jdk8">Kotlin JDK8</a></li>
		<li><a href="#core-ktx">CoreKtx</a></li>
        <li><a href="#kotlin-dsl">Kotlin DSL</a></li>
      </ul>
    </li>
    <li>
      <a href="#ui-ux">UI / UX</a>
      <ul>
        <li><a href="#app-compat">AppCompat</a></li>
        <li><a href="#material">Material</a></li>
        <li><a href="#constraint-layout">ConstraintLayout</a></li>
        <li><a href="#swipe-refresh-layout">Swipe-Refresh-Layout</a></li>
        <li><a href="#recyclerView">RecyclerView</a></li>
        <li><a href="#fragment-ktx">FragmentKtx</a></li>
      </ul>
    </li>
    <li>
      <a href="#architecture-components">ARCHITECTURE COMPONENTS</a>
      <ul>
        <li><a href="#lifecycle-viewmodel-ktx">Lifecycle ViewModel Ktx</a></li>
        <li><a href="#lifecycle-viewmodel">Lifecycle ViewModel</a></li>
        <li><a href="#lifecycle-livedata-ktx">Lifecycle LiveData Ktx</a></li>
        <li><a href="#lifecycle-runtime-ktx">Lifecycle Runtime Ktx</a></li>
      </ul>
    </li>
    <li>
      <a href="#coroutines">COROUTINES</a>
      <ul>
        <li><a href="#coroutines-core">Coroutines Core</a></li>
        <li><a href="#coroutines-android">Coroutines Android</a></li>
      </ul>
    </li>
    <li>
      <a href="#work-manager">Work Manager</a>
    </li>
    <li>
      <a href="#network">Network</a>
      <ul>
        <li><a href="#retrofit">Retrofit</a></li>
        <li><a href="#retrofit-rxjava3">Retrofit RXJava3</a></li>
        <li><a href="#retrofit-converter-moshi">Retrofit Converter Moshi</a></li>
        <li><a href="#moshi">Moshi</a></li>
        <li><a href="#moshi-kotlin">Moshi Kotlin</a></li>
        <li><a href="#moshi-adapters">Moshi Adapters</a></li>
        <li><a href="#logging-interceptor">Logging Interceptor</a></li>
      </ul>
    </li>
    <li>
      <a href="#rx">RX</a>
      <ul>
        <li><a href="#rx-android">RXAndroid</a></li>
        <li><a href="#rx-java">RXJava</a></li>
        <li><a href="#rx-java3">Adapter RXJava3</a></li>
        <li><a href="#rx-kotlin">RXKotlin</a></li>
      </ul>
    </li>
    <li>
      <a href="#dagger-hilt">DAGGER HILT</a>
      <ul>
        <li><a href="#hilt-android">Hilt Android</a></li>
        <li><a href="#hilt-viewModel">Hilt ViewModel</a></li>
        <li><a href="#hilt-android-compiler">Hilt Android Compiler</a></li>
        <li><a href="#hilt-compile">Hilt Compile</a></li>
      </ul>
    </li>
    <li>
      <a href="#test-unit">TEST UNIT</a>
      <ul>
        <li> <a href="#junit4">JUNIT4</a></li>
        <li><a href="#test-runner">Test Runner</a></li>
        <li><a href="#espresso">Espresso</a></li>
      </ul>
    </li>
    <li>
      <a href="#other">OTHER</a>
      <ul>
        <li> <a href="#hawk">HAWK</a></li>
        <li><a href="#timber">Timber</a></li>
        <li><a href="#google-location">Google Location</a></li>
      </ul>
    </li>
  </ul>
</details>
    </li>
  <li>
      <details>
  <summary>Kurallar</summary>
  <ul>
    <li>
      <a href="#kotlin">Kotlin</a>
      <ul>
        <li><a href="#kotlin-jdk8">Kotlin JDK8</a></li>
		<li><a href="#core-ktx">CoreKtx</a></li>
        <li><a href="#kotlin-dsl">Kotlin DSL</a></li>
      </ul>
    </li>
  </ul>
</details>
    </li>
    <li>
      <details>
  <summary>İsimlendirme Standartları</summary>
  <ul>
    <li>
      <a href="#kotlin">Kotlin</a>
      <ul>
        <li><a href="#kotlin-jdk8">Kotlin JDK8</a></li>
		<li><a href="#core-ktx">CoreKtx</a></li>
        <li><a href="#kotlin-dsl">Kotlin DSL</a></li>
      </ul>
    </li>
  </ul>
</details>
    </li>
    <li>
      <details>
  <summary>Branch Modeli</summary>
  <ul>
    <li>
      <a href="#kotlin">Kotlin</a>
      <ul>
        <li><a href="#kotlin-jdk8">Kotlin JDK8</a></li>
		<li><a href="#core-ktx">CoreKtx</a></li>
        <li><a href="#kotlin-dsl">Kotlin DSL</a></li>
      </ul>
    </li>
  </ul>
</details>
    </li>
    <li>
      <details>
  <summary>Kod inceleme ve onaylama</summary>
  <ul>
    <li>
      <a href="#kotlin">Kotlin</a>
      <ul>
        <li><a href="#kotlin-jdk8">Kotlin JDK8</a></li>
		<li><a href="#core-ktx">CoreKtx</a></li>
        <li><a href="#kotlin-dsl">Kotlin DSL</a></li>
      </ul>
    </li>
  </ul>
</details>
    </li>
    
  </ul>
</details>




<!-- ABOUT THE PROJECT -->
## Proje Hakkında

Dependency Injection ile Dagger Hilt ve Repository Pattern ile MVVM mimarisi kullanılarak oluşturulan temel proje.
<br><br>
Neden MVVM Kullanıyoruz?
* Geleneksel UI dizaynında yeni çıkan; işlerimizi hızlandıran ve performansı arttırıcı yapılar nedeniyle MVVM kullanıyoruz.
*  Veri modellerimiz tasarımlara ViewModel üzerinden ViewBinding ile kullanıcı bellek sızıntısına uğratmadan veri aktarımı yapabiliyoruz.
* Databinding ile UI'da hızlı düzenlemeler yapılabiliyor. 
* ViewBinding ile daha okunabilir, daha hızlı ve daha güvenli uygulamalar geliştirebiliyoruz.
* RXJava - RXKotlin ile asenkron ve fonksiyon programlama yapabiliyoruz.<br><br>
Büyük yapılar içim kullandığımız MVVM Tasarım Kalıbı çok fazla iş parçacığını düzenli ve hızlı yönetilebilir hale getiriyor.<br>
Google ve Apple 2018’den itibaren MVVM'e geçilmesi öneriyor. 

Öğrenme ve uygulama açısından yararlı kaynanklara <a href="#kotlin-dsl">buradan</a> ulaşabilirsiniz.

<!-- GETTING STARTED -->
## Başlangıç

Bu, projeyi kullanmak için ihtiyaç duyduğunuz şeylerin nasıl listeleneceğine ve bunların nasıl kurulacağına dair bir örnektir.<br>

### Hazırlık
Git'i indirip kurun;
<a href="https://git-scm.com/downloads" target="_blank">https://git-scm.com/downloads</a>
  ```sh
  $ brew install git 
  ```
### Kurulum

1. Depoyu yerel olarak kopyalayıp bağlayın, böylece yaptığınız güncellemeleri gönderebilir ve başkalarının yaptığı değişiklikleri alabilirsiniz
2. Repoyu kopyalayın
   ```sh
   git clone https://rgorkemkara@bitbucket.org/mobiliondevelopment/001_android_mobilionbase.git
   ```
   veya
   ```sh
   git clone ssh://git@bitbucket.org:mobiliondevelopment/001_android_mobilionbase.git 
   ```
3. Android Studio'yu açın ve terminalde şunu çalıştırın.
   ```sh
   ./gradlew clean build
   ```


<!-- USAGE EXAMPLES -->
## Kullanım

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

 1. <a href="#buildsrc-dependencies">Dependencies</a>'i açın.
   ```sh
   const val applicationId = "com.mobilion.baseproject" 
   ```
kısmını projenize göre değiştirin.

2. <a href="#package">Package</a>'in içerisinde 'baseproject' paketini projenize göre değiştirin.
3. <a href="#android-manifest">Manifest</a> dosyasını açın packageyi düzenleyin.</a>





[product-screenshot]: http://13.73.160.196/assets/img/logo.png
