---
title: Solarized color theme
layout: default
---
# {{ page.title }}

## light

|SOLARIZED|HEX    |16/8|TERMCOL  |XTERM/HEX  |L*A*B     |RGB        |HSB       |
|:--------|-------|---:|:--------|----------:|---------:|----------:|---------:|
|base03   |#002b36| 8/4|brblack  |234 #1c1c1c|15 -12 -12|  0  43  54|193 100 21|
|base02   |#073642| 0/4|black    |235 #262626|20 -12 -12|  7  54  66|192  90 26|
|base01   |#586e75|10/7|brgreen  |240 #585858|45 -07 -07| 88 110 117|194  25 46|
|base00   |#657b83|11/7|bryellow |241 #626262|50 -07 -07|101 123 131|195  23 51|
|base0    |#839496|12/6|brblue   |244 #808080|60 -06 -03|131 148 150|186  13 59|
|base1    |#93a1a1|14/4|brcyan   |245 #8a8a8a|65 -05 -02|147 161 161|180   9 63|
|base2    |#eee8d5| 7/7|white    |254 #e4e4e4|92 -00  10|238 232 213| 44  11 93|
|base3    |#fdf6e3|15/7|brwhite  |230 #ffffd7|97  00  10|253 246 227| 44  10 99|
|yellow   |#b58900| 3/3|yellow   |136 #af8700|60  10  65|181 137   0| 45 100 71|
|orange   |#cb4b16| 9/3|brred    |166 #d75f00|50  50  55|203  75  22| 18  89 80|
|red      |#dc322f| 1/1|red      |160 #d70000|50  65  45|220  50  47|  1  79 86|
|magenta  |#d33682| 5/5|magenta  |125 #af005f|50  65 -05|211  54 130|331  74 83|
|violet   |#6c71c4|13/5|brmagenta| 61 #5f5faf|50  15 -45|108 113 196|237  45 77|
|blue     |#268bd2| 4/4|blue     | 33 #0087ff|55 -10 -45| 38 139 210|205  82 82|
|cyan     |#2aa198| 6/6|cyan     | 37 #00afaf|60 -35 -05| 42 161 152|175  74 63|
|green    |#859900| 2/2|green    | 64 #5f8700|60 -20  65|133 153   0| 68 100 60|

![light]({{ site.baseurl }}/assets/solarized-values-light.png)

solarized-light.css segment

{% highlight css %}
html {
  /* base2 - background highlights */
  background-color: #eee8d5;
  /* base00 - body text / default code /primary content */
  color: #657b83;
  margin: 1em;
}
body {
  /* base3 - background */
  background-color: #fdf6e3;
  margin: 0 auto;
  max-width: 23cm;
  border: 1pt solid #93a1a1;
  padding: 1em;
}
code {
  /* base2 - background highlights */
  background-color: #eee8d5;
  padding: 2px;
}
a {
  /* yellow */
  color: #b58900;
}
a:visited {
  /* orange */
  color: #cb4b16;
}
a:hover {
  /* orange */
  color: #cb4b16;
}
h1 {
  /* magenta */
  color: #d33682;
}
h2,
h3,
h4,
h5,
h6 {
  /* green */
  color: #859900;
}
pre {
  /* base3 - background */
  background-color: #fdf6e3;
  /* base00 - body text / default code /primary content */
  color: #657b83;
  /* base1 - comments / secondary content */
  border: 1pt solid #93a1a1;
  padding: 1em;
  /* base2 - background highlights */
  box-shadow: 5pt 5pt 8pt #eee8d5;
}
pre code {
  /* base3 - background */
  background-color: #fdf6e3;
}
{% endhighlight %}

## dark

|SOLARIZED|HEX    |16/8|TERMCOL  |XTERM/HEX  |L*A*B     |RGB        |HSB       |
|:--------|-------|---:|:--------|----------:|---------:|----------:|---------:|
|base03   |#002b36| 8/4|brblack  |234 #1c1c1c|15 -12 -12|  0  43  54|193 100 21|
|base02   |#073642| 0/4|black    |235 #262626|20 -12 -12|  7  54  66|192  90 26|
|base01   |#586e75|10/7|brgreen  |240 #585858|45 -07 -07| 88 110 117|194  25 46|
|base00   |#657b83|11/7|bryellow |241 #626262|50 -07 -07|101 123 131|195  23 51|
|base0    |#839496|12/6|brblue   |244 #808080|60 -06 -03|131 148 150|186  13 59|
|base1    |#93a1a1|14/4|brcyan   |245 #8a8a8a|65 -05 -02|147 161 161|180   9 63|
|base2    |#eee8d5| 7/7|white    |254 #e4e4e4|92 -00  10|238 232 213| 44  11 93|
|base3    |#fdf6e3|15/7|brwhite  |230 #ffffd7|97  00  10|253 246 227| 44  10 99|
|yellow   |#b58900| 3/3|yellow   |136 #af8700|60  10  65|181 137   0| 45 100 71|
|orange   |#cb4b16| 9/3|brred    |166 #d75f00|50  50  55|203  75  22| 18  89 80|
|red      |#dc322f| 1/1|red      |160 #d70000|50  65  45|220  50  47|  1  79 86|
|magenta  |#d33682| 5/5|magenta  |125 #af005f|50  65 -05|211  54 130|331  74 83|
|violet   |#6c71c4|13/5|brmagenta| 61 #5f5faf|50  15 -45|108 113 196|237  45 77|
|blue     |#268bd2| 4/4|blue     | 33 #0087ff|55 -10 -45| 38 139 210|205  82 82|
|cyan     |#2aa198| 6/6|cyan     | 37 #00afaf|60 -35 -05| 42 161 152|175  74 63|
|green    |#859900| 2/2|green    | 64 #5f8700|60 -20  65|133 153   0| 68 100 60|

![dark]({{ site.baseurl }}/assets/solarized-values-dark.png)

solarized-dark.css

{% highlight css %}
html {
  /* base02 - background highlights */
  background-color: #073642;
  /* base0 - body text / default code /primary content */
  color: #839496;
  margin: 1em;
}
body {
  /* base03 - background */
  background-color: #002b36;
  margin: 0 auto;
  max-width: 23cm;
  border: 1pt solid #586e75;
  padding: 1em;
}
code {
  /* base02 - background highlights */
  background-color: #073642;
  padding: 2px;
}
a {
  /* yellow */
  color: #b58900;
}
a:visited {
  /* orange */
  color: #cb4b16;
}
a:hover {
  /* orange */
  color: #cb4b16;
}
h1 {
  /* magenta */
  color: #d33682;
}
h2,
h3,
h4,
h5,
h6 {
  /* green */
  color: #859900;
}
pre {
  /* base03 - background */
  background-color: #002b36;
  /* base0 - body text / default code /primary content */
  color: #839496;
  /* base01 - comments / secondary content */
  border: 1pt solid #586e75;
  padding: 1em;
  /* base02 - background highlights */
  box-shadow: 5pt 5pt 8pt #073642;
}
pre code {
  /* base03 - background */
  background-color: #002b36;
}
{% endhighlight %}

## sumerize for light and dark solarized color

**for light, colors from light to dark**:

base3 -> base2 -> base1 -> base0 -> base00 -> base01 -> base02 -> base03,

body background is base3, body color is base00.

**for dark, colors from dark to light**:

base03 -> base02 -> base01 -> base00 -> base0 -> base1 -> base2 -> base3,

body background is base03, body color is base0.

**for both**:

h1 is megenta, h2~h6 are green.
megenta and green are suitable for either light or dark.

