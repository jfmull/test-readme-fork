# stress-test-README
Testing the capability of markdown-it & 

## test PDF
[test pdf.pdf](https://github.com/leehsihaumw/test-readme/files/15275556/test.pdf.pdf)

## test GIF
![giphy](https://github.com/leehsihaumw/test-readme/assets/151086072/9cb82a73-886f-4bb9-8e96-d5445d275811)

## test JPG
![henry-gt-dixon-sDuylE325TM-unsplash](https://github.com/leehsihaumw/test-readme/assets/151086072/eb377b1d-64a8-4031-b314-64b53aa058e6)

## test svg



# Some basic markdown syntax

## Emphasis
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

## Emojis
@octocat :+1: This PR looks great - it's ready to merge! :shipit:

## Alerts
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## Lists
### Unordered
- Item 1
  - Item 1a

### Ordered
1. Item 1
   1. Item 1a

## Code
`This is inline code`

### Code Blocks
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

## Subscript
This is a <sub>subscript</sub> text

## Superscript
This is a <sup>superscript</sup> text

## Links
This site was built using [GitHub Pages](https://pages.github.com/).

## Themed image
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

## diagrams
This is likely unsupported as it requires a few 3P tools:
https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams#creating-mermaid-diagrams

### flow chart
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

### GeoJSON
```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "id": 1,
      "properties": {
        "ID": 0
      },
      "geometry": {
        "type": "Polygon",
        "coordinates": [
          [
              [-90,35],
              [-90,30],
              [-85,30],
              [-85,35],
              [-90,35]
          ]
        ]
      }
    }
  ]
}
```

### TopoJSON
```topojson
{
  "type": "Topology",
  "transform": {
    "scale": [0.0005000500050005, 0.00010001000100010001],
    "translate": [100, 0]
  },
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "properties": {"prop0": "value0"},
          "coordinates": [4000, 5000]
        },
        {
          "type": "LineString",
          "properties": {"prop0": "value0", "prop1": 0},
          "arcs": [0]
        },
        {
          "type": "Polygon",
          "properties": {"prop0": "value0",
            "prop1": {"this": "that"}
          },
          "arcs": [[1]]
        }
      ]
    }
  },
  "arcs": [[[4000, 0], [1999, 9999], [2000, -9999], [2000, 9999]],[[0, 0], [0, 9999], [2000, 0], [0, -9999], [-2000, 0]]]
}
```

### STL 3D models
```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```

## Tables
| Header 1 | Header 2 |
| -------- | -------- |
| Row 1 Col 1 | Row 1 Col 2 |
| Row 2 Col 1 | Row 2 Col 2 |

## Blockquotes
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

## Escaping Characters
\*This text is not italic*\, and \*\*this text is not bold\*\*.

## Task Lists
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

## Footnotes
Here's a simple footnote,[^1] and here's a longer one.[^longnote]

[^1]: This is the first footnote.
[^longnote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

## Strikethrough
~~This was a mistake.~~

## Collapsed section
<details>

<summary>Tips for collapsed sections</summary>

### example header

```ruby
   puts "Hello World"
```

</details>

# LaTeX Examples README

This README file provides a collection of LaTeX examples that can be used in markdown documents to display mathematical expressions, equations, and more. LaTeX is a powerful tool for typesetting complex mathematical formulas and symbols.

## Table of Contents
- [Basic Syntax](#basic-syntax)
- [Mathematical Expressions](#mathematical-expressions)
  - [Inline Expressions](#inline-expressions)
  - [Display Expressions](#display-expressions)
- [Equations](#equations)
  - [Numbered Equations](#numbered-equations)
  - [Aligned Equations](#aligned-equations)
- [Symbols](#symbols)
  - [Greek Letters](#greek-letters)
  - [Operators](#operators)
- [Matrices](#matrices)

## Basic Syntax

LaTeX expressions can be included in markdown files by enclosing them in dollar signs (`$`). For inline expressions, use a single dollar sign (`$expression$`), and for display expressions, use double dollar signs (`$$expression$$`).

## Mathematical Expressions

### Inline Expressions
Example: The formula for the area of a circle is $A = \pi r^2$.

### Display Expressions
$$
E = mc^2
$$

## Equations

### Aligned Equations
$$
\begin{align}
a &= b + c \\
x &= y - z
\end{align}
$$

## Symbols

### Greek Letters
Example: $\alpha, \beta, \gamma, \Delta$

### Operators
Summation example: $\sum_{n=1}^{\infty} \frac{1}{n^2} = \frac{\pi^2}{6}$

## Matrices
$$
\begin{matrix}
a & b \\
c & d
\end{matrix}
$$

---

# g3305096 images rendering issue
| Type | Images |
| --- | --- |
| CMU | ![dataset_samples_CMU0](https://github.com/preethamam/AutomaticPanoramicImageStitching-AutoPanoStitch/assets/28588878/52abe23a-b44f-4891-9712-6a0bc3ab324e) |

## Test for badges
![GitHub top language](https://img.shields.io/github/languages/top/UniprJRC/FSDA)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/UniprJRC/FSDA)](https://github.com/UniprJRC/FSDA/releases/latest)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/UniprJRC/FSDA)
[![View FSDA on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/72999-fsda)
[![Documentation](https://img.shields.io/badge/HTML_Documentation-Mathworks_style-chocolate.svg)](http://rosa.unipr.it/FSDA/guide.html) 

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FUniprJRC%2FFSDA&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
[![CircleCI](https://circleci.com/gh/UniprJRC/FSDA.svg?style=svg)](https://circleci.com/gh/UniprJRC/FSDA)
[![Build Status](https://dev.azure.com/aldocorbellini0395/FSDA/_apis/build/status/UniprJRC.FSDA%20(1)?branchName=master)](https://dev.azure.com/aldocorbellini0395/FSDA/_build/latest?definitionId=2&branchName=master)
[![MATLAB](https://github.com/UniprJRC/FSDA/actions/workflows/ci.yml/badge.svg)](https://github.com/UniprJRC/FSDA/actions/workflows/ci.yml)

[![codecov](https://codecov.io/gh/UniprJRC/FSDA/branch/master/graph/badge.svg)](https://codecov.io/gh/UniprJRC/FSDA)
[![GitHub contributors](https://img.shields.io/github/contributors/UniprJRC/FSDA)](https://github.com/UniprJRC/FSDA/graphs/contributors)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/UniprJRC/FSDA/graphs/commit-activity)

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=UniprJRC/FSDA&project=FSDA.prj)

[![Testing Links](https://hacker.example.com/?u=https://github.com/UniprJRC/FSDA/actions/workflows/ci.yml/badge.svg)](https://www.google.com)

## Test for image resizing g2531455
This repository is used to test g2531455 for readme rewriting for File Exchange submissions.

Adding this line to see if I can update from Git on MATLAB Desktop

| Left Justified    | Centered       | Right Justified     |
|:--                |:--------------:|                  --:|
| Gauche            | Centre         | Droit               |

| Image Test        | Image Test     |  Image 40px tall    |
|:-----------------:|:--------------:|:-------------------:|
| 1234567           | 123456         | <a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" height="40px" /></a>|

| Image Test        | Image Test     |  Image -40px tall    |
|:-----------------:|:--------------:|:-------------------:|
| 1234567           | 123456         | <a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" height="-40px" /></a>|

| Image Test        | Image Test     | Image invalid height|
|:-----------------:|:--------------:|:-------------------:|
| 1234567           | 123456         | <a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" height="dummy-value" /></a>|

## Test for updated mailto links g2550628
[Test for Chandler](mailto:ccrane@mathworks.com)
[Test for Fake](mailto:fake@mathworks.com)

## Test for newlines in summary (update the summary with newlines) g2469144

# New Test for Height all in Style
### With height
<a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" style="height:745px;" /></a>

### With max-height
<a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" style="max-height:745px;" /></a>

### With height + max-height
<a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" style="max-height:745px;height:800px;"/></a>

### With neither
<a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png"/></a>

# New Test for Height outside of Style
### With height
<a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" height="723px" /></a>

### With max-height
<a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" max-height="745px" /></a>

### With height + max-height
<a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" max-height="760px" height="770px" /></a>

### With neither
<a href="http://swdownloads.analog.com/cse/toolboxes/trx/master/AnalogDevicesTransceiverToolbox_v20.2.1.mltbx"><img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png"/></a>
