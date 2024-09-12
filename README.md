# BadHUD

<p align="center">
  <a href="https://github.com/Starexify/BadHUD/issues"><img alt="GitHub Issues" src="https://img.shields.io/github/issues/Starexify/BadHUD?style=for-the-badge&color=96000C"></a>
  <a href="https://github.com/Starexify/BadHUD/blob/main/LICENSE"><img alt="GitHub License" src="https://img.shields.io/github/license/Starexify/BadHUD?style=for-the-badge&color=96000C"></a>
</p>

<p align="center">
    <strong>
        ⚠️Please note that this is a mod made in my freetime as a hobby so feedback would be much appreciated. If you encounter any UNKNOWN issues or anything else please let me know.
    </strong>
</p>

## ⚙️ Options

![Options](https://github.com/Starexify/Starexify/blob/main/resources/BadHUD/BadHUD-Options.png?raw=true)

Explanation for each:

-Show Judgements On Left - Just shows the Judgements (Sick, Good, Bad etc) in the left side of the screen

-Show Timer - Shows the time elapsed of the song in down-center of the screen

-Vertical Health Bar - Moves the Health Bar in right side of the screen

-Vertical Score Bar - Moves the Score in the left side of the screen (also adds combo counter)

(Look at mod images for better example of how they look)

- Accuracy - There are 3 accuracy types (Vanilla, Psych Engine, osu!mania) with each different methods of calculation

The calculations for accuracy are:

n = the total of notes in a chart

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mi>A</mi>
  <mi>c</mi>
  <mi>c</mi>
  <mi>u</mi>
  <mi>r</mi>
  <mi>a</mi>
  <mi>c</mi>
  <msub>
    <mi>y</mi>
    <mrow data-mjx-texclass="ORD">
      <mi>V</mi>
      <mi>a</mi>
      <mi>n</mi>
      <mi>i</mi>
      <mi>l</mi>
      <mi>l</mi>
      <mi>a</mi>
    </mrow>
  </msub>
  <mo>=</mo>
  <mn>100</mn>
  <mo>&#x2212;</mo>
  <mrow data-mjx-texclass="ORD">
    <mfrac>
      <mrow data-mjx-texclass="ORD">
        <mi>s</mi>
        <mi>h</mi>
        <mi>i</mi>
        <mi>t</mi>
        <mi>s</mi>
        <mo>+</mo>
        <mi>b</mi>
        <mi>a</mi>
        <mi>d</mi>
        <mi>s</mi>
        <mo>+</mo>
        <mi>m</mi>
        <mi>i</mi>
        <mi>s</mi>
        <mi>s</mi>
        <mi>e</mi>
        <mi>s</mi>
      </mrow>
      <mrow data-mjx-texclass="ORD">
        <mi>n</mi>
      </mrow>
    </mfrac>
  </mrow>
  <mo>&#xD7;</mo>
  <mn>100</mn>
</math>

<br>
<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mi>A</mi>
  <mi>c</mi>
  <mi>c</mi>
  <mi>u</mi>
  <mi>r</mi>
  <mi>a</mi>
  <mi>c</mi>
  <msub>
    <mi>y</mi>
    <mrow data-mjx-texclass="ORD">
      <mi>P</mi>
      <mi>s</mi>
      <mi>y</mi>
      <mi>c</mi>
      <mi>h</mi>
      <mi>E</mi>
      <mi>n</mi>
      <mi>g</mi>
      <mi>i</mi>
      <mi>n</mi>
      <mi>e</mi>
    </mrow>
  </msub>
  <mo>=</mo>
  <mn>100</mn>
  <mo>&#x2212;</mo>
  <mrow data-mjx-texclass="ORD">
    <mfrac>
      <mrow data-mjx-texclass="ORD">
        <mi>s</mi>
        <mi>i</mi>
        <mi>c</mi>
        <mi>k</mi>
        <mi>s</mi>
        <mi>&#xD7;</mi>
        <mn>0</mn>
        <mo>+</mo>
        <mi>g</mi>
        <mi>o</mi>
        <mi>o</mi>
        <mi>d</mi>
        <mi>s</mi>
        <mi>&#xD7;</mi>
        <mn>0.33</mn>
        <mo>+</mo>
        <mi>b</mi>
        <mi>a</mi>
        <mi>d</mi>
        <mi>s</mi>
        <mi>&#xD7;</mi>
        <mn>0.67</mn>
        <mo>+</mo>
        <mi>s</mi>
        <mi>h</mi>
        <mi>i</mi>
        <mi>t</mi>
        <mi>s</mi>
        <mi>&#xD7;</mi>
        <mn>1</mn>
      </mrow>
      <mrow data-mjx-texclass="ORD">
        <mi>n</mi>
      </mrow>
    </mfrac>
  </mrow>
  <mi>&#xD7;</mi>
  <mn>100</mn>
</math>

<br>
<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mi>A</mi>
  <mi>c</mi>
  <mi>c</mi>
  <mi>u</mi>
  <mi>r</mi>
  <mi>a</mi>
  <mi>c</mi>
  <msub>
    <mi>y</mi>
    <mrow data-mjx-texclass="ORD">
      <mi>o</mi>
      <mi>s</mi>
      <mi>u</mi>
      <mo>!</mo>
      <mi>m</mi>
      <mi>a</mi>
      <mi>n</mi>
      <mi>i</mi>
      <mi>a</mi>
    </mrow>
  </msub>
  <mo>=</mo>
  <mrow data-mjx-texclass="ORD">
    <mfrac>
      <mrow data-mjx-texclass="ORD">
        <mn>300</mn>
        <mi>&#xD7;</mi>
        <mi>s</mi>
        <mi>i</mi>
        <mi>c</mi>
        <mi>k</mi>
        <mi>s</mi>
        <mo>+</mo>
        <mn>200</mn>
        <mi>&#xD7;</mi>
        <mi>g</mi>
        <mi>o</mi>
        <mi>o</mi>
        <mi>d</mi>
        <mi>s</mi>
        <mo>+</mo>
        <mn>100</mn>
        <mi>&#xD7;</mi>
        <mi>b</mi>
        <mi>a</mi>
        <mi>d</mi>
        <mi>s</mi>
        <mo>+</mo>
        <mn>50</mn>
        <mi>&#xD7;</mi>
        <mi>s</mi>
        <mi>h</mi>
        <mi>i</mi>
        <mi>t</mi>
        <mi>s</mi>
      </mrow>
      <mrow data-mjx-texclass="ORD">
        <mn>300</mn>
        <mo stretchy="false">(</mo>
        <mi>s</mi>
        <mi>i</mi>
        <mi>c</mi>
        <mi>k</mi>
        <mi>s</mi>
        <mo>+</mo>
        <mi>g</mi>
        <mi>o</mi>
        <mi>o</mi>
        <mi>d</mi>
        <mi>s</mi>
        <mo>+</mo>
        <mi>b</mi>
        <mi>a</mi>
        <mi>d</mi>
        <mi>s</mi>
        <mo>+</mo>
        <mi>s</mi>
        <mi>h</mi>
        <mi>i</mi>
        <mi>t</mi>
        <mi>s</mi>
        <mo>+</mo>
        <mi>m</mi>
        <mi>i</mi>
        <mi>s</mi>
        <mi>s</mi>
        <mi>e</mi>
        <mi>s</mi>
        <mo stretchy="false">)</mo>
      </mrow>
    </mfrac>
  </mrow>
  <mi>&#xD7;</mi>
  <mn>100</mn>
</math>

## 🧩 Other Mods

I also recommend trying these mods for QoL Features aswell:

[Custom Scroll Speed](https://gamebanana.com/mods/511039)

[More Strums Options - Middlescroll and Lane Underlay](https://gamebanana.com/mods/519686)

[FunnyInputs - Ghost Tapping and better Input](https://gamebanana.com/mods/519072)

[Icon-Colored Health Bar](https://gamebanana.com/mods/511342)

[OG Psych Engine HUD](https://gamebanana.com/mods/511527)

## 🖼️ Examples

### Example without mods

![Example without mods](https://github.com/Starexify/Starexify/blob/main/resources/BadHUD/Example%20Simple.png?raw=true)

### Example with Middlescroll and Lane Opacity from More Strums Options

![Example with Middlescroll](https://github.com/Starexify/Starexify/blob/main/resources/BadHUD/Example%20with%20Middlescroll.png?raw=true)

## Known Issues

- In Chart Editor after you start and then close the song and then start again it stops working. (Basically there's no fix for that)
- The health icons bop is kynda buggy
- The combo starts at 0 instead of 1

## 📜 License

This mod is licensed under the MIT License, allowing for free use, modification, and distribution, meaning you can use my mod in your modpacks. For more details, please see the full license included with the mod.
