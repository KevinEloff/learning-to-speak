## Learning to Speak and Hear Through Multi-Agent Communication over a Continuous Acoustic Channel

### eSpeak example audio
Here we give samples of [eSpeak](http://espeak.sourceforge.net/) generated audio, using eSpeak's internal phonetic descriptions. The text, phonetic description, and audio output are given. Our agents use eSpeak's phoneset, which we convert to IPA for display (using [lexconvert](http://ssb22.user.srcf.net/gradint/lexconvert.html)).

- "Hello World": `hələʊ wəːld`<br>
  <audio controls>
    <source src="assets/audio/hello_world.wav" type="audio/wav">
  </audio>

### Tacotron 2 + HiFi GAN example audio
Here we give samples of [Tacotron 2](https://github.com/NVIDIA/tacotron2) + [HiFi-GAN](https://github.com/jik876/hifi-gan) generated audio.

- "Hello World": `HH AH0 L OW1   W ER1 L D`<br>
  <audio controls>
    <source src="assets/audio/hello_world_taco.wav" type="audio/wav">
  </audio>

### Tacotron samples
Here we vary the first (s1) attribute and leave the other attributes constant

<!-- - Concept 0: `ggn.e:`<br> -->
- s1 = 0: `ɡoikiksss`<br>
  <audio controls>
    <source src="assets/audio/oikiksss.wav" type="audio/wav">
  </audio>
<!-- - Concept 1: `sikiksss`<br> -->
- s1 = 1: `sikiksss`<br>
  <audio controls>
    <source src="assets/audio/sikiksss.wav" type="audio/wav">
  </audio>
<!-- - Concept 2: `iikiksss`<br> -->
- s1 = 2: `iikiksss`<br>
  <audio controls>
    <source src="assets/audio/iikiksss.wav" type="audio/wav">
  </audio>
<!-- - Concept 3: `iiksssss`<br> -->
- s1 = 3: `iiksssss`<br>
  <audio controls>
    <source src="assets/audio/iiksssss.wav" type="audio/wav">
  </audio>

- s1 = 4: `aikkssss`<br>
  <audio controls>
    <source src="assets/audio/aikkssss.wav" type="audio/wav">
  </audio>

<!--
### Ungrounded two-concept audio samples

<table style="left: -50px; width: 120%; position: relative;">
  <tr>
    <td colspan="2" rowspan="2"></td>
    <th colspan="4">s1</th>
  </tr>
  <tr>
    <th>0</th>
    <th>1</th>
    <th>2</th>
    <th>3</th>
  </tr>
  <tr>
    <th rowspan="4">s2</th>
    <th>0</th>
    <td><code>nnʎɣɣx</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_00.wav" type="audio/wav">
      </audio>
    </td>
    <td><code>ðʎʎççç</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_10.wav" type="audio/wav">
      </audio>
    </td>
    <td><code>nsspxx</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_20.wav" type="audio/wav">
      </audio>
    </td>
    <td><code>nnssss</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_30.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
  <tr>
    <th>1</th>
    <td><code>jʎʎeee</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_01.wav" type="audio/wav">
      </audio>
    </td>
    <td><code>əəʀʀee</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_11.wav" type="audio/wav">
      </audio>
    </td>
    <td><code>wwwxxx</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_21.wav" type="audio/wav">
      </audio>
    </td>
    <td><code>sssəəə</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_31.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
  <tr>
    <th>2</th>
    <td><code>jjʎʎːː</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_02.wav" type="audio/wav">
      </audio>
    </td>
    <td><code>ðpʎʎjː</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_12.wav" type="audio/wav">
      </audio>
    </td>
    <td><code>ðwppçx</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_22.wav" type="audio/wav">
      </audio>
    </td>
    <td><code>enɣsss</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_32.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
  <tr>
    <th>3</th>
    <td><code>jjʎːːː</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_03.wav" type="audio/wav">
      </audio>
    </td>
    <td><code>ɣððpːː</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_13.wav" type="audio/wav">
      </audio>
    </td>
    <td><code>ɣjxxxp</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_23.wav" type="audio/wav">
      </audio>
    </td>
    <td><code>ɣssːːː</code><br>
      <audio controls style="width: 175px;">
        <source src="assets/audio/upred2_33.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
</table>-->

### Grounded one-word audio samples

<table>
  <tr>
    <th>Target word</th>
    <th>Ground truth</th>
    <th>Predicted phones</th>
  </tr>
  <tr>
    <td>Up</td>
<!--     <td><code>Vp</code><br> -->
    <td><code>ʌp</code><br>
      <audio controls>
        <source src="assets/audio/es_up.wav" type="audio/wav">
      </audio>
    </td>
<!--     <td><code>VvB</code><br> -->
    <td><code>ʌvb</code><br>
      <audio controls>
        <source src="assets/audio/pred_up.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
  <tr>
    <td>Down</td>
<!--     <td><code>daUn</code><br> -->
    <td><code>daʊn</code><br>
      <audio controls>
        <source src="assets/audio/es_down.wav" type="audio/wav">
      </audio>
    </td>
<!--     <td><code>daU</code><br> -->
    <td><code>daʊ</code><br>
      <audio controls>
        <source src="assets/audio/pred_down.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
  <tr>
    <td>Left</td>
<!--     <td><code>lEft</code><br> -->
    <td><code>lɛft</code><br>
      <audio controls>
        <source src="assets/audio/es_left.wav" type="audio/wav">
      </audio>
    </td>
<!--     <td><code>lE</code><br> -->
    <td><code>lɛ</code><br>
      <audio controls>
        <source src="assets/audio/pred_left.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
  <tr>
    <td>Right</td>
<!--     <td><code>raIt</code><br> -->
    <td><code>ɹaɪt</code><br>
      <audio controls>
        <source src="assets/audio/es_right.wav" type="audio/wav">
      </audio>
    </td>
<!--     <td><code>raISjn</code><br> -->
    <td><code>ɹaɪʃjəːn</code><br>
      <audio controls>
        <source src="assets/audio/pred_right.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
</table>
