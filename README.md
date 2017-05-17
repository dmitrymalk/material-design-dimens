# Material Design Dimens

[![Crates.io](https://img.shields.io/crates/l/rustc-serialize.svg?maxAge=2592000)]() [![Bintray](https://img.shields.io/bintray/v/asciidoctor/maven/asciidoctorj.svg?maxAge=2592000)](https://bintray.com/dmitrymalkovich/maven/material-design-dimens/view) [![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-Material%20Design%20Dimens-brightgreen.svg?style=flat)](http://android-arsenal.com/details/1/3675) [![Build Status](https://travis-ci.org/DmitryMalkovich/material-design-dimens.svg?branch=master)](https://travis-ci.org/DmitryMalkovich/material-design-dimens)

Default colors and dimens per [Material Design guidelines](https://www.google.com/design/spec/material-design/introduction.html) and [Android Design guidelines](https://developer.android.com/design/index.html) inside one library. 
 
## Dimens

**Pattern:**
```
R.dimen.material_[layout|component|typography]_[keylines|button|...]

R.color.material_[red|blue|...]_[500|800|...]
```
 
## Usage
Just add the dependency to your `build.gradle`:
```
compile 'com.dmitrymalkovich.android:material-design-dimens:1.4'
```

## Examples

#### Dialogs

<img width="600" src="https://material-design.storage.googleapis.com/publish/material_v_8/material_ext_publish/0Bzhp5Z4wHba3c3htV1IweVNKcFU/components_dialogs_updates1.png"/>

Name | Dimens | Values
------------ | ------------- | -------------
Padding around content area | `@dimen/material_component_dialogs_padding_around_content_area` | 24dp
Padding between title and body text | `@dimen/material_component_dialogs_padding_between_title_and_body_text` | 20dp
Padding around buttons | `@dimen/material_component_dialogs_padding_around_buttons` | 8dp
Action area height | `@dimen/material_component_dialogs_action_area_height` | 52dp
Dialog elevation | `@dimen/material_component_dialogs_elevation` | 24dp


#### Metrics & Keylines

<img width="300" src="https://material-design.storage.googleapis.com/publish/material_v_8/material_ext_publish/0B6Okdz75tqQseWRUbzJuUnpkNHM/layout_metrics_keyline_mobile2.png"/>

Name  | Dimens | Values
------------ | ------------- | -------------
Screen edge left and right margins | `@dimen/material_layout_keylines_screen_edge_margin` | 16dp
Content associated with an icon or avatar left margin | `@dimen/material_layout_keylines_content_left_margin_from_screen_edge` | 72dp
Horizontal margins on mobile | `@dimen/material_layout_keylines_horizontal_mobile_margin` | 16dp


#### Cards

<img width="600" src="https://material-design.storage.googleapis.com/publish/material_v_8/material_ext_publish/0Bzhp5Z4wHba3bElRc0xaZGR4S0E/components_cards20.png"/>

Name  | Dimens | Values
------------ | ------------- | -------------
Primary title top padding | `@dimen/material_component_cards_primary_title_top_padding` | 24dp
Primary title bottom padding | `@dimen/material_component_cards_primary_title_bottom_padding` | 16dp
Action button row padding | `@dimen/material_component_cards_action_button_row_padding` | 8dp
Supporting text top padding | `@dimen/material_component_cards_supporting_text_top_padding` | 16dp
Supporting text bottom padding | `@dimen/material_component_cards_supporting_text_bottom_padding` | 24dp


#### Floating Action Buttons

<img width="300" src="https://material-design.storage.googleapis.com/publish/material_v_8/material_ext_publish/0Bx4BSt6jniD7dkNVa080Ykd0ejg/patterns_actions_fab3.png"/>

Dimens | Values
------------- | -------------
 @dimen/material_component_floating_action_button_margin | 16dp
 @dimen/material_component_button_height | 36dp
 @dimen/material_component_button_touchable_target_height | 48dp


#### Color Palette

<img width="300" src="https://material-design.storage.googleapis.com/publish/material_v_8/material_ext_publish/0Bx4BSt6jniD7Ym1sRkstSzYtZmM/style_color_uiapplication_palette1.png"/>

Colors | Value
------------- | -------------
 @color/material_indigo_100 | #C5CAE9
 @color/material_indigo_500 | #3F51B5
 @color/material_indigo_700 | #303F9F

## Layout

* Keylines
* Spacing
* ... (More comming soon)

## Components

* Bottom sheets
* Buttons
* Floating Action Buttons
* Cards
* Dialogs
* Grid lists
* Lists
* Text fields
* Toolbars
* ... (More comming soon)

## Typography

* Font sizes

## Sample

* [Make Your App Material (XYZ reader)](https://github.com/DmitryMalkovich/make-your-app-material)

<img width="30%" vspace="20" hspace="20"  src="https://cloud.githubusercontent.com/assets/2931932/17039819/dd38d6c8-4fa4-11e6-9914-e25d8764a759.png" /> <img width="30%" vspace="20" hspace="20" src="https://cloud.githubusercontent.com/assets/2931932/17039818/dd386b98-4fa4-11e6-9e67-6a500ba7c209.png" /> <img width="60%" hspace="20" vspace="20" src="https://cloud.githubusercontent.com/assets/2931932/17039817/dd37f898-4fa4-11e6-8001-6105bda2cac9.png" />

## Contributing

Want to add your favorites dimens, just make pull request! 

### External contributors

* [FaizMalkani](https://github.com/FaizMalkani)
* [Jawnnypoo] (https://github.com/Jawnnypoo)

## License

Copyright 2016 Dmitry Malkovich

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
