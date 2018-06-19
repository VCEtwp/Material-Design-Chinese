<div class="article__intro">

[en]: <> (Applying color to UI)
# 将颜色应用于 UI

[en]: <> (Color is applied to UI elements and components in consistent and meaningful ways.)
译文 颜色以一致和有意义的方式应用于UI的元素和组件。

<nav>

[en]: <> (Usage)
[en]: <> (Top and bottom app bars)
[en]: <> (Backdrop)
[en]: <> (Sheets and surfaces)
[en]: <> (Buttons, chips and selection controls)
[en]: <> (Typography and iconography)
* [译文  用法](#usage)
* [译文  顶部和底部应用程序条](#top-bottom-app-bars)
* [译文  背景](#backdrop)
* [译文  纸张和表面](#sheets-surfaces)
* [译文  按钮、芯片和选择控件](#buttons-chips-selection-controls)
* [译文  印刷与肖像学](#typography-iconography)

</nav></div><div class="article__body">

[en]: <> (Usage)
<h2 id="usage">译文  用法</h2>

[en]: <> (These guidelines describe a variety of UI components and elements where color application is important.)
译文  这些指南描述了如果讲颜色应用于重要的各种UI组件以及元素。

[en]: <> (Principles)
### 原则

<div class="mdui-row-sm-3"><div class="mdui-col">

![]({assets_path}/color/applying-color-to-ui/color-illos-08.png)

[en]: <> (Consistent)
#### 一致性

[en]: <> (Color should be applied throughout a UI consistently and be compatible with the brand it represents.)
译文      颜色应该贯穿整个UI，并与它所代表的内容兼容。

</div><div class="mdui-col">

![]({assets_path}/color/applying-color-to-ui/color-illos-09.png)

[en]: <> (Distinct)
#### 区别性

[en]: <> (Color should create distinction between elements, with sufficient contrast between them.)
译文      颜色应该创造元素之间的区别，使得元素之间有足够的对比度。

</div><div class="mdui-col">
    
![]({assets_path}/color/applying-color-to-ui/color-illos-10.png)

[en]: <> (Intentional)
#### 目的性

[en]: <> (Color should be applied purposefully as it can convey meaning in multiple ways, such as relationships between elements and degrees of hierarchy.)
译文  颜色应该有目的地应用，因为它可以以多种方式传达意义，如元素之间的关系和等级。

</div></div>

[en]: <> (Top and bottom app bars)
<h2 id="top-bottom-app-bars">译文  顶部和底部应用程序条</h2>

[en]: <> (The way color is applied to top and bottom app bars helps users identify them and understand their relationship to surrounding UI elements.)
译文    颜色应用于顶部和底部应用程序条以帮助用户识别它们并理解它们与周围UI元素之间的关系。

[en]: <> (Identifying app bars)
### 译文  识别程序程序条

[en]: <> (Top and bottom app bars use an app’s primary color. System bars can use a dark or light variant of the primary color to separate system content from top app bar content.)
译文 顶部和底部应用程序条使用一个应用程序的原色。系统条可以使用主色调的深色或浅变，将系统内容与顶部应用程序栏内容区别开来。

<figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-bars-differentiating-baseline.png)

<figcaption>

{do}

[en]: <> (The primary color \(purple 500\) is used on this top app bar, and a dark primary variant \(purple 700\) is used on the system bar.)
译文  主色（紫色500）用于这个顶部应用程序条，在系统栏上使用一个黑色主变量（紫色700）。

</figcaption></figure>

[en]: <> (To emphasize the difference between app bars and other surfaces, use a secondary color on nearby components such as the FAB.)
译文  为了强调应用程序栏和其他内容之间的差异，应该在附近的组件（比如浮动动作按钮）上应用不一样的颜色。

<figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-bars-differentiating-reply.png)

<figcaption>

{do}

[en]: <> (The primary color \(blue 700\) is used on this bottom app bar, and the secondary color \(orange 500\) is used on the floating action button.)
译文  底部应用程序条使用了主色（蓝色700），则浮动动作按钮应该使用不同的颜色（橙色500）。

</figcaption></figure><figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-bars-differentiating-caution-1.png)

<figcaption>

{caution}

[en]: <> (If the bottom app bar and floating action button are the same color, use shadow or alternate means to create enough distinction between them.)
译文  如果底部应用程序条和浮动动作按钮的颜色是相同的，则使用阴影或替换来使他们更好区分。

</figcaption></figure>
on scroll the 
[en]: <> (Blending an app bar with the background)
### 译文  将应用程序条与背景混合

[en]: <> (When an app’s top or bottom app bar color is the same color as the background color, they blend together, placing emphasis on an app’s content instead of its structure.)
译文  当应用程序的顶部或底部应用程序条颜色与背景颜色相同时，它们将混合在一起，就可以使应用程序的内容更加明显而不是其结构。

<figure><video controls loop muted preload="metadata" class="mdui-video-fluid">
<source data-src="{assets_path}/color/applying-color-to-ui/color-applyingcolorui-blendedbars-fortnightly-1a-v1.mp4" src="{assets_path}/color/applying-color-to-ui/color-applyingcolorui-blendedbars-fortnightly-1a-v1.mp4" type="video/mp4">
</video><figcaption>

[en]: <> (Both this app’s top app bar color and background color is the primary color: white. However, on scroll the top app bar gains a shadow, showing it has an elevation higher than the content that scrolls behind it.)
译文  这个应用程序的顶部应用程序条颜色和背景颜色都使用了主色（白色）。但是顶部应用程序栏有一个阴影，使得看起来它的高度要高于其背后的内容。

</figcaption></figure><figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-blendedbars-owl.png)

<figcaption>

[en]: <> (This app’s bright, seamless layout uses it’s primary blue \(blue 700\) color for app bars, bottom navigation, and the background color, so individual elements stand out less, and content stands out more. The activation state uses the secondary yellow. It includes a shadow on the bottom navigation to show the elevation division between surfaces.)
译文  这个应用程序的明亮，无缝布局使用它的主蓝（蓝色700）颜色的应用程序条，底部导航，和背景颜色，因此个别元素脱颖而出，内容突出。激活状态使用次级黄色。它包括底部导航上的阴影，以显示表面之间的高度分割。

</figcaption></figure>

[en]: <> (Backdrop)
<h2 id="backdrop">译文</h2>

[en]: <> (A backdrop has a front and back layer. To distinguish between these two layers, the baseline back layer color is your primary color and the baseline front layer is white.)
译文  背景有前、后两层。为了区分这两层，基线后层颜色是你的主要颜色，基线前层是白色的。

<figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-surfaces-surfaceelevations-crane.png)

<figcaption>

[en]: <> (This app uses its primary color \(purple 800\) on the backdrop’s back layer. The text fields are a light primary variant \(purple 700\). A secondary color \(red 700\) is applied as an accent to the flight fares.)
译文  这个应用程序使用它的基色（紫色800）在背景的背面层。文本字段是一个光主变量（紫色700）。第二种颜色（红色700）被用作飞机票价的重音。

</figcaption></figure><figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-surfaces-surfaceelevations-shrine.png)

