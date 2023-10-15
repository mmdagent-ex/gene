# CG Cybernetic Agent Model "Gene"

[![en](https://img.shields.io/badge/lang-en-red.svg)](README.md)
[![ja](https://img.shields.io/badge/lang-ja-blue.svg)](README.ja.md)

"Gene" is a CG avatar character model, developed under [AVATAR SYMBIOTIC SOCIETY Project](https://avatar-ss.org/en/index.html). It has been developed with [MMDAgent-EX](https://github.com/mmdagent-ex/MMDAgent-EX).

It is in MMD format, so you can open/edit/modify the model with MMD tools.

## Specifications

- 28646 vertices, 47106 surfaces, 13 materials, 12 textures
- A-pose, MMD-compliant scale
- 224 bones (supports MMD semi-standard bones)
- 184 morphs (basic MMD-compliant faces + perfect sync support)
- Physics: 87 rigid bodies, 92 joints

## Usage

To load model in MMDAgent-EX, just specify the model file "`Gene.pmd`" at `MODEL_ADD` message or other messages.

To use this model on MMD tools, use "`Gene.pmx`".

If you have troubld reading the model, try light-weight version with smaller texture: `Gene_light.pmd`.  The functions are the same.

## Special morphs

You can show/hide head parts by morph parameters:

- Mesh highlights on the hair
- Hear pin
- Cheek lines
- Cheek color

Relevant morphs are:

- "`頬斜線消し`": set to 1 to erase cheek lines
- "`頬赤み消し`": set to 1 to erase cheek color
- "`頬全消し`": set to 1 to erase both cheek lines and color
- "`メッシュなし`" set to 1 to erase hear mesh highlights
- "`髪留なし`" set to 1 to erase hear pin

On MMDAgent-EX, you can set the morph value by the following message:

```text
MODEL_BINDFACE|(model alias name)|morphname|value
```

## License

Files in this repository are licensed by Nagoya Institute of Technology under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.en):

CG-CA Gene (c) 2023 by Nagoya Institute of Technology

**Note**: the copyright holder still has trademark and design rights of this model.  You are permitted to use its trademark and design for:

- Academic purpose (publications and releases), and
- Personal non-commercial usage (posts to SNS or at an event).

For commercial use, please contact us (ri@nitech.ac.jp).

## Usage Guideline

These guidelines outline the ethical, legal and social issues to be observed when using this model.

Disallowed usage of our model:

- Child Sexual Abuse Material or any content that exploits or harms children
- Promotion of hateful, harassing, or violent content
- Activity that has high risk of physical harm, including:
  - Weapons development
  - Military and warfare
  - Management or operation of critical infrastructure in energy, transportation, and water
  - Content that promotes, encourages, or depicts acts of self-harm, such as suicide, cutting, and eating disorders
- Fraudulent or deceptive activity, including:
  - Scams
  - Coordinated inauthentic behavior
  - Plagiarism
  - Disinformation
- Actions harmful to the MikuMikuDance related community and its fun society:
  - Creation and disribution of contents that violates the rights of copyright holders of models, motions, music, etc.
  - Ignoring guidelines set by the copyright holders.
  - Unauthorized redistribution, plagiarism, and impersonation of the original creators.

Disclaimer: we are not responsible for any troubles between users caused by derivative works. Please take responsibility for your actions.

---
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/mmdagent-ex/gene">CG-CA Gene</a> by <span property="cc:attributionName">Nagoya Institute of Technology</span> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a></p>
