---
layout: default
title: Chapter 5
permalink: /chapter_5/
---

# AFTER : Audio feature transfer and exploration in real-time

<div style="text-align: center; margin-bottom: 30px;"> 
  <img src="/phd_support/docs/assets/after.jpg" 
       alt="Chapter 5 Banner" 
       style="max-width: 100%; height: auto; border-radius: 10px; box-shadow: 0px 4px 12px rgba(0,0,0,0.2);" />
</div>

This page presents results for our proposed AFTER model, that learns to map audio samples to explicit and implicit control spaces. We present results of timbre transfer between polyphonic instruments and drum recordings. 

Additional examples are available on our publication demo page : <a href="https://nilsdem.github.io/control-transfer-diffusion/">here</a>.

Github page with code :  <a href="https://github.com/acids-ircam/AFTER"> here </a>.

## Results on instrumental recordings 

<table class="table table-sm text-center" style="vertical-align: middle; width: 100%;">
  <thead>
    <tr>
      <th style="text-align:center; width: 200px;">Audio 1</th>
      <th style="text-align:center; width: 200px;">Audio 2</th>
      <th style="text-align:center; width: 300px;">AFTER (no SSL)</th>
      <th style="text-align:center; width: 300px;">AFTER (SSL)</th>
    </tr>
  </thead>
  <tbody>

  <!-- Example 11 -->
  <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_11/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_11/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_11/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_11/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/example_11/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/example_11/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>

  <!-- Example 15 -->
  <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_15/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_15/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_15/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_15/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/example_15/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/example_15/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>

  <!-- Example 18 -->
  <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_18/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_18/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_18/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_18/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/example_18/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/example_18/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>

  <!-- Example 84 -->
  <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_84/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_84/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_84/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_84/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/example_84/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/example_84/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>

  <!-- Example 87 -->
  <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_87/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_87/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_87/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/example_87/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/example_87/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/example_87/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>
<!-- Example 63 -->
  <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_63/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_63/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_63/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_63/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/real/example_63/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/real/example_63/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>

  <!-- Example 66 -->
  <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_66/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_66/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_66/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_66/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/real/example_66/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/real/example_66/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>

  <!-- Example 69 -->
  <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_69/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_69/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_69/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_69/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/real/example_69/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/real/example_69/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>

  <!-- Example 73 -->
  <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_73/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_73/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_73/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/nossl/real/example_73/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/real/example_73/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/ssl/real/example_73/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>
  

  </tbody>
</table>



## Results on drum recordings 

Experiments conducted on the [E-GMD dataset](https://magenta.withgoogle.com/datasets/e-gmd). 


<table class="table table-sm text-center" style="vertical-align: middle; width: 100%;">
  <thead>
    <tr>
      <th style="text-align:center; width: 200px;">Audio 1</th>
      <th style="text-align:center; width: 200px;">Audio 2</th>
      <th style="text-align:center; width: 300px;">AFTER (no SSL)</th>
      <th style="text-align:center; width: 300px;">AFTER (SSL)</th>
    </tr>
  </thead>
  <tbody>

  <!-- Example 11 -->
  <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_36/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_36/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_36/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_36/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_ssl/example_36/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_ssl/example_36/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>
  
  <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_41/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_41/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_41/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_41/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_ssl/example_41/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_ssl/example_41/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>
  
   <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_46/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_46/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_46/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_46/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_ssl/example_46/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_ssl/example_46/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>
  
  <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_50/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_50/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_50/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_50/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_ssl/example_50/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_ssl/example_50/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>
  
  <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_56/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_56/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_56/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_56/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_ssl/example_56/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_ssl/example_56/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>
  
  <tr>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_61/audio1.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_61/audio2.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_61/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_nossl/example_61/audio21.wav" controls style="width: 180px"></audio>
    </td>
    <td>
      <div><b>Audio 1 → 2</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_ssl/example_61/audio12.wav" controls style="width: 180px"></audio>
      <div><b>Audio 2 → 1</b></div>
      <audio src="/phd_support/docs/assets/samples/chapter5/drums_ssl/example_61/audio21.wav" controls style="width: 180px"></audio>
    </td>
  </tr>
  
  </tbody>
</table>