<figcaption>

[en]: <> (This app uses the primary color \(pink 100\) for the backdrop’s back layer and the primary dark primary variant \(pink 900\) for typography and iconography. Additionally, the secondary color \(pink 50\) is used for the expanding sheet on the front layer.)
译文  这个应用程序使用了底色背面的原色（粉色100）和主要的暗原色变体（粉红色900）用于排版和图像。此外，二次色（粉红色50）用于前层上的膨胀片材。

</figcaption></figure>


[en]: <> (Sheets and surfaces)
<h2 id="sheets-surfaces">译文</h2>

[en]: <> (The baseline color for sheets and surfaces, such as bottom sheets, navigation drawers, menus, dialogs, and cards is white. These components can incorporate color to create contrast between other surfaces. Contrast can make surface edges apparent, indicating elevation differences when surfaces overlap.)
译文  纸张和表面的底色，如底片、导航抽屉、菜单、对话框和卡片都是白色的。这些组件可以合并颜色以创建其他表面之间的对比度。对比度可以使表面边缘明显，指示表面重叠时的高程差异。

<figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-surfaces-baseline-alt.png)

<figcaption>

[en]: <> (This product has changed the default white to a primary color in a bottom sheet and the navigation drawer.)
译文  这个产品已经改变了默认的白色到底色和导航抽屉中的原色。

[en]: <> (This product uses a primary color \(purple 500\) in part of the bottom sheet instead of the baseline white.)
[en]: <> (This product’s navigation drawer uses its primary color \(purple 500\) instead of the baseline white.)
* 译文  该产品使用原色（紫色500）在部分底片而不是基线白色。
* 译文  该产品的导航抽屉使用其原色（紫色500）代替基线白色。

