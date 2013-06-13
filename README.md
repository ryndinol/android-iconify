![Alt](https://raw.github.com/JoanZapata/android-iconify/master/screenshot.png)

**Iconify** is a single JAR, you can download it [here](http://search.maven.org/remotecontent?filepath=com/joanzapata/android/android-iconify/1.0.0/android-iconify-1.0.0.jar), it's available on **Maven Central**:

```xml
<dependency>
    <groupId>com.joanzapata.android</groupId>
    <artifactId>android-iconify</artifactId>
    <version>1.0.0</version>
</dependency>
```

## Programmatically

```xml
<TextView
    android:id="@+id/iconTextView"
    android:text="Iconify this {icon_star} !"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content" />
```

> You can use any icon from [FontAwesome 3.1.1](http://fortawesome.github.io/Font-Awesome/icons/)

```java
Iconify.addIcons(iconTextView);
```

> Syntax is inspired from [Linkify](http://developer.android.com/reference/android/text/util/Linkify.html).

![Alt](https://raw.github.com/JoanZapata/android-iconify/master/iconify-this.png)


## From XML

```xml
<IconTextView
    android:id="@+id/icon"
    android:text="Iconify this {icon_star} !"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content" />
```

It works the same way for anything that extends TextView, so you can put icons in your buttons too.

```xml
<IconButton
    android:id="@+id/icon"
    android:text="{icon_edit} Edit"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content" />
```

![Alt](https://raw.github.com/JoanZapata/android-iconify/master/edit.png)

## License

```
Copyright 2013 Joan Zapata

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

It uses FontAwesome font, licensed under OFL 1.1, which is compatible
with this library's license.

    http://scripts.sil.org/cms/scripts/render_download.php?format=file&media_id=OFL_plaintext&filename=OFL.txt
    
```
