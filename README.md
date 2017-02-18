# elog-banner-css
CSS style sheets for [elog](https://midas.psi.ch/elog/)

These 14 CSS stylesheets can be used to modify the default.css color of the sltab, title1, title2, and title3 elements of an
elog logbook, i.e., the title banner background-color.

## Usage
Place a copy in the your elog theme directory, for example (in ubuntu)

```bash
cd /usr/share/elog/themes/default
git clone https://github.com/ad3ller/elog-banner-css
```

To change the banner color for a given logbook to skyblue, add the following to the elog.conf file. 
```
CSS = elog-banner-css/skyblue.css
```

Supported colors:

black, blue, brown, coral, green, grey, lime, orange, purple, red, skyblue, teal, white, yellow.
