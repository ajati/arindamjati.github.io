---
layout: page
title: Talks
subtitle: Caffine helps...
---

<head>
<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 50%;
  padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}

div {
  text-align: justify;
  text-justify: inter-word;
}

</style>
</head>
<body>

<h2>Supervised Deep Hashing for Efficient Audio Retrieval</h2>
<a href="https://www.microsoft.com/en-us/research/video/supervised-deep-hashing-for-efficient-audio-retrieval">Talk at Microsoft Research, Redmond, WA, USA</a>

<div class="row">
  <div class="column">
    <p>
    Efficient retrieval of audio events can facilitate real-time implementation of numerous query and search-based systems. This work investigates the potency of different hashing techniques for efficient
audio event retrieval. Multiple state-of-the-art weak audio embeddings are employed for this purpose. The performance of four classical unsupervised hashing algorithms is explored as part of off-theshelf analysis. Then, we propose a partially supervised deep hashing framework that transforms the weak embeddings into a lowdimensional space while optimizing for efficient hash codes. The
model uses only a fraction of the available labels and is shown here
to significantly improve the retrieval accuracy on two widely employed audio event datasets. The extensive analysis and comparison
between supervised and unsupervised hashing methods presented
here, give insights on the quantizability of audio embeddings. This
work provides a first look in efficient audio event retrieval systems
and hopes to set baselines for future research.
    </p>
  </div>
  <div class="column">
    <iframe width="400" height="300" src="https://www.youtube.com/embed/yg-Hbu9GbRs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>

</body>
