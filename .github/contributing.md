
# Welcome to the Term Language

Thank you for wanting to contribute to the Term language! All your effort and help with the project is very much so appreciated, and will help us reach the goal of translating the first 10,000 words into Term.

## Background

First, this project was started out of curiosity of how regular "natural" languages work, and wanting to find a way for a computer to understand a language like English. Well after many years of thinking about this and pondering the problem, it still seems very hard to handle English. However, what if we created our own language that had more sharply and clearly defined rules, that was more "structured" as well so a computer could understand it? (But at the same time you could speak it, too). That is the spark of the interest that led to Term being created.

Basically the goal with Term is to take _all_ of the English words (and words from other cultures, religions, sciences, fields, etc.), and convert them into a standard form. In the end, we will have all of the concepts classified into one system that isn't polluted by centuries of tinkering around and patching the English language with different features and such. English is full of words derived from Latin and Greek, but also other languages, and it is very complex. Especially for things like the biological species name (in the biological taxonomy), or chemical names, particle names, rock names, places on earth, etc. We would like to redo all these things and come up with a central system for the whole thing. If for no other reason than it would make it easier for a computer to understand the meaning of different words and concepts.

## Goal

So what we are doing, first and foremost, is capturing the simplest, most fundamental words first, and making those 1 syllable within Term so they are easy to pronounce. In an ideal world, these are the first words you would teach a child or young student. Up until around the first 5,000 words or so (as that is how many words we can easily create using the patterns and systems we've landed on for word formation, and that is about how many words we could collect on the web efficiently, based on many lists of 100 to 1000 common words). So we have collected 5,000 or so English words _in their base form_, meaning, given the words "create", "created", and "creating", the base form is "create". So we have 5,000 words like "create" which are in their base form, and have single-syllable Term words associated with them for ease of use.

The first goal, is to take these 5000 words, and to figure out the part of speech of them (verb, noun, etc.), and to take the base Term word and complete it so it correctly reflects the English word's part of speech. This will give us a list of 5,000 1-syllable words, with proper translations into Term.

Another goal is to build on these 5,000 words by finding word _derivations_. That is, finding the words like "created" and "creating" (and many others like "creation", etc.), which will greatly explode the size of our word list (lexicon). You can say there are on average 5-10 derivations of a word, so given we have 5,000 base words, that is anywhere from 25,000-50,000 different words! And for each of these derivations, we need a specific Term translation. That is no easy task, and will take the contribution efforts of many people over a long period of time, especially to make it a good list to learn from. Well it turns out, the average high-school graduate is said to know about 50,000 words, so that would be just the right amount. But we aren't sure if that means 50k "base" words, or 50k words in general. If it's 50k base words, then we have much more to go!

That leads us to another goal, to collect 1 million "terms". That is an extremely long term goal that will probably take many many years. But a "term" means either a single word (which can be a "compound" word, composed of many sub-word parts), or multiple words (like "Radio Show Host"). We want to collect as many of these terms as we can so it comes up to par in breadth and depth of scope to a natural language like English. We can use Wikipedia as our guide here, on which terms to translate, along with all their "glossaries" in different academic fields.

A related goal is to translate many standard terminology sets into Term, such as the biological taxonomy previously mentioned, the chemical names, atom names, tool and technology names, and jargon from specific academic fields. We aren't just going to necessarily directly translate each word part-by-part (using the Latin/Greek affixes, for example), into Term, but we can do that if it makes sense. Instead, we will try and use those as inspiration for coming up with an even simpler jargon for whatever industry or topic we are focusing on.

So those are the main goals, first building a relatively small and high quality word list which will work with children, and then expanding it to include as many terms as possible. The first 5,000 or so words will be 1-syllable extremely simple words and concepts. Then we have room for 130,000+ words, written as two-syllable 5-letter words, following the pattern c-v-c-v-c (consonant, vowel). In total, these 135,000+ possible words should/will represent _fundamental_ concepts which are hard to break down any further efficiently/usefully, with the 5,000-ish 1-syllable words being the simplest of the group. Then we will have room to create potentially millions of compound words which are derived from these fundamental building blocks.

## How You Can Help

Now we can get into the details a little bit of how you can help translating words into Term.

The first major thing that can be done is collecting words in their "base" form. This can be done by browsing dictionaries, or finding word lists (though we have already found most word lists on the web we could and filtered through them to find the best ones), or thinking of words you already know (though it's hard to tell what we _don't_ have haha). Another place to look for words is in specific industries (like you'll find the word "tensor" used in physics, but hardly anywhere else). If you find any words, even just one, feel free to create a pull request on GitHub for this project, or work with us however is easiest for you and we can get them integrated into this GitHub project (which is freely available under the Apache license for now).

The second thing that can be done is to find word derivations based on these base forms, as we previously described. Several tools on the web already provide word derivations for you, so sometimes its as easy as just doing a search and harvesting the results. Other times it's less obvious and things may have to be done by hand.

Those two tasks are focusing on English word collection and curation. You can gather words from other languages as it makes sense, as some languages have words for things which English doesn't have a word for. However, we don't want to duplicate the effort as of now in collecting words from every language, we'll save that for a separate project. So this project is mainly focused on "concept" collecting in the more general sense, most of which are in English words already, but some of which may be in other languages.

The third thing that you could quickly help with is taking the initial Term words which we have provided along with each base word, and writing the Term word so it matches the English word's part of speech. Or you can take the English words for which there are no Term words associated, and find the base word to get the base Term word for it, and then write out the full Term word to match the part of speech and features of the English word.

The final thing you can do is to look for mistakes in the existing translations and English words we've harvested. Many word lists come with junk words, words which don't make any sense, or words that are spelled wrong. If you see any of these, please feel free to let us know, or fix them and send us the updated files, or create a GitHub PR with the associated changes. Always feel free to help contribute to this project in any way you can see fit, that's the main way we can get to where we can see in the future.

## How Term Works

Now that you know what can be done, all that's really left is figuring out how Term works. What are the grammatical features for word construction? That is what we will discuss in this section.

### Phonology and Writing System

First, we need to know how to actually write the words in Term, and what sounds we can even use to make words in the first place! That is the writing system and "phonology" (sound study).

All sounds and pronunciations are written using [call script](https://github.com/drumworkteam/call), which is a system we have devised for writing the _pronunciation_ of words using only letters you have on your traditional laptop keyboard. We use only a small subset of the features of the call script in Term, because Term is designed as a language to only use really simple sounds, and it turns out to map nicely to call scripts lettering system. Take a look at that call script link, it describes in much more detail what call script is all about and how it works, if you are interested. However, we will give you just the pieces of it you need to know of right here as well.

Here, we will write the consonants and vowels we use in Term, which is using call script, and will write a word next to each letter to show the key sound that the letter represents. After reading through these, you should know how to write a pronunciation using your keyboard. That is, you can write a word in Term, which inherently includes how to pronounce it!

In Term, there are 22 **consonants** used. They are:

- `m`: "mark" "mol"
- `n`: "note" "nag"
- `q`: the `-ng` in "sing"
- `g`: "gift" "gap"
- `d`: "deed" "dim"
- `b`: "band" "ban"
- `p`: "play" "pek"
- `t`: "time" "tom"
- `k`: "king" "kez"
- `h`: "heal" "hup"
- `s`: "soul" "sov"
- `f`: "fire" "fod"
- `v`: "vibe" "vab"
- `z`: "zone" "zeg"
- `j`: "measure"
- `x`: "ship", the "sh" sound "xip"
- `c`: "thor"
- `C`: "this"
- `w`: "wave" "wav"
- `y`: "yard" "yok"
- `l`: "love" "lit"
- `r`: "rat" but with spanish, arabic, or indian accent "rot"

The consonants that are missing (i.e. that Term does not use) are things like the Hebrew/Arabic harsh "h" sound, the ejective (hard) consonants like in Georgian, the stop consonants like in Korean, or the click sounds like in some African languages. Also, we don't use the "j" sound (like in "measure"), or the "th" sound (represented as "c" in call script), either like in the word "the" or "thing".

Then we have the **vowels**. There are 5 vowels used in Term. They are:

- `i`: "seat"
- `e`: "make"
- `a`: "call"
- `o`: "hold"
- `u`: "tool"

We have left out as many as 10 or more vowel sounds used by various other languages, focusing only on these extremely distinct vowel sounds.

In the end, we have 22 consonants and 5 vowels, for a total of 27 sounds. Here is the alphabetical order.

- `i`: 1
- `e`: 2
- `a`: 3
- `o`: 4
- `u`: 5
- `m`: 6
- `n`: 7
- `q`: 8
- `g`: 9
- `d`: 10
- `b`: 20
- `p`: 30
- `t`: 40
- `k`: 50
- `h`: 60
- `s`: 70
- `f`: 80
- `v`: 90
- `z`: 100
- `j`: 200
- `x`: 300
- `c`: 400
- `C`: 500
- `w`: 600
- `y`: 700
- `l`: 800
- `r`: 900

## Word Formation Rules

Next we will describe the key word formation rules. First, some major things we can get out of the way up front.

- All base word forms start and end with a consonant. They are turned into nouns, verbs, adjectives, etc. by adding vowels to the end.
- Words components can't end in `el` or `il` because it adds an extra syllable depending on pronunciation style.
- Words components can't end in `h`, `y`, or `w`, as these don't really make a clear audible sound to a non-native speaker.
- Word components can't start with `xr`, `xl`, or `xn` because they are too hard to pronounce.
- Words can't have `r*r` in them because it's also too hard to pronounce.
- You can have "consonant clusters", like `str` in "string", or `pl` in "plan".
- There can only be one vowel between consonants. That is, there are not sounds like `oi` and `ao`.
- On even-syllabled words, the stress falls on the last vowel. So if it's "tenak", it would be pronounced "tenAK".
- On odd-syllabled words, the stress falls on the second to last vowel. So if the word is "tenakan", it would be pronounced "tenAKan".

So here are a few basic words:

- `bam`: create
- `dip`: tree
- `dram`: purple

These word forms are in their "base" form. You can tell because they start and end with a consonant. As they are in their base form, they mean simultaneously they are a noun, verb, and feature (this concept is kind of difficult to grasp). But you can easily convert them to the more familiar nouns, verbs, and features (word "modifiers" like adjectives and adverbs), by adding a 1-letter suffix to the end. So we have:

- `bami`: create (verb)
- `dipa`: tree (noun)
- `dramo`: purple-like (adjective)

That is:

- `-i` suffix creates a verb.
- `-a` suffix creates a noun.
- `-o` suffix creates an adjective or adverb.
- `-u` suffix creates an anchor or focuser ("swivel")

Things are broken down into 3 categories:

1. Objects (nouns)
2. Actions (verbs)
3. Fusions (relations/modifiers like adjectives and adverbs, and determiners and the rest of grammatical parts of speech)
4. Swivel (pronouns, prepositions, determiners, etc.)

Then we have more complex prefixes and suffixes, like we do with English. In English we have prefixes like "bi-" meaning "two" ("biweekly"), or "un-" meaning something like "not" ("unlikeable"). In English, we also have suffixes like "-tion" meaning something like "the result of applying an action" like "creation", or "or" meaning "the person or thing who performed this action" like "creator". We can do pretty much the same thing in Term script. However, unlike in English where sometimes the base word is modified before attaching the affix (like "create" drops the "e" to make "creat" before adding the "-or" to make creator), we don't modify the base form at all in Term. Instead, you simply add the appropriate vowel "separator", depending on if the base is being treated as an "object" (noun), "action" (verb), or "feature" (adjective/adverb), and the appropriate follow-up word. All you are doing is attaching more simpler words onto the base word, separated by vowels. That's pretty much it.

So for example, we have these:

- `bami`: "create"
- `bamiho`: "created"
- `bamiha`: "creating"
- `bama`: "creation"
- `bamayoga`: "creationism"
- `bamawa`: "creationist"
- `bamawaya`: "creationists"
- `bamaya`: "creations"
- `baminado`: "creative"
- `baminadoyo`: "creatively"
- `baminada`: "creativeness (state of being creative)"
- `bamivana`: "creativity (result of being creative)"
- `bamivanaya`: "creativities"
- `bamiwa`: "creator"
- `bamiwaya`: "creators"
- `bamiveda`: "creatology"

Notice how on the adverbs like "creatively" (ends in "-ly"), we add `-yo`. Well basically, all words follow similar patterns. But it is not always so straightforward how to translate an English word to Term, as English "base" words are not always nouns, sometimes they are verbs, sometimes adjectives, maybe even sometimes adverbs, or other parts of speech. Then English derives other words from those weird bases, and it gets complicated what is what. So if you have any questions on how to translate a specific word, please don't hesitate ot ask.

Oh, one more common case to note. The past tense is marked by `-ha` ("created" is `bamiha`), the currently active tense (symbolized by "-ing" in English) is marked by `-ho` ("creating" is `bamiho`), and the future tense ("will x" in English) is using `-hi` ("will create" is `bamihi`).

There are no other sorts of word "inflections" or "conjugations" like you find in Latin or Spanish or Finnish or other languages, Term tries to be as atomic as possible, by keeping everything as separate words. However, it is nice how we are able to form longer words from Latin/Greek in English (like "hydrogen" is really "hydro" + "gen", meaning "water generating"), so Term makes it possible to construct longer words from parts. For example, the word for "kilometer" (which is "kilo" or "thousand" plus "meter") is `kil` + `mirt` or `kilomirta`.

In the end, there are these "base" word forms:

| pattern | sounds | syllables | example |
|--------:|:--------|:----------|:--------|
| `cv` | 2 | 1 | bo |
| `cvc` | 3 | 1 | dip |
| `ccvc` | 4 | 1 | blap |
| `cvcc` | 4 | 1 | hold |
| `ccvcc` | 5 | 1 | grasp (all vulgar words fall into this category so as to not pollute other areas) |
| `cvcvc` | 5 | 2 | tikan |
| `ccvcvc` | 6 | 2 | trikan |
| `cvccvc` | 6 | 2 | kitxen |
| `cvcvcc` | 6 | 2 | tikatx |

The most common are `cv`, `cvc`, `ccvc`, `cvcc`, and `cvcvc`. The rest hold very few words matching that pattern, but they are there for completeness. In total this gives around 150,000 possible words. Then these word "bases" can be combined to form more complex concepts, like the Latin/Greek names used in the biological naming conventions, or as described earlier. So we have 150k foundational concepts, which can be combined in a seemingly endless combination to give many more words. Then those words can be combined into sentences, to give unlimited meaning like regular natural languages.

Out of the 150k foundational concepts, only an estimated 25k should be necessary to ultimately use, while realistically only 5k should be necessary for everyone to understand to have a good reach and rich understanding of things. The remaining 125k shouldn't really even be necessary to use. Instead, these base words should be combined to make compound words. Then you can understand the compound words in part by understanding their components, at least to start, before thinking of them as a whole. To give you a sense, 150k^2 is 22.5 billion possible words, while 5k^2 is 25 million words, that is a huge set of possible words! If we do 5k^3 (3-word compounds), that is 125 billion words! Plenty to capture knowledge in a concise way.

Here is a table of the known common word suffixes in Term.

| suffix | meaning |
|-------:|:--------|
| `-i` | converts words to verbs/actions |
| `-a` | converts words to nouns/objects |
| `-o` | converts words to adjectives (noun/object modifiers) |
| `-ya` | plural tense "-s" on nouns/objects like "trees" |
| `-wa` | possesive ("the bird's food") |
| `-waya` | possesive plural ("the birds' food") |
| `-iha` | past tense "-ed" like "created" |
| `-ihi` | future tense like "will create" |
| `-iho` | currently active tense "-ing" like "creating" |
| `-wi` | actor of the verb/action like "creator" or "engineer" |
| `-wo` | receiver of the verb/action like "createe" |
| `-yo` | converts words to adverbs (verb/action modifiers) |
| `-vula` | result (-tion) |
| `-xama` | the state of being x (-acy, -ness, -ship) |
| `-nala` | period of x (-hood) |
| `-hena` | (-ment) |
| `-pata` | act of |
| `-lami` | do like x |
| `-yoga` | practice of focusing on x (-ism) |
| `-vana` | having the nature of (-ivity, -ity, -ance) |
| `-fina` | belief in x |
| `-hona` | place x |
| `-zira` | pertaining to x (pleasantry) |
| `-doma` | area or state of being (-dom) |
| `-veda` | study or science of (-ology) |
| `-tula` | it's a tool (zipper) |
| `-rata` | the x action process |
| `-lena` | the nature of doing x (-ence) |
| `-mona` | featuring x |
| `-moxa` | the model of the action ("the transform", "the create") |
| `-kosa` | disease (-osis) |
| `-duka` | thing (hatchling) |
| `-kana` | ability (-ability) |
| `-kuna` | -ableness |
| `-xito` | shaped |
| `-gara` | language (-ese) |
| `-kano` | capable of being (-able) |
| `-nado` | having some aspects of (-ish) |
| `-falo` | full of (-full) |
| `-laso` | less of (-less) |
| `-tazo` | very much of (-some) |
| `-ravo` | reminiscent of (-esque) |
| `-maro` | more (-er) |
| `-miso` | most (-est) |
| `-tubo` | over (overburden) |
| `-yipo` | resembling (-istic) |
| `-tevo` | relates to (affectional) |
| `-zuno` | -wise |
| `-mavo` | loving (-phile) |
| `-firo` | hating/fearing/resisting (-phobia) |
| `-pati` | do like |

For names, use `-e` or `-u`. For long words, use a `:` colon to separate them.

Here are some common prefixes.

| prefix | meaning |
|-------:|:--------|
| `mes-` | different |
| `gag-` | opposite (anti) |
| `baq-` | self (auto-) |
| `sus-` | beyond (extra-, hyper-) |
| `tap-` | subtract (wi) |
| `pag-` | undo |
| `vim-` | exceed (super) |
| `rov-` | below (sub-) |
| `wol-` | mesh (inter-) |
| `nan-` | not (un-, -im) |
| `yap-` | all (omni-) |
| `tan-` | before (pre-) |
| `sin-` | after (post-) |
| `sem-` | same (sym-) |
| `sup-` | above (super) |
| `zuz-` | repeat |
| `zig-` | equal (iso-) |
| `bis-` | across (trans-) |
| `dit-` | distance (tele-) |
| `geno-` | without |
| `nivo-` | with (con-) |
| `funo-` | within (endo-) |
| `rino-` | again (re-) |
| `reso-` | partial (semi-) |
| `sudo-` | somewhat (pseudo-) |
| `medo-` | thing about the thing (meta-) |

**Note**, there can become ambiguities in compound words, which is why we have the `-wi-` infix. You probably won't have to worry about this unless you are working on constructing or cleaning up _compound words_, but it is here for completeness. For example, say we have these 4 words:

- bib
- pap
- bibap
- bibab

We can form these sorts of compound words out of them:

- `bib` + `pap` = `bibapapi`
- `bib` + `bipap` = `bibabipapi`

However, we run into a problem:

- `bibab` + `pap` = `bibabipapi`

That is, the two different forms end up with the same result! That is, these two are equal when combined into one word:

- `bibab` + `pap` = `bib` + `bipap` = `bibabipapi`

We can get around this with our handy-dandy `-wi-` infix, for disambiguation. We plug it in between the two words, like this:

- `bibab` + `wi` + `pap` = `bibabiwipapi`
- `bib` + `wi` + `bipap` = `bibawibipapi`

They are not the same anymore, woohoo!

This is also a problem with larger words, such as combining a 5-cvcvc word with a 3-cvc word, which is equivalent to combining 3 3-cvc words.

- `bipav` + `tikal` = `bipavotikala`
- `bip` + `vot` + `kal` = `bipavotikala`

Just seeing `bipavotikala` you wouldn't know if it was 5-3, 3-5, or 3-3-3, so  you have to add the infix whenever combining words. The only time you don't have to use the infix is when you combine two 1-syllable words, as there is only one way to parse it.

## Changing Between Objects, Actions, and Features

So things typically start being modelled from _reference points_. As such, in our mind we make the default either an action (verb), an object (noun), or a feature (adjective). Then there are specific common transformations we do from this default to reach other word forms that are related in meaning.

The first example is in English and is the word "trap". In this it is hard to say without doing a study what comes first, the noun ("a trap") or the verb ("to trap"). We don't have a -tion ending for trap because there is no result of trapping something, you have the trapped, but not a trapping result object. So we just say trap. But a trap is an object that performs trapping (a trapper?), while to trap is to apply a trap something. So they are two different focuses, and the object is not on the result of the action, hence no -tion. The object that performs the action is given by "-tula".

The second example is "create". This definitely starts as a verb. We have a derived noun/object "creation". This is the result of the create action. We mark this with "-xama". We can also talk about the more obscure "create" object, "the create". This is at first hard to imagine, but thinking closer we realize it is talking about the _mental model of create_, the create model so to speak. We mark the mental model with "-moxa".

The next example is "transport", which is an action. This has the -tion form ("transportation"), which is not the result of the action but the action field, the action industry, the abstract action or action class (action as a whole). Using -tion as the ending makes it difficult to see the actual underlying meaning, but now it is a little bit more clear. So we give this a separate ending, that which means "action class", "-kiqa".

But then what is the noun form vs. the verb form of every object in general? How can we arrive at a noun form for every word base? That should be a contextual and cultural decision, basically picking the default meaning (is it a "-xama" or result of an action, or a "-kiqa" abstract action class, or is it the model of the action "-moxa"). Whatever is the norm to how you think about the corresponding action is how you pick the object. But what about things which are object focused, like "tree"?

A tree is an object by default. But you can convert a tree to a verb "to tree" or "treeify". But what does this mean? We can provide it any meaning we'd like, for example "to grow like a tree", or "to live off light like a tree", or "to be green like a tree", or many other possibilities. Again, we go with convention and pick the simplest thing, to grow like a tree. Well, the result of growing is the tree itself, so we are back to "tree" again, just deriving it in reverse! So we really have "treeifytion", which is equal to "tree".

Now what about features (adjectives), like "warm"? We can convert warm to a verb/action with -ify, "warmify", meaning "to make warm". The "end result", now, is like we would expect, a "warmification". So we got back to "the end result" idea, from the feature. But we don't much talk about "warmification" (and probably instead call it "warming up"). We can talk about "the warm", like the warm _things_. This is not the result of being warm, but referencing warm objects. We reference this with "-dukaya", things (actions and objects and features). So we would say "wormodukaya" to mean "the warm". So again, by convention this is how we think of the default for the warm object reference.

We also have "-ness" for adjectives. The adjective "trivial" (an easy to do thing) can be made into a noun with "-ness", meaning "the state of being trivial". The state of being something is represented with "-nesa".

Considering state, we have things like "-ship" in "friendship". This is the abstract concept of being a friend. That is, it is the friend relation. It is the object of a friend action, the result of becoming friends is the friendship. So it is the same as "-tion", except "-tion" is applied to verbs, while here we are focusing on nouns.

Then we have "-hood" like "neighborhood". A neighbor is an object (thing), in relation with other neighbors. The neighborhood, then, is the area in which neighbors exist. It is the neighbor area, or neighbor space. Another example of "-hood" is manhood. A man is an object, and manhood is the nature of being a man. That is, it is "man nature". So there are at least two different concepts underlying "-hood", one of space (which is similar to kingdom), and one of nature. We call the space one "-doma", and the nature one "-vana".

Next we can move to verbs again, focusing on "-ity" or "-ivity", like "activity" or "creativity". To act is a verb, and just saying "act" defaults to a verb. Adding "-ivity" makes the verb a noun, and in terms of act it doesn't mean "the act", which is also a common noun, but "the nature of act". Likewise, "creativity" implies the "the nature of create". So again, this leads to "-vana".

We can work on "-ance" too, like "observance". This is clearly an extension of the verb "observe", but is a noun. The observance is the act of observing. The act of doing x is represented with "-pata". This is different from the "result of doing x", and so is not "-xama".

We can try "obedience" too, with the "-ence" ending. This is based on the verb "obey", and is the nature of applying the obey action regularly. Another is "insistence", which is the nature of applying the "insist" action regularly. So "-ence" is the nature of doing x, which "-ance" is the act of doing x. The nature of doing x is "-lena".

Then we have an easier to comprehend on, the "-ism" ending like "activism" or "creationism". Creationism is the practice of believing in creation. Activism is the practice of acting. They are two slightly different meanings, the most general being the practice of x. But we can also have an ending for a "belief in x", that is "-fina". While the practice of x is "-yoga". Another is "altruism", where altruistic is the key default. Altruism is the practice of being altruistic, so it makes sense.

Another ending is "-acy", like "intricacy", based on the adjective "intricate", or being highly detailed. Intricacy is the abstract class of being intricate. So it is the class of being intricate, so it falls under "-kiqa".

Those are the key suffixes to be aware of, and also the fact that the "default state" of a words meaning can fall onto an action, object, or feature. And choosing which short derivations are used from this default base is based on convention, with the longer meaning spelled out in the 3-letter suffixes.

Let us try some other examples. The word "suspend" is an action, with "suspension" being a noun. It ends in "-sion" which sounds like "-tion". It means the result of suspending, so that fits the model.

So that's the gist of the major suffixes.

In the end, the -i, -a, and -o of actions, objects, and features are chosen to be the cultural norm of the related action, object and feature. Then to reach more specific or tangential actions, objects, and features, you can use the more specific endings.

The -a is the object if it is clearly an object, or the result of the action if it is clearly an action.

An "association" can be either the result of associating, or a general association between things, so those are two different endings. Likewise, "acceptance" can mean having the nature of accepting, or the actual acceptance.

## Word System

The words are broken into different categories:

- 2-letter (sounds)
- 3-letter (basic mathematical/computational model)
- 4-letter-1-syllable (extended mathematical model)
- 5-letter-1-syllable (taboo words)
- 5-letter-2-syllable (mind/experience/consciousness model)
- 6-letter-2-syllable (earth model)

So words like "tree" or "network" or primitive numbers go under the 3-letter words, words like "mind" and "feeling" go under the 4-letter words. Words like "body" or "liquid" go under body model. Words like "grasshopper" go under 5-2-syllable words.

## Loan Words

There are no loan words, all words must be translated to a nice meaning in Term.

For names, like translating Western names into Chinese, there are two parts, a first name and last name. Each should just be one or two words combined themselves, such as `mego:wolfana skagana` "Great-Wolf Eagle". You can match it to their personality, or their profession, desires, goals, aspirations, hopes, dreams, etc.. Make it simple, elegant, and meaningful. These are "common names".

All names for individual things should have a secondary globally unique slug within a certain "type" context. This is like saying "John Smith the American explorer".

For other words, you can translate them literally if and where it makes sense ("White House" as literally `witrano:hostapa`). For book titles, too, you can name them close to literal meaning or slightly alter them where appropriate. Try and keep proper names (like "World Wide Web") to under 3 separate words (each of which can be 2 or 3 sub-words). So `world-information-network` sort of thing.

As we figure out the ideal name for someone, they might have multiple different names as we add better ones which more nicely capture their essence. So each person has a "main" or "canonical" name, which may be updated as new names are added. But you can always access them by their old name.

- english: `higlexowa` (angle)
- arabic: `dizartowa` (desert)
- jewish: `djuwixowa` (celebrated)
- islamic: `hizlamowa` (submission)
- buddhist: `budistowa` (enlightened)
- hindu: `hinduzowa` (river)
- sikh: `siksanowa` (disciple)
- zoroastrian: `vrido:karzanowa` (old camel)
- taoist: `bweno:pacowa` (good path)
- christian: `krisanowa` (anointed)
- believer: `blivowa`
- clam: `klamona`

## Numbers

Numbers are written using the consonant symbols prefixed by a "a" for decimal and "i" for hexadecimal. Instead of infix notation for addition and the rest, you use function notation like with programming languages.

1. `han` (`h`)
1. `zen` (`z`)
1. `dob` (`d`)
1. `san` (`s`)
1. `laf` (`l`)
1. `kam` (`k`)
1. `viv` (`v`)
1. `xab` (`x`)
1. `fet` (`f`)
1. `nas` (`n`)
1. `bid` (`b`)
1. `cuk` (`c`)
1. `mod` (`m`)
1. `raf` (`r`)
1. `tic` (`t`)
1. `wez` (`w`)

So the number 102 in decimal is `azhd`, and 24 in hexademical is `izf` (0x18).

## Punctuation

You have () parentheses and \<\> quotes and the slash / for how you would use them in English. The colon `:` is for combining words into a single whole.

## Summary

So to summarize, if how the words are structured/made makes sense to you, then please, it would be of great help to write translations of words into Term from English, using the above rules. If anything doesn't make sense to you, like it's unclear how to translate some specific case, or you have found a new case or suite of cases (phew!), please reach out so we can figure out how they should be represented in the Term language and we can get that solved for you so you can continue on.

If there's anything we can add to this guide, or anything at all you would like to improve or tell us about, please reach out to us directly through whatever means you are most comfortable with, or through the [Conlang StackExchange](https://conlang.stackexchange.com/) or the [Conlang Facebook Group](https://www.facebook.com/groups/Conlang).

But anyways, thank you for reading this and hopefully things makes sense. Term is pretty much solidified in terms of its word formation patterns, so we can be off to the races in building a large list of words and concepts translated into Term. In the end, anyone is free to use the word lists for whatever purpose following the license, and even we can use this word list and translation into the more structured Term language, to try and see if we can solve some disparate interesting problems.
