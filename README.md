# Vivid Syntax   ////  Atom Syntax Theme

![Vivid main
screenshot](https://www.dropbox.com/s/9ftemviukkpgafb/Screenshot%202017-02-08%2014.04.16.png?dl=1)


This dark syntax theme sports a subtle, deep purple base with vivid candy-like colors which bring your syntax to life without going too far to the point of being impractical.

#### Recommended Settings:

* **UI Theme:**  **[Atom Material UI](https://atom.io/themes/atom-material-ui)** or **[One Dark](https://github.com/atom/one-dark-ui)**

* **Font size:** 13-14px depending on resolution.

* **Font Family:** Source Code Pro


## Calibrate

By default, the brightness, saturation, and contrast are lowered a bit so you can calibrate for your monitor. To do so, add the following into your user stylesheet (Atom > Stylesheet):

```less
atom-text-editor .line > .syntax--source {
  -webkit-filter: saturate(90%) brightness(80%) contrast(90%);
}
```
The above values will do nothing since they are the default values. Try increasing/decreasing each to your liking.


# Language Previews

### Javascript:
![JS Screenshot](https://www.dropbox.com/s/k16waf5hwbbyj4h/Screenshot%202015-07-25%2022.49.41.png?dl=1)

### Coffeescript:
![Coffeescript Screenshot](https://www.dropbox.com/s/j3v86tzekwbx9ie/Screenshot%202015-07-26%2012.19.55.png?dl=1)

### MeteorJS (w/ tree view styling enabled)
![Meteor Screenshot](https://www.dropbox.com/s/v3jowyau6q1dtt1/Screenshot%202015-07-26%2012.48.00.png?dl=1)

### Spacebars:
![Spacebars](https://s3.amazonaws.com/f.cl.ly/items/3J070V2h070X182c3F1R/Image%202015-05-01%20at%207.42.33%20PM.png)

### Jasmine:
![Jasmine
Screenshot](https://s3.amazonaws.com/f.cl.ly/items/2P453t1f2E250B1u2U3c/Image%202015-05-26%20at%209.46.57%20PM.png)

**Note:** To get Jasmine colors to work you need to:
  1.  name your files `someFile.spec.js`
  2.  make sure you have [file types](https://atom.io/packages/file-types) installed
  3.  add the following in your config:

      ```coffee
      "file-types":
        "^[^.]+.js$": "source.js"
        ".spec.js$": "source.spec.js"
      ```
* I've noticed that opening the settings panel for this package will mess up current settings that use regex, so try to only edit this setting via File > Open your config.

### CSS/SASS/LESS:
![CSS](https://s3.amazonaws.com/f.cl.ly/items/2Q1H1W2R3o2F0C2b043K/Image%202015-05-01%20at%207.41.18%20PM.png)

### HTML:
![HTML Screenshot](https://s3.amazonaws.com/f.cl.ly/items/0L3E1F1F1r3G2y242a0E/Image%202015-05-01%20at%207.39.59%20PM.png)
