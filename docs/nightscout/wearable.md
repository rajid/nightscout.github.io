# How to display Nightscout data on your watch.

</br>

## Pebble Smartwatches

<img src="..\img\PebbleNSFoundation.jpeg" style="zoom:50%;" />

Pebble smartwatch use is a historic milestone of CGM in the Cloud. Pebble has been bought by Fitbit in 2016 and necessary resources have moved to archives and [rebble.io](https://rebble.io/). Pebble support is still maintained in Loop, AndroidAPS, FreeAPS and xDrip+.

You still can find the Pebble app for iOS in the [Apple Store](https://apps.apple.com/us/app/pebble/id957997620). For Android you need to download it from [APKMirror](https://www.apkmirror.com/apk/pebble-technology-corp/pebble/pebble-4-4-2-1405-62d45d7d7-endframe-release/pebble-4-4-2-1405-62d45d7d7-endframe-android-apk-download/) or [APKPure](https://apkpure.com/it/pebble/com.getpebble.android.basalt).

For authentication and getting the watchfaces, the original server closed so you'll need to register with [Rebble](https://auth.rebble.io/auth/).

You'll find Nightscout watchfaces [here](https://apps.rebble.io/en_US/search/watchfaces/1). Search for Nightscout, CGM, ... 

Configure the watchface with your Nightscout site URL.

</br>

##### [urchin](https://github.com/mddub/urchin-cgm)

A Pebble watchface to view data from a continuous glucose monitor in graph format.

</br>

If you want to use your Pebble with Loop look [here](https://loopkit.github.io/loopdocs/nightscout/pebble/), for AndroidAPS [here](https://androidaps.readthedocs.io/en/latest/EN/Configuration/Watchfaces.html#pebble) and FreeAPS [here](https://github.com/mddub/pancreabble).

</br>

#### [xDrip+](https://github.com/NightscoutFoundation/xDrip/releases)

Enable Pebble Integration in Smartwatch features.

<img src="..\img\Watch02.png" style="zoom:80%;" />

</br>

You can answer no to default watchface install so that you will be able to select another one. You can then decide to install or not the snooze control.

<img src="..\img\Watch03.png" style="zoom:80%;" />

</br>

## [Android Wear OS smartwatches](https://wearos.google.com/#hands-free-help)

With an Android smartphone.

##### Android Wear 1.x:

- Recommended: Install an old version of Android Wear on your phone (search APKMirror for example: Android Wear 2.9.0.185084575.gms) and pair your watch. Make sure to allow GPS and Wear OS access to position on the watch. Allow Wear OS to run in background on your phone.

!!!note
     If you installed Wear OS, you will need to manually update the watch the Google Play Services see [here](https://androidaps.readthedocs.io/en/latest/EN/Usage/SonySW3.html).

  - Once your smartwatch Google Play Service has been updated to a version above 9.x you can safely update Android Wear to Wear OS.
  - Change the watchface to match your app (in Wear OS or on your watch).

##### Android Wear 2.x:

- Install [Wear OS](https://play.google.com/store/apps/details?id=com.google.android.wearable.app) on your phone and pair your watch. Make sure to allow GPS and Wear OS access to position on the watch. Allow Wear OS to run in background on your phone.

- [Install](https://support.google.com/wearos/answer/7314014?hl=en) your app wear extension from the smartwatch Google Play store, selecting the apps installed on your phone.

  *Note: Newer versions of Wear OS do not support this feature anymore, use [Wear Installer](https://youtu.be/8HsfWPTFGQI).*

- Change the watchface to match your app (in Wear OS or on your watch).

#### [xDrip+](https://github.com/NightscoutFoundation/xDrip/releases)

Enable Android Wear Integration to send xDrip+ BG to the smartwatch. Do not enable neither Collection nor Force Collection.

<img src="..\img\Watch00.png" style="zoom:80%;" />

Full xDrip+ wear documentation [here](https://github.com/jamorham/xDrip-plus/blob/master/Documentation/WatchGuide.md).

*NB: you can also use [Tasker](./#xdrip-with-tasker).*

#### [AndroidAPS](https://androidaps.readthedocs.io/en/latest/EN/Installing-AndroidAPS/Building-APK.html)

For AndroidAPS [here](https://androidaps.readthedocs.io/en/latest/EN/Configuration/Watchfaces.html#aaps-on-wear-os-smartwatch).

#### [Glimp](https://play.google.com/store/apps/details?id=it.ct.glicemia)

Select your Wearable device and enable the Glimp watchface.

<img src="..\img\Watch01.png" style="zoom:75%;" />

#### [NightWear](https://github.com/rahim/nightwear)

NightWear is a Wear OS app available in the [Google Play Store](https://play.google.com/store/apps/details?id=im.rah.nightwear&utm_source=github&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1) directly from your watch. You can use it with Android and iOS.

</br>

## Amazfit Pace & Stratos

#### [xDrip+](https://github.com/NightscoutFoundation/xDrip/releases)

- Install the [Amazfit watch app](https://play.google.com/store/apps/details?id=com.huami.watch.hmwatchmanager) on your phone.
- Install the [Amazfit tool](https://forum.xda-developers.com/t/tool-pace-stratos-verge-tool-all-in-one-drivers-unlock-twrp-factory-image.3874802/) on a Windows PC.
- Download the [widget](https://github.com/Klaus3d3/XdripWidgetForAmazfit-Klaus/releases) from the project author (Klaus3d3) GitHub [repository](https://github.com/Klaus3d3/XdripWidgetForAmazfit-Klaus).
- OEM unlock and enable USB debug on the watch, run TOOL ALL IN ONE and click the APK Installer button, select the widget apk file and INSTALL it. Close the install window and click Reboot System.
- In xDrip+, enable the Amazfit service and select the options you want to enable.

<img src="..\img\Watch04.png" style="zoom:75%;" />

*Original instructions [here](https://crazyinfo.de/2018/07/25/xdrip-smartwatch-widget-fuer-amazfit-pace-stratos).*

</br>

## Xiaomi MiBand 4, 5 and 6

## Amazfit Band 5, Bip, Bip Lite, Bip S and GTR

## Amazfit GTR2, GTR2e, GTS2, GTS2e and GTR42

#### xDrip+

Follow Artem's instructions [here](https://bigdigital.home.blog/).

</br>

## Apple Watch

#### [Nightguard](https://apps.apple.com/us/app/nightguard/id1116430352#?platform=appleWatch)

Apple Watch series 3 and above.

[GitHub](https://github.com/nightscout/nightguard)

</br>

#### [sugarmate](https://sugarmate.io/)

!!!note "Important limitation"
    Sugarmate doesn't allow Nightscout as a data source if you receive your data from Dexcom share with `bridge`.

You can setup sugarmate as a calendar complication to display Nightscout on your Apple watch.

</br>

#### [nsapple](https://github.com/Perceptus/nsapple)

nsapple is an apple watch app for Nightscout / Loop followers.

</br>

#### [Loop Follow](https://sweloop.se/LoopFollow/index.html)

You can setup Loop Follow as a calendar complication to display Nightscout on your Apple watch.

</br>

## Fitbit

#### [Nightscout Monitor](https://gallery.fitbit.com/details/eaed806d-9ff5-4aa9-a2c8-518f1f852f5a)

Ionic/Sense/Versa/Versa 2/Versa 3/Versa Lite

[Repository](https://github.com/sulkaharo/nsfitbit)

</br>

#### [Glance](https://gallery.fitbit.com/details/7b5d9822-7e8e-41f9-a2a7-e823548c001c)

Ionic/Sense/Versa/Versa 2/Versa 3/Versa Lite

[Web site](https://glancewatchface.com/)

</br>

#### [Sentinel](https://gallery.fitbit.com/developer/b50ac7f5-b932-441a-be18-e258b17c736b)

Ionic/Sense/Versa/Versa 2/Versa Lite

Facebook group: [Sentinel](https://www.facebook.com/groups/3185325128159614)

</br>

#### [Marclock](https://gallery.fitbit.com/details/9eacf714-5b23-40c8-9621-ded74bd9edf9)

Ionic/Sense/Versa/Versa 2/Versa Lite

[Instructions](https://github.com/cramis1/Marclock-with-CGM-weather/blob/master/README.md)

</br>

## Samsung Gear Smartwatches

#### xDrip+ with Tasker

*Note: also available for Android Wear devices*

[Instructions](https://github.com/FreDiabetics/xDrip--Tasker-Tizen-Watchface-Integration/blob/master/README.md)

</br>

#### [G-Watch app](https://play.google.com/store/apps/details?id=sk.trupici.g_watch)

Facebook group: [G-Watch App](https://www.facebook.com/gwatchapp)

</br>

## Garmin Smartwatches and Computers

By [Phimby](https://apps.garmin.com/en-US/developer/74d80f40-f80a-45c2-b934-321cc86f9dac/apps)

By [Horsetooth](https://apps.garmin.com/en-US/developer/e985e9ec-bcf6-4aef-bfe9-77c1c93fc854/apps)

By [andreas-may](https://apps.garmin.com/en-US/developer/f9420c47-810f-47ac-a7dd-9fa7b8ecd22d/apps)

By [Fredrik_S](https://apps.garmin.com/en-US/developer/c3842ca7-a645-4758-b9ed-4ee6f8e3abec/apps)

By [John_](https://apps.garmin.com/en-US/developer/b2d30711-2708-4f3a-8e83-009c16d07081/apps)