# CardListItem

[![](https://jitpack.io/v/sandisetiawan444/CardListItem.svg)](https://jitpack.io/#sandisetiawan444/CardListItem)

Custom list item with CardView

![alt text](https://firebasestorage.googleapis.com/v0/b/cardlistitem.appspot.com/o/images%2FScreenshot_2018-08-01-09-03-44-024_com.cardlistitem.cardlistitem.png?alt=media&token=15c01d35-3a5c-45c6-81e8-225759f696f0)

![alt text](https://firebasestorage.googleapis.com/v0/b/cardlistitem.appspot.com/o/images%2FScreenshot_2018-08-01-09-05-15-899_com.cardlistitem.cardlistitem.png?alt=media&token=3a999dac-0b40-469e-89ed-62596c22dbcd)

![alt text](https://firebasestorage.googleapis.com/v0/b/cardlistitem.appspot.com/o/images%2FScreenshot_2018-08-01-09-09-13-692_com.cardlistitem.cardlistitem.png?alt=media&token=af7c03fa-9b1e-4261-8b47-6f7549856786)

![alt text](https://firebasestorage.googleapis.com/v0/b/cardlistitem.appspot.com/o/images%2FScreenshot_2018-08-01-09-10-40-673_com.cardlistitem.cardlistitem.png?alt=media&token=9d0b0446-74c4-4552-bf9d-ed9d1ee0f539)

![alt text](https://firebasestorage.googleapis.com/v0/b/cardlistitem.appspot.com/o/images%2FScreenshot_2018-08-01-09-02-45-030_com.cardlistitem.cardlistitem.png?alt=media&token=2fdbff97-62e8-4d59-a934-0377ab0a32ad)

## Getting Started

### Installing

Step 1. Add the JitPack repository in your root build.gradle at the end of repositories:

```
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```

Step 2. Add the dependency

```
dependencies {
    implementation 'com.github.sandisetiawan444:CardListItem:1.0.1'
}
```

Include the CardListItem widget in your layout

```
<com.cardlistitem.cardlistitemlibrary.CardListItem
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_marginLeft="4dp"
    android:layout_marginRight="4dp"
    app:cardCornerRadius="10dp"
    app:cardUseCompatPadding="true"
    app:contentShortDescription="Short description"
    app:contentTitle="Title"
    app:headerTitle="Name"
    app:timestampt="1 hour ago" />
```

## Views

There are several views you can access:

| Method | Description |
|---|---|
| headerToolbar | android.support.v7.widget.Toolbar. Contains headerImageView and headerTitleTextView |
| headerImageView | CircleImageView |
| headerTitleTextView | TextView. headerToolbar will disappear if not set |
| contentImageView | SquareImageView |
| contentTitleTextview | This TextView will disappear if not set |
| contentShortDescriptionTextView | This TextView will disappear if not set |
| contentTextLayout | LinearLayout |
| timestamptTextView | This TextView will disappear if not set |

## Methods & Attributes

| Method & Attribute | Description |
|---|---|
| headerImageSrc | Get or set headerImageView image resource |
| headerTitle | Get or set headerTitleTextView text value |
| contentImageSrc | Get or set contentImageView resource |
| contentImageVisibility | Set visibiliy of contentImageView. If set to gone, the image will disappear |
| contentTitle | Get or set contentTitleTextview text value |
| contentShortDescription | Get or set contentShortDescriptionTextView text value. Maximum of two lines of text |
| timestampt | Get or set timestamptTextView text value |

## License

    Copyright 2018 Sandi Setiawan

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
