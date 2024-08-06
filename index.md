---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
author_profile: false
---
<!-- Complex numbers are numbers with a *real* and *imaginary* component, in the form \\(a+bi\\), where \\(a\\) and \\(b\\) are real numbers, and \\(i\\) is the ***imaginary unit***.

An extended explanation of complex numbers can be found [here](https://en.wikipedia.org/wiki/Complex_number).

It can be helpful to visualize complex numbers on the complex plan:
![Complex Plane](https://upload.wikimedia.org/wikipedia/commons/5/57/90-Degree_Rotations_in_the_Complex_Plane.png)

Complex numbers can also be represented in polar form as seen below:
[![Polar form](https://www.songho.ca/math/euler/files/euler17.png)](https://www.songho.ca/math/euler/euler.html)

To understand how the polar form is derived, check out this video:
<iframe width="560" height="315" src="https://www.youtube.com/embed/lFT2hwsCMls?si=_flcSkiBf9YD6IUX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Complex numbers are important in quantum mechanics and quantum computing, (explanation of concept)[^1]. ⚛️

[^1]: [Scientific American](https://www.scientificamerican.com/article/quantum-physics-falls-apart-without-imaginary-numbers) -->
<ins>Mini Project Idea</ins>

In this mini-project demonstration, I would like to answer the question:
How can the properties of quantum mechanics be utilized to generate truly random numbers?


<br />  <ins>Background</ins>

I have enjoyed indulging in the mathematics behind qubits and quantum gates throughout the MathQuantum Fellowship and saw this opportunity to familiarize myself with the various technical aspects of quantum computing. Thus, I wanted to apply my knowledge to a simple project and better understand the properties of qubits and quantum gates.

Here is a video I found particularly enlightening about Quantum Random Number Generation:

<iframe width="1040" height="595" src="https://www.youtube.com/embed/KXDxFCRgPoQ" title="Quantum Random Number Generation - Do we really need it?" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<br /> I learned that classical random number generators create pseudo-random numbers, which is suitable for most practical purposes, but when it comes to cryptography and the generation of keys, it may not be the most ideal.

Another comprehensive resource I've found helpful in the search for randomness was *A Comprehensive Review of Quantum Random Number Generators: Concepts, Classification and the Origin of Randomness*, which detailed how some Quantum Random Number Generators spawned numbers from radioactivity and electronic circuit noise[^1].

I also found the article *Quantum random number generation* very helpful, as the authors delved into the specifics of how randomness can be calculated through entropy and the several methods of preparing random quantum states[^2].

[^1]: [arXiv](https://arxiv.org/pdf/2203.00261)
[^2]: [Nature](https://www.nature.com/articles/npjqi201621)


<br />  <ins>Mathematical & Quantum Tools/Techniques</ins>

The necessary mathematical tools to approach this project are probability and statistics, as we need to analyze the probability distribution of the number generator outputs. Linear Algebra is also hidden within this problem, as preparing the necessary qubit states that lead to random bit measurements stems from unitary matrix operations on the starting qubit state. The fundamental quantum mechanics concepts involved in this work are superposition and measurement, as we take advantage of the qubit's superposition between the &#124;0> and &#124;1> states to create a random distribution of measuring a 0 or 1 as the output bit.

The code sample for my mini number generator can be found [here](https://colab.research.google.com/drive/1RzHvUcaCdU4DLMN4EsDXW755mJCEx-3u#scrollTo=Jz4td9jgiplh).


<br />  <ins>Goals</ins>

Through this mini-project, I’ve explored how qubits are inherently random when placed into an equal superposition, and I learned more about the programming aspect of quantum computing. I would like to implement my quantum gate bit generation in video games such as Pong or Flappy Bird, where the player is supposed to construct a quantum circuit in order to make the character move. In the future, I would like to research the intersection between quantum computing and machine learning. To reach this point of expertise, I would like to build my knowledge of composing quantum algorithms via circuits and become more fluent in quantum programming libraries.
