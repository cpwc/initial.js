# initial.js

[![Build Status](https://travis-ci.org/cpwc/initial.js.svg?branch=master)](https://travis-ci.org/cpwc/initial.js)

Simple jQuery plugin to make Gmail like text avatars for profile pictures.
Credits: Original plugin and author https://github.com/judesfernando/initial.js

## Browser compatibility

 - Chrome
 - Firefox
 - Opera 9+
 - Safari 3.2+
 - iOS Safari 3.2+
 - Android Browser 3+


 ## Usage

 ```html
 <img data-name="Steve" class="profile">
```

```js
$('.profile').initial();
```

## Options

**Below options can be overridden with data-attributes inside the image element. Refer to the "data-attribute" column for related data-attribute for each option**

| Option      | data-attribute   | Description                                                    | Default                                                                                            |
|-------------|------------------|----------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| name        | data-name        | Name of the user which the profile picture should be generated | Name                                                                                               |
| height      | data-height      | Height of the picture                                          | 100                                                                                                |
| width       | data-width       | Width of the picture                                           | 100                                                                                                |
| charCount   | data-char-count  | Number of characters to be shown in the picture.               | 1                                                                                                  |
| wordCount   | data-word-count  | Number of Words to be initialized in the picture.              | 2                                                                                                  |
| textColor   | data-text-color  | Color of the text                                              | #ffffff                                                                                            |
| fontSize    | data-font-size   | Font size of the character(s)                                  | 60                                                                                                 |
| fontWeight  | data-font-weight | Font weight of the character(s)                                | 400                                                                                                |
| radius      | data-radius      | Rounded corners                                                | 0                                                                                                  |
| seed        | data-seed        | Number to randomize the background color                       | 0                                                                                                  |
| src         | data-src         | Image url to load instead of initial text if available         | null                                                                                               |


### License

initial.js is [MIT licensed](./LICENSE). All credit to original [author and contributors](https://github.com/judesfernando/initial.js/graphs/contributors).
