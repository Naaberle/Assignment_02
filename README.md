<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->




<!-- PROJECT LOGO -->
<br />
<div align="center">
  </a>

  <h3 align="center">Moiré Interference: Designing Overlap as a Medium</h3>

  <p align="center">
    A parametric design strategy for physical Moiré-based illusions in overlapping rotational geometries.
    <br />
    <br />
    <a href="https://nikaberle.carbonmade.com">Nik Aberle</a>
    &middot;
    <a href="https://sites.google.com/view/viza626/home">VIZA 626</a>
  </p>
</div>

[![4-comma][images-fig1]](https://github.com/Naaberle/4-comma-Assignment_01/blob/main/images/fig1.png)

Figure 1. This is my 4-comma, highlighting a previously known hallucination of LLMs (that has since been fixed) that most didn't expect the models to struggle with. 

<!-- Abstract -->
## Abstract
Utilizing parametric design principles within Grasshopper and Rhino, I designed a system for generating unique radial geometries to explore their overlaps in the context of Moiré-based illusions. The goal was to create a means to analyze how interference patterns emerge from physical overlap, and to identify configurations that could be 3D printed to produce convincing optical illusions. This process helps define specific metrics that influence the Moiré effect; such as the number of spokes, spoke width, depth, direction, and potentially even rotational speed. The result is an elegant solution for rapidly prototyping and testing combinations of interference in physical forms.

<!-- Introduction and Related Works -->
## Introduction and Related Works (200 Wds)

I’ve always found the concept of hallucinations within AI and LLMs to be among the most fascinating aspects. Over time it went from being something I was amused by – such as when an LLM makes up an accidentally humorous fabrication – to being something that was almost like a game. As the models got better and hallucinations were more infrequent, trying to trick a model into giving false information came with its own sort of reward system. 

While some have debated over the use of the word hallucination, as well as its definition when used[1][2], all agree that it is a common issue when training a new model. Since hallucinations can sometimes be very dramatic I chose to illustrate my comic in a minimalist style, so that the 3rd panel could offer a sudden visual difference before the punch line of the joke in panel 4.

Some researchers have also posited that hallucinations are inevitable [3], so to further validate my comic I conducted an experiment involving 200 questions and two different versions of ChatGPT. The goal being to get it to hallucinate, and/or determine which types of questions it’s less likely to hallucinate answers to.

## Methodology (300 wds)

I broke the 200 hundred questions up into four categories. Known Truths vs Obscure Data, Random Fact Generation, Fake Sources and Citations, and Plausibility-Based Deceptions. For a complete list of the questions as well as a more detailed explanation of each method please see the Supplemental Documentation. 

The hallucination depicted in my comic was a common known hallucination for LLMs circa 2023. A problem that was seemingly simple to solve, but that LLMs couldn’t properly calculate. It has since been fixed, but made me wonder what other seemingly simple things were difficult for LLMs to properly parse. 

I worked in this manner as I believed having four distinct categories offered me a chance to broaden how many ways I could attempt to elicit a hallucination. Working in categories will allow for others to replicate this experiment with their own questions if they so choose. 
For the testing component, I asked the same questions to both ChatGPT 4o and a free ChatGPT account. I targeted these because they’re currently two of the most commonly used LLMs specifically for text, and would create a great base for my experiment. This methodology could be used to test future LLMs for wide spectrum hallucinations.

## Result and Future Work (200 wds)
While there were some hallucinations, there were far fewer than I expected. Only a total of three were identified across all eight sets of questions between both models. One important note is that the free ChatGPT was unable to offer answers either way for the article citations as it doesn’t have internet access. If I could do the experiment again I would include more models in different stages of their training to get a more robust series of data across the life of an LLM.

For future works I plan to apply similar methodology seeking hallucinations but to image generation. 

[![4-comma][images-fig2]](https://example.com)

Figure 2. One of two instances of a hallucination was ChatGPT free hallucinating a movie title and director.

[![4-comma][images-fig3]](https://example.com)

Figure 3. The second instance of hallucination was ChatGPT 4o hallucinating scholarly article locations that didn't exist, though they did contain similar titles.

## Conclusion (100 wds)
After the first set of questions yielded a single hallucination I became both excited to find another and surprised there weren’t more. LLMs have come a long way since their debut and they are far less prone to hallucinations, but that won’t stop me from trying to find them.

<!-- Bibliography -->
## Bibliography 
[1] Lei Huang, Weijiang Yu, Weitao Ma, Weihong Zhong, Zhangyin Feng, Haotian Wang, Qianglong Chen, Weihua Peng, Xiaocheng Feng, Bing Qin, et al. 2025. A survey on hallucination in large language models: Principles, taxonomy, challenges, and open questions. ACM Transactions on Information Systems 43, 2 (2025), 1–55.

[2] Negar Maleki, Balaji Padmanabhan, and Kaushik Dutta. 2024. AI hallucinations: a misnomer worth clarifying. In 2024 IEEE conference on artificial intelligence (CAI). IEEE, 133–138.

[3] Ziwei Xu, Sanjay Jain, and Mohan Kankanhalli. 2024. Hallucination is inevitable: An innate limitation of large language models. arXiv preprint arXiv:2401.11817 (2024).


<!-- CONTACT -->
## Contact

Your Name - nik.aberle@tamu.edu

Personal Website: https://nikaberle.carbonmade.com




<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

This work is submitted as part of Assignment 1 for the VIZA 626 course at Texas A&M University, under the instruction of Professor You-Jin Kim, during the Spring 2025 semester.

VIZA 626 Class Website: [https://sites.google.com/view/viza626/](https://sites.google.com/view/viza626/home)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[images-fig1]: images/fig1.png
[images-fig2]: images/fig2.png
[images-fig3]: images/fig3.png
[images-fig4]: images/fig4.png
[images-fig5]: images/fig5.png
[images-fig6]: images/fig6.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
