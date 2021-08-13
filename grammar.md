this is a guide on grammar, so basically how to
use relationals to turn words into verbs, and
how to effectively attach particles to those
relationals to change their behaviour.
theres also some weird nuance to how relationals
affect
*each other* in a sentence

# relationals
relationals are the basic blocks that turn
words into verbs

there are multiple ways the lang could
potentially handle relationals.

one way is with [three relationals](#three-relational-system):
*existence,
posession, and causation.* this "3 relational"
version of the language would have
alot of versatility, especially as
the relationships between existence and
posession would be more robust.

its possible to build the language with
only [two relationals](#two-relational-system),
however.
this would be *existence
and causation*, with existence covering cases
of both instancing objects and declaring
possesion in the way of "noun1 exists within
noun2". this config has a little less
wiggle room, but you can pretty much
get your point across and theres less
redundancy. i like this one the most
bc i want the lang to be simple and elegant,
and if i can get away with two relationals
without causing more confusion than i solve,
then its a keeper.

its technically possible to have only one
super versitile relational.. but it requires
***word order***, something im choosing to
avoid for the sake of using word order to
denote *topical importance* (important
words first) instead of verb function.
i still wanna explore this tho cuz its super
interesting.

im also thinking of two ways to put the verbs
in the sentence.
1. attach them to the subject
  (`exist.basket bread` would mean
  basket has the existence of the bread in it)

2. attach them to the object
  (`basket exist.bread` would mean
  bread exists within the basket)

these both mean the same thing (the
basket has bread), but they got there differently.
im not sure which way i like better. im leaning
on v1.. but v2 aint far behind.

without further ado, lemme explain how the
relationals work, starting with the *two
relational system* (i will be demoing both
variants as well)

## two relational system

### variant 1: emphasis on subject
```
xeku
+ ku exists

xeku ko
+ ku has ko

xeku xeko
+ ku = ko

caku
+ ku enters

caku ko
+ ku causes ko [passively]

caku xeko
+ ku causes ko [actively]

caku xeko ka
+ ku gives ka to ko

caku xeko xeka
+ ku causes ko to = ka
```

### variant 2: emphasis on object
```
xe existence
ca causation

xeko
+ ko exists

xeko ka
+ ko exists within ka
- ka has ko (or properties of ko)

xeko xeka
+ ko and ka have the same existence
- ko and ka are the same
- ko is ka | ka is ko

xeko xeka ki
- ki has ko and ka?

caku
+ ku causes itself
- ku now exists
- ku enters the chat

caku ka
+ ka causes ku
- ka actively causes ku
- ka makes ku happen anew
- [cu.murder paya] would mean paya
  actively commits a new murder

caku xeko
+ ko's existence causes ku
- ko passively causes ku
- ko makes ku happen generally
- [ca.murder xe.paya] would mean paya
  passively commits murder (but isnt rn)

caku xeko ka
+ ka caused ku to be in ko
- ka causes ko to have ku
- ka gives ku to ko
```

## three relational system
there are 3 relationals:
+ existence
+ posession
+ causation

the relationals are listed in order of power,
with the first relational having the least power
and the final relational having the most.
power
dictates how relationals interact with one another,
as opposed to word order.
higher power relationals will always take affect
unto the verb of a lower level relational.
for instance if the relational of causation is
used in the same sentence as the relational of
existence, the relational of causation has affect
on the VERB OF EXISTENCE, and not on the objects
in the sentence.
this is why `exist.chair cause.cat cut` means
that *cat causes chair to be cut* and
not that *chair is a cat causing cut*

here is a breakdown of how each of these
relationals work individually, and i will dive
deeper into multi-verb sentences afterwards

**for these examples, i will be using placeholders
as the exact blocks havent been worked out**

`ko, ka, ku, ke, ki` will all be nouns used for
exampling purposes

```
xe existence (x is y)

xeko          : ko is topic
xeko ka       : ko is ka
xeko ka ki    : ko is ka and ki
xeko xeka ki  : ko and ka is ki
xeko xeka     : ko and ka are the same
```
```
po possesion (x has y)

poke         : ke has topic
- ?? idk
poke ka      : ke has ka
poke ka ki   : ke has ka and ki
poke poka ki : ke and ka have ki
```
```
ca causation (x caused y)

caku         : ku causes topic
+ ku becomes/enters
caku ka      : ku causes ka
caku ka ki   : ku causes ka and ki
caku caka ki : ku and ka causes ki
```
#### combining verbs
affecting existence
```
poke xeko    : ke owns ko
- ke has ko's existence
poke xeko ka : ke has ko being ka
- ?? idk

caku xeko    : ku causes ko to exist
caku xeko ka : ku causes ko to be ka
```
affecting possession
```
caku poke    : ku causes ke to have
- ?? idk
caku poke ka : ku gives ka to ke
- ku causes ke to have ka

caku poke xeko : ku causes ke to own ko
- ku gives ko to ke (the ownership, not
  the physical object)
caku poke xeko ka : lol
- ?? ku causes ke to have ko be ka
  - i literally cannot figure out wtf
    this would mean lol
```

# particles
particles are little blocks that go between
the verb and root that change how the verb
affects the sentence. an easy example is the
`negative` particle, which makes the verb mean
the opposite of its original meaning. for instance
`has.negative.noun1 noun2` would mean that `noun1`
DOESNT have `noun2`. here is a list of particles
and some more examples
```
no : negative
pa : past tense
fu : future tense
vo : volition
qe : equivalence
```
```
an example might be
xenoko : ko does not exist
sapako ka : ko used to have ka
safuko ka caku : ku will give ka to ko
```
volition is super important.
phrases are assumed non-volitional
unless tagged volitional [MIGHT CHANGE
IN THE FUTURE]

volition in causal verbs notates
that the causor intended the effect.
if john were to cause lisa to not exist
*non-volitionaly* (which is the default)
`exist.not.lisa cause.john`..,
that would mean he accidentally ended her
life. if john were to cause lisa to
not exist *volitionaly* `exist.not.lisa
cause.volition.lisa`.., that would mean
he sent that bich to the shadow realm

here are some more examples
```
xeko caku   : ku happens to make ko exist
xeko cavoku : ku makes ko exist intentionally

poko ka caku   : ku gives ka to ko (no intent)
poko ka cavoku : ku gives ka to ko (with intent)

