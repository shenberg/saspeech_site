<style type="text/css">
  .tg {
    border-collapse: collapse;
    border-color: #9ABAD9;
    border-spacing: 0;
  }

  .tg td {
    background-color: #EBF5FF;
    border-color: #9ABAD9;
    border-style: solid;
    border-width: 1px;
    color: #444;
    font-family: Arial, sans-serif;
    font-size: 14px;
    overflow: hidden;
    padding: 0px 20px;
    word-break: normal;
    font-weight: bold;
    vertical-align: middle;
    horizontal-align: center;
    white-space: nowrap;
  }

  .tg th {
    background-color: #409cff;
    border-color: #9ABAD9;
    border-style: solid;
    border-width: 1px;
    color: #fff;
    font-family: Arial, sans-serif;
    font-size: 14px;
    font-weight: normal;
    overflow: hidden;
    padding: 0px 20px;
    word-break: normal;
    font-weight: bold;
    vertical-align: middle;
    horizontal-align: center;
    white-space: nowrap;
    padding: 10px;
    margin: auto;
  }

  .tg .tg-0pky {
    border-color: inherit;
    text-align: center;
    vertical-align: top,
  }

  .tg .tg-fymr {
    border-color: inherit;
    font-weight: bold;
    text-align: center;
    vertical-align: top
  }
  .slider {
  -webkit-appearance: none;
  width: 75%;
  height: 15px;
  border-radius: 5px;
  background: #d3d3d3;
  outline: none;
  opacity: 0.7;
  -webkit-transition: .2s;
  transition: opacity .2s;
}

.slider::-webkit-slider-thumb {
  -webkit-appearance: none;
  appearance: none;
  width: 25px;
  height: 25px;
  border-radius: 50%;
  background: #409cff;
  cursor: pointer;
}

.slider::-moz-range-thumb {
  width: 25px;
  height: 25px;
  border-radius: 50%;
  background: #409cff;
  cursor: pointer;
}

audio {
    width: 110px;
}
</style>

# SASPEECH: A Hebrew Single Speaker Dataset for Text To Speech and Voice Conversion

We present SASPEECH, a 30-hour single speaker Hebrew corpus accompanied by a text-to-speech (TTS) benchmark. It is the first large-scale high-quality open dataset of its kind. We believe our work will facilitate future generative Hebrew tools and low resource language research. The corpus will be publicly accessible at [https://www.openslr.org/134]. Code for the baseline TTS system will be available at [TODO]

Link to dataset coming soon.

## Dataset examples

<table class="dataframe tg">
  <thead>
    <tr style="text-align: center;">
      <th>Original</th>
      <th>OverFlow (7350 steps) + HiFi-GAN</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><audio id="audio-small" controls>
    <source src="wavs/gt/Live_Relocation_0012.wav" type="audio/wav">
</audio></td>
      <td><audio id="audio-small" controls>
    <source src="wavs/tts_paper/065.wav" type="audio/wav">
</audio></td>
    </tr>
    <tr>
      <td><audio id="audio-small" controls>
    <source src="wavs/gt/Hashlama111_0004.wav" type="audio/wav">
</audio></td>
      <td><audio id="audio-small" controls>
    <source src="wavs/tts_paper/041.wav" type="audio/wav">
</audio></td>
    </tr>
    <tr>
      <td><audio id="audio-small" controls>
    <source src="wavs/gt/Stock Market_0049.wav" type="audio/wav">
</audio></td>
      <td><audio id="audio-small" controls>
    <source src="wavs/tts_paper/096.wav" type="audio/wav">
</audio></td>
    </tr>
    <tr>
      <td><audio id="audio-small" controls>
    <source src="wavs/gt/Corona12_0022.wav" type="audio/wav">
</audio></td>
      <td><audio id="audio-small" controls>
    <source src="wavs/tts_paper/018.wav" type="audio/wav">
</audio></td>
    </tr>
    <tr>
      <td><audio id="audio-small" controls>
    <source src="wavs/gt/Prisons_0151.wav" type="audio/wav">
</audio></td>
      <td><audio id="audio-small" controls>
    <source src="wavs/tts_paper/084.wav" type="audio/wav">
</audio></td>
    </tr>
    <tr>
      <td><audio id="audio-small" controls>
    <source src="wavs/gt/Putin_0026.wav" type="audio/wav">
</audio></td>
      <td><audio id="audio-small" controls>
    <source src="wavs/tts_paper/086.wav" type="audio/wav">
</audio></td>
    </tr>
    <tr>
      <td><audio id="audio-small" controls>
    <source src="wavs/gt/Lod_0010.wav" type="audio/wav">
</audio></td>
      <td><audio id="audio-small" controls>
    <source src="wavs/tts_paper/067.wav" type="audio/wav">
</audio></td>
    </tr>
    <tr>
      <td><audio id="audio-small" controls>
    <source src="wavs/gt/Hashlama116_0024.wav" type="audio/wav">
</audio></td>
      <td><audio id="audio-small" controls>
    <source src="wavs/tts_paper/043.wav" type="audio/wav">
</audio></td>
    </tr>
    <tr>
      <td><audio id="audio-small" controls>
    <source src="wavs/gt/Annexation_0048.wav" type="audio/wav">
</audio></td>
      <td><audio id="audio-small" controls>
    <source src="wavs/tts_paper/010.wav" type="audio/wav">
</audio></td>
    </tr>
    <tr>
      <td><audio id="audio-small" controls>
    <source src="wavs/gt/4000_1_0004.wav" type="audio/wav">
</audio></td>
      <td><audio id="audio-small" controls>
    <source src="wavs/tts_paper/000.wav" type="audio/wav">
</audio></td>
    </tr>
  </tbody>
</table>
