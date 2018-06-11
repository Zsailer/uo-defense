# Thesis Defense

Reveal slides used for the defense of my PhD at University of Oregon, June 2018.

## Install

```
# Clone repo
git clone xx
cd uo-defense

# Get reveal.js submodule
git submodule init
git submodule update

# Build reveal.js
cd reveal.js/
npm install

# Build presentation using slide machine
cd ..
slidemachine talk.md --template template.html

# Open presentation locally
open index.html
```
