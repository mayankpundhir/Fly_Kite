# Fly_Kite

Custom Layout for Zerodha's Kite Platform by using CSS files.

### Features

| CSS File              | Full Width    | Dark Theme    |
| --------------------- |:-------------:|:-------------:|
| **custom.css**        | **Yes**       | **Yes**       |
| custom_width.css      | Yes           | No            |
| custom_dark.css       | No            | Yes           |

Check Screenshots for comparison.


### Prerequisites

An extension to inject a css to a website.
You can use any extension as long as you can make it work.

Recommended on Chrome: [Injector](https://chrome.google.com/webstore/detail/injector/bfdonckegflhbiamlmidciapolfccmmb)


### Installing

1. Install Injector as told in prerequisite and (Download/Copy text of) one of the following css file.

      **Use custom.css if you don't know which one to download.**

      - [custom.css](https://github.com/mayankpundhir/Fly_Kite/blob/master/Css%20Files/custom.css): Changes BOTH max-width of site AND colors.(Applies both Features)

      - [custom_width.css](https://github.com/mayankpundhir/Fly_Kite/blob/master/Css%20Files/custom_width.css): Only changes max-width of site.

      - [custom_dark.css](https://github.com/mayankpundhir/Fly_Kite/blob/master/Css%20Files/custom_dark.css): Only changes site's color.

2. Open Injector and go under Snippets Tab > Create New snippet(+ sign) for domain ```kite.zerodha.com```. Check Screenshots > Install_Step2.png 
3. Copy paste whole css file(Around 16k lines) to editor and select Styles > CSS from dropdown. Check Screenshots > Install_Step3.png
4. Save the snippet and refresh Kite.

#### Recommended: Change Chrome Browser's Default Scrollbar

1. Open Chrome.
2. Go to ```chrome://flags/```.
3. Search '**Overlay Scrollbars**' and enable it.


### Settings Used

You can change following settings. Most of them can be change with Find and Replace because they are only present in custom css files. Some settings are used both in default and custom files. So replacing them will need a little css knowledge.

#### Check difference from default version of Kite's css file
Comparing file from default css and custom css will help. Check history to see difference of different custom css file on github.

#### Resolution

| Width             | Default   | Custom    | Find and Replace  |
| ----------------- |:---------:|:---------:|:-----------------:|
| Full Width        | 1366px    |1920px     | Yes               |
| Header-Left       | 401px     | 401px     | Yes               |
| Container-Left    | 400px     | 400px     | No                |
| Container-Right   | 966px     | 1520px    | Yes               |

#### Colors

Only used in custom css files:

Following colors are used only in custom files so you can Find and Replace.

**Gray 1**: #3a3a3a

**Gray 2**: #2a2a2a

**Gray 3**: #202020

**Blue**: #1188ff

**Purple**: #aa77ff

**Text Gray**: #a0a0a0a

Also used in default css file:

DO NOT Find and Replace. (Will effect default colors)

**Orange**: #ff5722

## License

This project is licensed under the WTFPL - see the [LICENSE.md](https://github.com/mayankpundhir/Fly_Kite/blob/master/License.md) file for details.

### Remove/ Temporarily Disable

All css data is stored in Injector Extension. Just remove snippet from the Injector or diable/ remove the Extension itself.
