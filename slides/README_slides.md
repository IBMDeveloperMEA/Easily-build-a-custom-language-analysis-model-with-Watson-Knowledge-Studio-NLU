---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: myst
      format_version: '1.1'
      jupytext_version: 1.1.0
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
---
<!-- 
+++ {"slideshow": {"slide_type": "slide"}}

# Tutorial slides

- Slides are optional (e.g., you may not use them if your presentation is via live coding).
- If the pre-recorded presentations will use slides, we request that you deposit the slides in this folder.

+++ {"slideshow": {"slide_type": "slide"}}

## Use text-based source

- We ask that you use text-based formats for your slides, e.g., markdown 
- This markdown file is an example source for slides using `nbconvert` and Reveal. See the GitHub action '.github/workflows/slides.yml' in this repo so see how this markdown file is converted to a HTML slide show and published on GitHub Pages - https://fawazsiddiqi.github.io/slides_to_pages

+++ {"slideshow": {"slide_type": "subslide"}}

## An example sub-slide

- Another option: you can write your slide content using markdown and use an app for slide design, like [Deckset](https://www.deckset.com) or similar.

+++ {"slideshow": {"slide_type": "slide"}}

## Naming convention and file list

- Use a **naming convention** where each file name starts with a number, reflecting the order of use in the presentation of the tutorial.
- List your slide files in a markdown, with a brief description.


+++ {"slideshow": {"slide_type": "slide"}} 
-->


**🌟 Overview** <br />
Natural language understanding is one of the most important fields in AI. It’s the comprehension of human language such as English, Spanish and French, for example, that allows computers to understand commands without the formalized syntax of computer languages. Join us in this workshop to see how easy and simple it is to create and build a customized language analysis model for a specific domain with Watson Knowledge Studio. The use case domain that we will be working with is the automotive field focusing on auto repair facilities.


**🎓 What will you learn?** <br />
What is Natural Language Understanding (NLU)?
What is Watson Knowledge Studio?
How to build a custom language analysis model?
How to train the model to analyse reviews?

**👩‍💻 Who should attend?** <br />
Anyone interested in NLU and machine learning
The workshop is for beginners and no programming experience or advanced technical knowledge is needed.

+++ {"slideshow": {"slide_type": "subslide"}}

**🎈 Prerequisites** <br />
☁ Sign in/Login into IBM Cloud using: https://ibm.biz/WKS_NLU

🍉 Register for the live stream and replay on Crowdcast: <br/>
https://www.crowdcast.io/e/custom-language-analysis

👩‍💻Resources <br />
- GitHub Repository - https://ibm.biz/WKSNLURepo
- Workshop Slides - https://ibmdevelopermea.github.io/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/
- Survey - https://ibm.biz/WKSNLUSurvey
- Follow along for the hands-on: https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU#CodeLab
- Meetup page - https://www.meetup.com/IBM-Cloud-MEA/events/ 

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide1.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide2.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide3.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide4.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide5.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide6.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide7.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide8.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide9.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide10.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide11.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide12.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide13.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide14.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide15.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide16.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/IBMDeveloperMEA/Easily-build-a-custom-language-analysis-model-with-Watson-Knowledge-Studio-NLU/blob/main/images/slide_images/Slide17.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

## License

**Recommend** that slides be shared under a [CC-BY](https://creativecommons.org/licenses/by/4.0/) license.
