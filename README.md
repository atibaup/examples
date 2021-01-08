
# Examples for Jina

<p align="center">
 
[![Jina](https://github.com/jina-ai/jina/blob/master/.github/badges/jina-hello-world-badge.svg "Run Jina 'Hello, World!' without installing anything")](https://github.com/jina-ai/jina#jina-hello-world-)
[![Jina](https://github.com/jina-ai/jina/blob/master/.github/badges/license-badge.svg "Jina is licensed under Apache-2.0")](#license)
[![Jina Docs](https://github.com/jina-ai/jina/blob/master/.github/badges/docs-badge.svg "Checkout our docs and learn Jina")](https://docs.jina.ai)
[![Python 3.7 3.8](https://github.com/jina-ai/jina/blob/master/.github/badges/python-badge.svg "Jina supports Python 3.7 and above")](#)
[![Docker](https://github.com/jina-ai/jina/blob/master/.github/badges/docker-badge.svg "Jina is multi-arch ready, can run on differnt architectures")](https://hub.docker.com/r/jinaai/jina/tags)

</p>

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Adding Tests for Examples](#adding-tests-for-examples)
- [Community](#community)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Start Here

First a little light background reading, and then let's jump in and build our first app!

<table>
  <tr>
    <td>
      <a href="https://jina.ai/2020/07/06/What-is-Neural-Search-and-Why-Should-I-Care.html">
        <img src="https://miro.medium.com/max/1000/1*czKD1E9fL1ndRGzwjv9Kvg.png", title="What is Neural Search?" alt="What is Neural search?">
      </a>
    </td>
    <td>
      <h3>
      <a href="https://jina.ai/2020/07/06/What-is-Neural-Search-and-Why-Should-I-Care.html">
        What is Neural Search?
      </a>
      </h3>
      <p>AI-powered search with less effort, more flexibility</p>
    </td>
  </tr>
  <tr>
      <td width="30%">
    <a href="https://github.com/jina-ai/jina/tree/master/docs/chapters/101">
      <img src="https://github.com/jina-ai/jina/blob/master/docs/chapters/101/img/ILLUS12.png?raw=true" alt="Jina 101 Concept Illustration Book, Copyright by Jina AI Limited" title="Jina 101 Concept Illustration Book, Copyright by Jina AI Limited"/>
    </a>
    </td>
    <td width="70%">
&nbsp;&nbsp;<h3><a href="https://github.com/jina-ai/jina/tree/master/docs/chapters/101">Jina 101: First Thing to Learn About Jina</a></h3>
&nbsp;&nbsp;<a href="https://github.com/jina-ai/jina/tree/master/docs/chapters/101">English</a> •
  <a href="https://github.com/jina-ai/jina/tree/master/docs/chapters/101/README.ja.md">日本語</a> •
  <a href="https://github.com/jina-ai/jina/tree/master/docs/chapters/101/README.fr.md">français</a> •
  <a href="https://github.com/jina-ai/jina/tree/master/docs/chapters/101/README.de.md">Deutsch</a> •
  <a href="https://github.com/jina-ai/jina/tree/master/docs/chapters/101/README.ru.md">Русский язык</a> •
  <a href="https://github.com/jina-ai/jina/tree/master/docs/chapters/101/README.zh.md">中文</a>
    </td>

  </tr>
</table>

## 🐣 Simple Examples

<table>
  <tr>
    <td>
      <h1>📄</h1>
    </td>
    <td>
      <h4><a href="https://github.com/jina-ai/examples/tree/master/my-first-jina-app">My First Jina App</a></h4>
      Brand new to neural search? Not for long! Use cookiecutter to search through Star Trek scripts using Jina
    </td>
  </tr>
  <tr>
    <td>
      <h1>📄</h1>
    </td>
    <td>
      <h4><a href="https://github.com/jina-ai/examples/tree/master/southpark-search">Build a NLP Semantic Search System with Transformers</a></h4>
      Upgrade from plain search to sentence search and practice your Flows and Pods by searching South Park scripts
    </td>
  </tr>
  <tr>
    <td>
      <h1>📄</h1>
    </td>
    <td>
      <h4><a href="https://github.com/jina-ai/examples/tree/master/multires-lyrics-search">Search Lyrics with Transformers and PyTorch</a></h4>
      Get a better understanding of chunks by searching a lyrics database. Now with shiny front-end!
    </td>
  </tr>
  <tr>
    <td>
      <h1>🖼️</h1>
    </td>
    <td>
      <h4><a href="https://github.com/jina-ai/examples/tree/master/pokedex-with-bit">Google's Big Transfer Model in (Poké-)Production</a></h4>
      Use SOTA visual representation for searching Pokémon!
    </td>
  </tr>
  <tr>
    <td>
      <h1>🖼️</h1>
    </td>
    <td>
      <h4><a href="https://github.com/jina-ai/examples/tree/master/object-search">Object detection with fasterrcnn and MobileNetV2</a></h4>
      Detect, index and query similar objects
    </td>
  </tr>
  <tr>
    <td>
      <h1>🎧</h1>
    </td>
    <td>
      <h4><a href="https://github.com/jina-ai/examples/tree/master/audio-search">Search YouTube audio data with Vggish</a></h4>
      A demo of neural search for audio data based Vggish model.
    </td>
  </tr>
  <tr>
    <td>
      <h1>🎞️ </h1>
    </td>
    <td>
      <h4><a href="https://github.com/jina-ai/examples/tree/master/tumblr-gif-search">Search Tumblr GIFs with KerasEncoder</a></h4>
      Use prefetching and sharding to improve the performance of your index and query flow when searching animated GIFs.
    </td>
  </tr>
</table>

## 🕊️ /Advanced Examples

<table>
  <tr>
    <td>
      <h1>🖼️📄</h1>
    </td>
    <td>
      <h4><a href="https://github.com/jina-ai/examples/tree/master/cross-modal-search">Cross Modal: Search images from captions and vice-versa</a></h4>
      Use one modality (text) to search another (images)
    </td>
  </tr>
  <tr>
    <td>
      <h1>🖼️📄</h1>
    </td>
    <td>
      <h4><a href="https://github.com/jina-ai/examples/tree/master/multimodal-search-tirg">Multi-Modal: Search images with 2 modalities in the query</a></h4>
      Use more than one modality (image+text) to search images
    </td>
  </tr>
  <tr>
    <td>
      <h1>🖼️</h1>
    </td>
    <td>
      <h4><a href="https://github.com/jina-ai/examples/tree/master/fashion-example-query">Build complex logic, structures and filters with Query Language</a></h4>
      Create separate indexes and queries for different clothing in Fashion-MNIST
    </td>
  </tr>
  <tr>
    <td>
      <h1>🖼️</h1>
    </td>
    <td>
      <h4><a href="https://github.com/jina-ai/examples/tree/master/faiss-search">Index and query with FAISS</a></h4>
      Build a vector search engine that finds the closest vector in the database to a query.
    </td>
  </tr>
</table>

## Useful Docs

<table>
<tr>
<td>
<h5>Performance and Scalability</h5>
</td>
<td>
- <a href="https://docs.jina.ai/chapters/remote/index.html">Distribute Your Workflow Remotely</a>
- <a href="https://docs.jina.ai/chapters/hub/index.html">Run Jina Pod in Docker Containers</a>
</td>
</tr>
<tr>
<td>
<h5>Extend and Share Jina</h5>
</td>
<td>
- <a href="https://docs.jina.ai/chapters/extend/executor.html">Extend Jina by Implementing Your Own Executor</a>
- <a href="https://github.com/jina-ai/jina-hub#publish-your-pod-image-to-jina-hub">Share Your Extension with the World</a>
</td>
</tr>
</table>

## Adding Tests for Examples

You are highly encouraged to add a test for your example so that we will be alerted if it breaks in the future:

1. Put your test data in the `tests` folder. The test data can be a few text sentences, images or audio samples
2. Create `test_[your_example].py` in the `tests` folder. Add your test cases to the `tests` file with meaningful asserts depending on example input and output
3. Run the test locally to confirm before pushing with [pytest](https://docs.pytest.org/en/stable/contents.html)
4. Add your example folder name to the `path` variable in `matrix` of `.github/worflows/ci.yml`. This will trigger your example test on creating a pull request.


## Tips

- For reference, check out the `tests` folder from [South Park example](https://github.com/jina-ai/examples/tree/master/southpark-search/tests) if your data is about text and [object search example](https://github.com/jina-ai/examples/tree/master/object-search/tests) for images.
- Try using the original example function by importing them to the test. Avoid any modifications to original Flow or logic.
- Use the [pytest fixture](https://docs.pytest.org/en/stable/fixture.html) `tmpdir` for temporary directory

## Community

- [Slack channel](http://slack.jina.ai) - a communication platform for developers to discuss Jina
- [LinkedIn](https://www.linkedin.com/company/jinaai/) - get to know Jina AI as a company and find job opportunities
- [![Twitter Follow](https://img.shields.io/twitter/follow/JinaAI_?label=Follow%20%40JinaAI_&style=social)](https://twitter.com/JinaAI_) - follow us and interact with us using hashtag `#JinaSearch`  
- [Company](https://jina.ai) - know more about our company, we are fully committed to open-source!


## License

Copyright (c) 2021 Jina AI Limited. All rights reserved.

Jina is licensed under the Apache License, Version 2.0. See [LICENSE](https://github.com/jina-ai/jina/blob/master/LICENSE) for the full license text.