</figcaption></figure>

[en]: <> (Modal sheets)
### 译文  形式单

[en]: <> (Use contrasting colors on surfaces that appear on-screen temporarily, such as navigation drawers and bottom sheets. Usually these surfaces are white, but you can use your app’s primary or secondary color.)
译文  使用对比颜色，显示在屏幕上暂时的表面，如导航抽屉底板。通常这些表面是白色的，但你可以使用你的应用程序的主要或次要的颜色。

<figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-surfaces-tempsurfaces-reply.png)

<figcaption>

[en]: <> (This app uses its primary color blue \(blue 700\) on the bottom navigation drawer, a primary dark variant \(blue 800\) for the account switcher, and a secondary color \(orange 500\) for selection.)
译文  这个应用程序使用它的主色蓝色（蓝色7000）在底部导航抽屉中，一个主暗变型（蓝色800）的帐户切换器，和二次色（橙色500）的选择。

</figcaption></figure><figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-surfaces-tempsurfaces-fortnightly.png)

<figcaption>

[en]: <> (This app uses its primary color \(white\) for its modal navigation drawer, creating the maximum contrast between the dark typography and the navigation. A white scrim is used to make content behind it less noticeable, as the navigation drawer is the same color as the background.)
译文  这个应用程序使用它的原色（白色）作为它的模态导航抽屉，创造了深色排版和导航之间的最大对比。白色的文稿用来使后面的内容不那么明显，因为导航抽屉与背景颜色相同。

</figcaption></figure><figure>
<video controls loop muted preload="metadata" class="mdui-video-fluid">
<source data-src="{assets_path}/color/applying-color-to-ui/tempsurfaces-owl-1a.mp4" src="{assets_path}/color/applying-color-to-ui/tempsurfaces-owl-1a.mp4" type="video/mp4">
</video><figcaption>

[en]: <> (This app displays a sheet in the bottom right, colored with its primary color \(pink 500\). Upon tap, the sheet expands.)
译文  这个应用程序在右下角显示一张纸，用它的原色（粉红色500）着色。在敲击时，纸张膨胀。

</figcaption></figure>

[en]: <> (Cards)
### 译文 卡 

[en]: <> (The baseline color for cards is white. This color can be customized to express brand or to improve legibility. Card text and icons can also use the color theme to improve legibility.)
译文  卡片的底色是白色的。这种颜色可以定制来表达品牌或提高易读性。卡片文字和图标也可以使用颜色主题来提高易读性。

<figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-surfaces-cards-baseline.png)

<figcaption>

[en]: <> (The surfaces of these cards use the primary color \(purple 500\). The app’s background color is white. The secondary color \(teal 200\) is used for data visualization.)
译文  这些卡片的表面使用原色（紫色500）。应用程序的背景颜色是白色的。二次色（TEAL 200）用于数据可视化。

</figcaption></figure><figure><video controls loop muted preload="metadata" class="mdui-video-fluid">
<source data-src="{assets_path}/color/applying-color-to-ui/interaction-baseline-1a.mp4" src="{assets_path}/color/applying-color-to-ui/interaction-baseline-1a.mp4" type="video/mp4">
</video><figcaption>

[en]: <> (Cards can inherit color to showcase selection or importance.)
译文  卡片可以继承颜色来展示选择或重要性。

</figcaption></figure><div class="mdui-row-sm-2"><div class="mdui-col">

[en]: <> (When a card’s text and icons appear in front of imagery, they can be difficult to read. To improve legibility, you can use color to create a surface for text and icons.)
译文  当卡片的文字和图标出现在图像前面时，它们很难阅读。为了提高易读性，可以使用颜色创建文本和图标的表面。

</div><div class="mdui-col"><figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-surfaces-cards-legibility-baseline-1a.png)

<figcaption>

[en]: <> (This card uses a colorful scrim to ensure text remains legible.)
译文  这张卡片使用彩色的文稿来确保文字清晰易懂。

</figcaption></figure></div></div>

[en]: <> (Buttons, chips and selection controls)
<h2 id="buttons-chips-selection-controls">译文</h2>

[en]: <> (Buttons, chips and selection controls can be emphasized by applying your primary or secondary color to them.)
译文  按钮、芯片和选择控件可以通过将主色或次色应用于它们来强调。

