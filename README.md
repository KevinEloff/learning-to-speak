## Learning to Communicate

### eSpeak example audio
Here we give samples of [eSpeak](http://espeak.sourceforge.net/) generated audio, using eSpeak's internal phonetic descriptions. The text, phonetic description, and audio output are given.

- "Hello World": `h@loUw3:ld`<br>
  <audio controls>
    <source src="assets/audio/hello_world.wav" type="audio/wav">
  </audio><br>
- "Up": `Vp`<br>
  <audio controls>
    <source src="assets/audio/es_up.wav" type="audio/wav">
  </audio><br>
- "Down": `daUn`<br>
  <audio controls>
    <source src="assets/audio/es_down.wav" type="audio/wav">
  </audio><br>
- "Left": `lEft`<br>
  <audio controls>
    <source src="assets/audio/es_left.wav" type="audio/wav">
  </audio><br>
- "Right": `raIt`<br>
  <audio controls>
    <source src="assets/audio/es_right.wav" type="audio/wav">
  </audio>

### Ungrounded single-concept audio samples

- Concept 0: `VtSXx`<br>
  <audio controls>
    <source src="assets/audio/hello_world.wav" type="audio/wav">
  </audio><br>
- Concept 1: `aUllC`<br>
  <audio controls>
    <source src="assets/audio/hello_world.wav" type="audio/wav">
  </audio><br>
- Concept 2: `test`<br>
  <audio controls>
    <source src="assets/audio/hello_world.wav" type="audio/wav">
  </audio><br>
- Concept 3: `test`<br>
  <audio controls>
    <source src="assets/audio/hello_world.wav" type="audio/wav">
  </audio>

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
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
  <tr>
    <th>1</th>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
  <tr>
    <th>2</th>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
  <tr>
    <th>3</th>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
    <td>
      <audio controls style="width: 175px;">
        <source src="assets/audio/hello_world.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
</table>

### Grounded one-word audio samples

<table>
  <tr>
    <th>Target word</th>
    <th>Ground truth</th>
    <th>Predicted phones</th>
  </tr>
  <tr>
    <td>Up</td>
    <td>`Vp`<br>
      <audio controls>
        <source src="assets/audio/es_up.wav" type="audio/wav">
      </audio>
    </td>
    <td>`VvB`<br>
      <audio controls>
        <source src="assets/audio/pred_up.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
  <tr>
    <td>Down</td>
    <td>`daUn`<br>
      <audio controls>
        <source src="assets/audio/es_down.wav" type="audio/wav">
      </audio>
    </td>
    <td>`daU`<br>
      <audio controls>
        <source src="assets/audio/pred_down.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
  <tr>
    <td>Left</td>
    <td>`lEft`<br>
      <audio controls>
        <source src="assets/audio/es_left.wav" type="audio/wav">
      </audio>
    </td>
    <td>`lE`<br>
      <audio controls>
        <source src="assets/audio/pred_left.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
  <tr>
    <td>Right</td>
    <td>`raIt`<br>
      <audio controls>
        <source src="assets/audio/es_right.wav" type="audio/wav">
      </audio>
    </td>
    <td>`raISjn.`<br>
      <audio controls>
        <source src="assets/audio/pred_right.wav" type="audio/wav">
      </audio>
    </td>
  </tr>
</table>
