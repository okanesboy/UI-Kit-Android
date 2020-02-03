# Android-UI-Kit
UI Kit is component for Android

## Installation
Maven
```
<dependency>
  <groupId>com.nesprasit.design</groupId>
  <artifactId>design</artifactId>
  <version>0.1.0</version>
  <type>pom</type>
</dependency>
```
Gradle
```
implementation 'com.nesprasit.design:design:0.1.0'
```
## How to use
CheckBox
```
<com.nesprasit.design.CheckBox
  android:layout_width="wrap_content"
  android:layout_height="wrap_content"
  app:size="40dip"
  app:checked="false"
  app:stroke_width="2dp"
  app:enabled="true"/>
```
![](./example/checkbox.gif)

RadioButton
```
<com.nesprasit.design.RadioButton
    android:id="@+id/radio1"
    android:layout_width="50dip"
    android:layout_height="50dip"
    app:stroke_width="5dp"
    app:enabled="true"
    app:checked="false"/>
```

SwitchView
```
<com.nesprasit.design.SwitchView
    android:id="@+id/switch3"
    android:layout_width="80dip"
    android:layout_height="40dip"
    android:layout_marginBottom="20dp"
    app:enabled="true"
    app:checked="false"/>
```
## License
```
Copyright (C) 2020 Nesprasit

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