[en]: <> (Color categories)
#### 译文  颜色类别

[en]: <> (The baseline color for contained, text and outlined buttons is your *primary color*.)
[en]: <> (The baseline color for floating action buttons and extended floating action buttons is your *secondary color*.)
[en]: <> (The baseline color for selection controls is your *secondary color*.)
* 译文  包含颜色、文本和轮廓按钮的基线颜色是你的*原色*。
* 译文  浮动动作按钮的基线颜色和扩展的浮动动作按钮是你的第二颜色*。
* 译文  选择控件的基线颜色是您的第二颜色*。

<figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-inputselectioncontrols-baseline.png)

<figcaption>

[en]: <> (The color theme for this app consists of a primary color \(purple 500\) with a primary dark variant \(purple 600\) and a secondary color \(teal 200\).)
译文  这个应用程序的主题颜色由一个主要颜色（紫色500）与原发暗变\（紫色600）和次要颜色（绿色200）。

[en]: <> (This product uses the primary color \(purple 500\) for the bottom app bar and the secondary color \(teal 200\) as an accent for the floating action button and selection controls.)
[en]: <> (This product uses the secondary color \(teal 200\) as an accent for selected list items.)
* 译文  该产品使用基色（紫色500）用于底部应用条和二次色（TEAL 200）作为浮点动作按钮和选择控件的重音。
* 译文  该产品使用第二颜色（TEAL 200）作为选定列表项目的重音。

</figcaption></figure>

[en]: <> (Buttons, chips, and selection controls)
### 译文  按钮、芯片和选择控件

[en]: <> (Buttons, chips, and selection controls can be emphasized with your primary or secondary colors.)
译文  按钮、芯片和选择控件可以用主色或次色来强调。

<figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-inputselectioncontrols-buttonschips-shrine.png)

<figcaption>

[en]: <> (This app uses its primary color \(pink 100\) for its extended floating action button and chips. It uses its primary dark variant \(pink 900\) for the slider.)
译文  这个应用程序使用它的原色（粉红色100）作为扩展的浮动动作按钮和筹码。它使用其主暗变量（粉红色900）的滑块。

</figcaption></figure><div class="mdui-row-sm-2"><div class="mdui-col"><figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-inputselectioncontrols-buttonschips-dont-crane.png)

<figcaption>

{do}

[en]: <> (Selection controls can inherit your app’s secondary color.)
译文  选择控件可以继承应用程序的第二颜色。

</figcaption></figure></div><div class="mdui-col"><figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-inputselectioncontrols-buttonschips-do-crane.png)

<figcaption>

{dont}

[en]: <> (Don’t use one of your brand colors for coloring alerts. This will help it stand out.)
译文  不要用你的品牌颜色来着色警报。这将帮助它脱颖而出。

</figcaption></figure></div></div>

[en]: <> (Floating action button \(FAB\))
### 译文  浮动动作按钮（FAB）

[en]: <> (The floating action button \(FAB\) should be one of the most recognizable items on your screen.)
译文  浮动动作按钮（FAB）应该是屏幕上最容易识别的项目之一。

[en]: <> (Use color to create contrast between the FAB and surrounding elements, such as the app bar. Your secondary color is the baseline color for use on the FAB. If your canvas uses many colors, your FAB can use monochromatic coloring instead, to stand out from the content.)
译文  使用颜色来创建Fab和周围元素之间的对比，例如应用程序条。你的次要颜色是在Fab上使用的底色。如果您的画布使用多种颜色，您的Fab可以使用单色着色，而不是从内容中脱颖而出。

<figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-inputselectioncontrols-fab-reply.png)

<figcaption>

[en]: <> (This app’s secondary color \(orange 500\) is applied to the FAB, contrasting it from the surrounding UI.)
译文  这个程序的第二颜色（橙色500）应用于工厂，对比于周围的UI。

</figcaption></figure><figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-inputselectioncontrols-fab-posivibes.png)

<figcaption>

[en]: <> (This app’s color theme uses a primary white and a secondary black for all buttons, selection controls, and iconography. These components stand out because they contrast with the vivid, multicolor content.)
译文  这个应用程序的颜色主题使用一个主要的白色和二级黑色的所有按钮，选择控件，和图像。这些组件之所以突出，是因为它们与生动、多色的内容形成鲜明对比。

</figcaption></figure>

