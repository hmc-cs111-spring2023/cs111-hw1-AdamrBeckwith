# Language

The Name of the Language is SUPERCOLLIDER

https://supercollider.github.io/

# Domain

DSL For Audio Synthesis and Algorithmic Composition 


# Computational model

The Computational model takes the DSL code and converts it to an audio format when `.play` is run. 
Within the code you can create samples from established code and changing pitch, volume, etc, and then string them together at different paces. _Creating music or sound effects!_


# DSL-ness

Definitely domain specific, it doesnt any use outside of making audio samples. However, for the purpose of making audio samples it brings many functions of general progamming language as using algorithms (and math) is necessary for synthesizing the audio.  

_Fowler writes about a spectrum of languages, from general-purpose languages to
"purely" domain-specific. Where does the DSL you chose fall on this spectrum,
and why?_

# Internal or external?

External. The Main instalation is self contianed, and isnt called from another language pipeline. In fact, although it initially has some syntax simularities to python it doesnt really connect with any other language. It seems to be mostly external. 

# Host language

The DSL is made mostly with C++ and is **open source**: https://github.com/supercollider/supercollider

# Benefits

Compared to traditional audio creation methods (folly and music) this DSL fulfills a niche of purely synthetic audio. We store audio as bits and math, so this allows us to work with that directly and create sounds we couldn't have otherwise. 

# Drawbacks

One drawback is it is very low level and slow, making a 3 minute sample that doesnt repeat signficantly would take a signficant amount of code. Its high fidelity and complexity but low usability .


I answered most the questions just with my gut instinct. Please inform me if future assignments require longer replies. 