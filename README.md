# The General Major Mnemonic Memory System
For easier remembering of numbers and dates, or to create memory pegs. 

The General Major system is similar to other Major systems, but 'R' sounds have no impact on the mnemonic associations. The helps speakers of many varieties of English where certain R's are not pronounced. Also we group 'th' sounds together with V and F sounds.

## Basics 

To use a word as a mnemonic, replace these sounds with these digits:

|Sound |Digit |
| --- | --- |
| S Z | 0 |
| T D | 1 |
| B | 2 |
| M | 3 |
| N | 4 |
| L | 5 |
| CH SH ZJ | 6 |
| K G | 7 |
| V F TH | 8 |
| P | 9 |
| vowels | ignored |
| R W H Y | ignored |

Notes:
* Other sounds are ignored: R, W, H, Y (as in yolk), and vowels
* Double letters are treated as a single letter (as it's based on pronunciation not spelling)
* Unlike other Major memory systems, there is no /r/ (more on this below)

## Usage Example

```
bentley uranium possum
2-415-- ---4--3 9-0--3
```
Say you want to remember the number 241543903, a famous meme number. Once you've learned the sound-digit associations, you can remember 241543903 as easily as you can remember a story about a Bentley carrying uranium which swerves to avoid a possum. To remember this story better, you'll need to add more details to the bentley-uranium-possum story (google: "elaborative encoding" for more information on this). You'll also have to practice (do "reviews") to help make it stick. Like with flash cards or something. Yeah, it's not magic.

## Peg noun example tables

### Single digit words

| 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ace | hat | bear | emu | hen | owl | jay | kiwi | fae | hippo |

### Two-digit words

|  | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
| ---: | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **0** | sauce | suit | sub | sumo | snow | seal | sushi | sock | sofa | soap |
| **1** | dice | dodo | tub | dome | tuna | drill | torch | taco | dove | trap |
| **2** | bus | bat | bob(sled) | bomb | bunny | bell | badger | bug | beaver | beeper |
| **3** | moose | meteor | moby (whale) | mime | moon | mole | match | mug | (ear)muff | map | 
| **4** | nasa (rocket) | newt | nib | gnome | onion | anole | nacho | nuke | knife | nope (snake) | 
| **5** | louse | lady(bug) | lube | lime | lion | lily | leech | lock | lava | leaper (zombie) | 
| **6** | cheese | cheetah | cherub | chime | ocean | chili | cheshire (cat) | shark | chef | sheep |
| **7** | goose | goat | crab | grim | crown| gorilla | cash | kayak | quiver | capy(bara) |
| **8** | fez | ferret | furby | firearm | raven | (pea)fowl | fridge | fig | fifa | vape |
| **9** | Pisa (tower) | parrot | probe | puma | pony | pearl | peach | pig | puff (pastry) | pawpaw |

### Skeleton stations

Words starting with 1 to 9, from top (0) of the head to the feet (9=peds) and ground (0=sand), to use as pegs to file and remember list items.

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 | 
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| top | brow | mouth | neck | liver | \[hip] joint | \[knee] cap | fibula | peds (feet) | sand (ground) |

More mnemonic words and their General Major digits can be found in [`myna-system-max-2-digits.json`](https://github.com/pengowray/myna/blob/main/myna-system-max-2-digits.json) in this repo.

## To do

TODO: 
- [ ] Other ways to use the General Major system
- [ ] Other ways to learn the General Major system
- [ ] A web page where you can translate between numbers and mnemonic words
- [ ] Gather feedback 
- [ ] Explain better / more
- [ ] Why "General Major"?
- [ ] Add IPA to ambiguous words in json files
- [ ] Add encoding table in json files
- [ ] Using with other memory techniques such as method of loci, PAO (person, action, object), link system, etc

## Dictionary files

* The dictionary files in this repo are human readable json files with the number values associated with dictionary words, based on pronunciations. 
* Ambiguous words (for which multiple pronunications were found and they match different mnemonic numbers) were removed from the main list and are listed later in the file as ambiguous words.
* The format is not finalized and may change
* The 99-digit file contains all the information from the others (other than different statistics), the 2-, 3-, and 4-digit files are smaller, for your convienence.
* There's also other files with the legacy Major system if you're into that.
* The words are based on `cmudict-en-us.dict.txt`

## Comparison to the Legacy Major system

The Legacy Major system, which is popular with many American memorists, requires the user to either use or think with a "rhotic" accent, differenting /r/ sounds which may not exist in their own English accent. For example, in my Australian accent, the word "nurse", when spoken aloud, has no "R", so using the Major system requires mentally flipping between the sounds of a word and the spelling, either that or switching mentally to a rhotic accent (which, for me, means thinking in Scots English). This mismatch or added overhead leads to more errors and difficulty with using the Major memory system.

This General Major system removes this mental hurdle by treating all /r/ sounds the same as vowels. In other words, ignoring them. B and P sounds, which are combined in the Legacy Major system, are split up to fill the space. Also the "th" sound are moved away from being grouped with "T" and "D" sounds to be with the F & V sounds, better matching English accents which group these sounds together (such as Cockney), and a little more evenly distributing sounds across numbers. For no reason other than aesthetics, The N sound was moved to 4 to make space for B at 2. This allows B to be 2, and for M to be followed by N, like in the alphabet. It would have forever been itching at me if I had not made 2 B.

As a side effect of the changes, many more words can be used as mnemonics for 2-digit numbers, which are the most used for mnemonics and can also be used for pegs (e.g. for mental lists with up to 100 items)
