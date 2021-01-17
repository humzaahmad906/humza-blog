---
layout: post
title: Transformer Architecture
---

This blog post is about understanding transformer architecture that uses attention mechanism to focus on certain words on which the output depends. For example in language translation a word’s focus will mostly be on its meaning in another language. In transformer first all the words of a sentence will be converted into vectors that will represent their meanings and relative positions in that sentence. These embeddings will then be passed to the network that will see what words to focus for certain outputs also called self-attention plus a feed forward neural network. This network will encode the text to some numerical vectors that can be decoded with some similar kind of network to get the target output.

(![_config.yml]&#40;{{ site.baseurl }}/images/transformer.png&#41;)

[comment]: <> (![_config.yml]&#40;{{ site.baseurl }}/images/config.png&#41;)

[comment]: <> (The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository]&#40;https://github.com/barryclark/jekyll-now&#41; on GitHub.)