[en]: <> (Typography and iconography)
<h2 id="typography-iconography">译文  印刷与肖像学</h2>

[en]: <> (Color can express whether text has greater, or lesser, importance relative to other text. Color also ensures text remains legible when placed above imagery or backgrounds, which can make it difficult to read the text in front of them.)
译文  颜色可以表示文本相对于其他文本是否具有更大或更小的重要性。颜色也确保文本保持清晰，当放置在图像或背景之上，这使得很难阅读前面的文本。

[en]: <> (Typographic hierarchy)
### 译文  排版层次

[en]: <> (Color can increase both text’s visibility and its level of importance.)
译文  颜色可以增加文本的可见性和重要性水平。

<figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-typography-baseline-alt.png)

<figcaption>

[en]: <> (The color theme for this app consists of a primary color \(purple 500\) and a secondary color \(orange 600\). Orange accents the card’s headlines, and purple appears on tabs and buttons.)
译文  这个应用程序的颜色主题由原色（紫色500）和第二颜色（橙色600）组成。橙色强调卡片的标题，紫色出现在标签和按钮上。

</figcaption></figure>

[en]: <> (Headlines and tabs)
### 译文  标题和标签

[en]: <> (Important text, like tabs and headlines, can use your primary or secondary color.)
译文  重要的文本，如标签和标题，可以使用您的主要或次要颜色。

<figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-typography-headlinetabs-basil-1.png)

<figcaption>

[en]: <> (This app uses its secondary color \(orange 800\) to accent and call attention to the headlines.)
译文  这个应用程序使用它的二次色（橙色800）来强调并唤起人们对标题的关注。

</figcaption></figure><figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-typography-headlinetabs-basil-2.png)

<figcaption>

[en]: <> (This app uses its primary color \(green 800\) for tabs, with weight changes indicating selected and unselected states.)
译文  这个应用程序使用它的主色（绿色800）作为标签，重量变化表明选择和未选择的状态。

</figcaption></figure><div class="mdui-row-sm-2"><div class="mdui-col"><figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-typography-headlinetabs-do-owl-1.png)

<figcaption>

{do}

[en]: <> (Use your primary or secondary color to emphasize shorter text, such as headlines.)
译文  使用初级或次要颜色来强调较短的文本，如标题。

</figcaption></figure></div><div class="mdui-col"><figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-typography-headlinetabs-do-owl-2.png)

<figcaption>

{do}

[en]: <> (You can use your primary or secondary color to accent links.)
译文  您可以使用主色调或次色来强调链接。

</figcaption></figure></div></div><figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-typography-headlinetabs-caution-owl-1.png)

<figcaption>

{caution}

[en]: <> (Avoid using bright primary or secondary colors for body text.)
译文  避免使用明亮的主或次要颜色的正文。

</figcaption></figure>

[en]: <> (Text legibility)
### 译文  文本易读性

[en]: <> (When text is placed above imagery, it often leads to legibility issues. Creating a colored layer between text and image can ensure text remains legible.)
译文  当文本放置在图像之上时，它往往导致易读性问题。在文本和图像之间创建彩色层可以确保文本仍然清晰易懂。

<figure>

![]({assets_path}/color/applying-color-to-ui/textlegibility-posivibes-2.png)

<figcaption>

[en]: <> (This app applies a yellow scrim above imagery to ensure text above it is legible.)
译文  这个应用程序在图像上面应用黄色的文字，以确保上面的文字清晰易懂。

</figcaption></figure>

[en]: <> (Icons)
### 译文  图标

[en]: <> (Icons help identify actions and provide information. Their color should contrast against the background to ensure that they are legible and identifiable.)
译文  图标有助于识别动作并提供信息。它们的颜色应与背景对比，以确保它们清晰易懂。

<figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-inputselectioncontrols-icons-basil.png)

<figcaption>

[en]: <> (This app uses both its primary color \(green 800\) and secondary color \(orange 800\) for its icons.)
译文  这个应用程序使用它的主色（绿色800）和二次色（橙色800）的图标。

</figcaption></figure><figure>

![]({assets_path}/color/applying-color-to-ui/color-applyingcolorui-inputselectioncontrols-icons-shrine.png)

<figcaption>

[en]: <> (Shrine uses its primary dark variant \(pink 900\) for icons.)
译文  神龛使用它的主要暗变型（粉红色900）作为图标。

</figcaption></figure></div>
