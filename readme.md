
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

<p align='center'>
  <img src='https://github.com/teamdrumwork/tune/blob/make/view/make.svg?raw=true' height='312'/>
</p>

<h3 align='center'>
  tune
</h3>
<p align='center'>
  An Intermediate Constructed Language
</p>

<br/>
<br/>
<br/>

<h3 id="summary">Summary</h3>

_Note: Tune is just in the prototype phases right now._

Tune is a [#conlang](https://en.wikipedia.org/wiki/Constructed_language) ("constructed language") that takes influence from English, Mandarin Chinese, Spanish, Sanskrit, Vietnamese, Hebrew, Arabic, Japanese, Tamil, and Hawaiian. Words are typically derived from English, though a few come from these other languages. Its phonology (i.e. the sounds it uses) is quite simple, only consisting of 19 simple consonant sounds and 5 basic vowel sounds. It is a mostly "analytic" language, meaning that pretty much everything is divided into words instead of having word inflections or word morphology changes. However we have taken the opportunity in a few cases to compress some words by shortening them and making them into suffixes, for extremely common paradigms like using verbs in the past tense. In addition, you can form words by joining them together separated by an appropriate vowel, so it is in a sense fusional and agglutinative as well to a small degree. There are no tones (like in Chinese), or clicks, like in some African languages.

One goal of tune is to create a language which can be used for programming (using very short words), and for speaking at the same time. The end goal is to define words that will help you think holistically about the universe and see its beautiful structure in great detail and clarity, to the point where you are so capable of seeing it that you can also read it in code. Code is highly structured information that is ideally unambiguous, so seeing the universe as code would be an extraordinary thing.

First we will outline the phonology in more detail so you know what to expect and how to write the words on a typical keyboard in ASCII. Next, we will go into some of the basic word forms and show you how to construct some basic words. Finally, we will show how we can build up the lexicon to eventually include all of the millions of English words in existence, from molecules to life forms to locations, etc..

See the [contributing guide](https://github.com/teamdrumwork/tune/blob/make/.github/contributing.md) for the intricate details on how things work, and how to contribute.

### Knowledge Representation

All things are actually a `xix` under the hood (pronounced "sheesh", see [call script](https://github.com/teamdrumwork/call) for pronunciation details). In English we are calling this a "shift" or "tropon", an action-object. The `xix` is then divided into `xiq` ("shing") "action" and `xaq` ("shaung") "object". A generic "shift type" is a `kix` "keesh", an action type being a `kiq` ("king") and an object type a `kaq` ("kong").

Can call a "fox" a "small wild canine". Can call a "canine" a "carnivorous animal". Can call an animal a "living structure". So a "fox" becomes a "small wild carnivorous living structure". But that is too long of a name, so for common stuff you give it a short name, in our case a 5-letter c-v-c-v-c word. The question is, what do you pick to give a common name to?

### Parts of Speech

All words are `xix` in their base form. They manifest into actions and objects and modifiers/features by suffixing the words with singular vowels.

- `-i`: The `xix` is a `xiq` (action).
- `-a`: The `xix` is a `xaq` (object).
- `-o`: The `xix` is a `xoq` (feature).

### Representing Self and Other

- `baq`: self
- `biq`: other
- `boq`: self and other

### Singular vs. Plural

All things are singular by default, so you just need to mark them the plural particle suffixing the main shift.

- `-ya`: many

This comes as a sortened form of `yaq`.

### Tense

Tense is marked by particles as well. Present is the default tense.

- `-ho`: past, shortened form of `hoq`.
- `-hi`: future, shortened form of `hiq`.
- `-ha`: currently active (-ing in English), shortened form of `haq`.

Note, there have evolved to be many "suffixes". You can tell what a suffix is by looking for an internal `h`. Regular words can begin with an `h`, but an `h` cannot fall in the middle of a word unless what follows is a suffix.

### Focusers

The words like "the", "a", "this", and "that" are focusers. They focus attention on aspects of the speaking context.

- `la`: the
- `ka`: a
- `fa`: this
- `fi`: that

### Representing I, you, and it

- `ma`: I, me, or myself.
- `ga`: You.
- `da`: It.
- `maya`: We.
- `gaya`: You all.
- `daya`: Them.

### Basic Sentences

_Note: A more up-to-date translation of some sentences should be found [here](https://github.com/teamdrumwork/tune/blob/make/list/sentence/full.csv)._

Sentences follow the SVO subject-verb-object format. Modifiers/features/adjectives precede the main verb or noun.

> I see the tree

```
do gezi la xudipa
```

> Black and white are all I see.

```
xonano vi xomano simi yu do gezi
```

> The water flows.

```
la sawasa madiha
```

### Generic types

Generic types are `kix` and are divided into action types `kiq` and object types `kaq`. This is used to describe the abstract things, especially used in modeling and representation like used in code.

A function call, for example, is called a `kiqakal`.

<h3 id="license">License</h3>

Copyright 2021 <a href='https://drum.work'>DrumWork</a>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

<h3 id="mount">DrumWork</h3>

The tune language is being developed by the folks at [DrumWork](https://drum.work), a California-based project for helping humanity master information and computation. DrumWork started off in the winter of 2008 as a spark of an idea, to formalizing the work 10 years later in the winter of 2018, now just beginning its development phases. DrumWork funds the development here. It is entirely bootstrapped by working full time and running [Etsy](https://etsy.com/shop/teamdrumwork) and [Amazon](https://www.amazon.com/s?rh=p_27%3AMount+Build) shops. Also find us on [Facebook](https://www.facebook.com/teamdrumwork), [Twitter](https://twitter.com/teamdrumwork), and [LinkedIn](https://www.linkedin.com/company/teamdrumwork). Check out our other GitHub projects as well!
