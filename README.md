# clew

## prologue

today, i received mail from a Jehovah's Witness imploring me to look for answers in the Bible.
specifically, Romans 15:4. i typically discard such mail, but upon discovering the reference-filled,
deeply-interconnected Bible available at [their website](
https://www.jw.org/en/library/bible/study-bible/books/romans/15/#v45015004)... i felt called to
explore. so many _connections!_ how could i resist?

my day of digging was interesting and enriching, though made far more tedious by the lengthy
reformatting process. alas! version zero-point-one was rapidly assembled in Microsoft Word.
_gratitude_ for the ease of the tool. but _woe_ to those who do not _begin_ in Markdown. eat that
elephant before it grows.

but the _results_ of my effort \
were not the only shining facet

the _process_ \
(you shall find) \
is elegant-- \
_**divine**_ \
dive you into the depths \
then begin your climb \
the labyrinth calls \
_grasp my clew twine_

## execute($tributary, $YOU) =>

this elegant process \
though your thoughts may... _resist_ \
**here** we _recurse_ \
through any `verse` you wish:

* // _perhaps you have risen_ \
  // _perhaps you have not yet been_ \
  // _it matters not_ \
  // _**here** we begin_
* read the `verse`
  feel it out
* write it down \
  give it _the format_ \
  (for _this:_ stay close to mine)
* _**emph** a size_ \
  what it means to YOU
* see an {alternative}? \
  need some {context}? \
  add it! this \
  journey _belongs to YOU_
* follow the footnotes \
  but! only verses that _**shine**_ \
  (whatever the rest?) \
  ((wither and die))
* indent!
    * for
        * we
    * will
        * _step!_
            * into new
                * _depths!_
                    * of _**recursion!**_
* for each `shineVerse` \
  that showed you some _Light:_
    * // _you will be **back** here_ \
      // _before you **pass** here_ \
      // _so that it can flow just let it go_
    * start _simple process_ again \
      input anew! \
      { read the `shineVerse`, continue... }
    * // _by the time that you reach **here**_ \
      // _`shineVerse` will be in full bloom_ \
      // _you've already traveled all its footnotes_ \
      // _its depths no longer loom_
    * now, on to the _next_ one \
      [this relentless train] \
      execute _for each_ \
      til no `shineVerse` remain
* many shines or none \
  you'll arrive **here** all the same \
  you have now traversed everything \
  of `verse` that _shined_ this day \
  a simple benediction \
  your works, now: _to the sky_ \
  within _**holy recursion**_ \
  **now** is time to { _rise_ }
* unindent!
    * for
        * we
    * have
        * _stepped!_
            * up from the
                * _depths!_
                * on to the next
                    * one footnote alone
                * a final sibling
            * back up to the parent, sibling of "stepped!"
                * _three_ feet
                * this time
                * have _shone_
            * // but! no further siblings, so...
        * _rise_ yet again
    * _rise_
* _**LET GO**_

## _behold:_ the black core

```c#
public static VerseTree ProcessVerse(Verse v) {
    VerseEntry entry = Annotate(Emphasize(Format(Feel(Read(v)))));
    var childTrees = new List<VerseTree>();
    
    foreach ( Verse fv in v.Footnotes.Where(HasShine) ) {
        childTrees.Add(ProcessVerse(fv));
    }
    
    return new VerseTree(entry, childTrees);
}
```

## tributary

### [`Romans 15:4`](https://biblia.com/books/kjv1900/Ro15.4)

For whatsoever things were _written for our learning_ { or _instruction_ }, were written
foretime `…`

* [`1 Corinthians 10:11`](https://biblia.com/books/kjv1900/biblekjv.1Co10.11)
  Now all these things happened unto them for _ensamples_ { or _examples_ }: and they are written
  for our _admonition_ { or _learning_ }, upon whom the _ends of the world are come._ `…` `13.5`
  but will with the temptation _also make a way to escape,_ that ye may be
  _able to bear it._

* [`2 Timothy 3:16`](https://biblia.com/books/kjv1900/2Ti3.15)
  _All_ scripture { scripture in its every part } is given by _inspiration of God,_ `…`

    * [`John 14:26`](https://biblia.com/books/kjv1900/Jn14.25) `JW`
      But the _Comforter_ { or _Helper_ }, which is the Holy Ghost, whom the Father will send in my
      name, he shall _teach you all things,_ and bring _all things to your remembrance_ { bringing
      to living consciousness what lay like slumbering germs in their minds }, whatsoever I have
      said unto you.

        * [`Matthew 10:19`](https://biblia.com/books/kjv1900/Mt10.19) `JW`
          But when they deliver you up, _take no thought_ { do not be _anxious_ } how or what ye
          shall speak { or in which _manner_ }: for it shall be _given you in that same hour_ what
          ye shall speak. `20` For it is not _ye_ that speak, but the Spirit of your Father which
          speaketh _in_ you.

            * [`Luke 21:13`](https://biblia.com/books/kjv1900/Lk21.13)
              And it shall turn to you for a testimony. `14` Settle it therefore in your hearts,
              _not to meditate before_ what ye shall answer: `15` For _I will give you a mouth and
              wisdom,_ which all your adversaries shall not be able to gainsay nor resist.

        * [`John 16:7`](https://biblia.com/books/kjv1900/Jn16.7)
          Nevertheless I tell you the truth; It is expedient for you _that I go away:_ for if I go
          _not_ away, the _Comforter_ { or _Helper_ } will _not_ come unto you; but if I depart, I
          will send him unto you. `…` `12` I have yet many things to say unto you, but ye _cannot
          bear them now._ `13` Howbeit when he, _the Spirit of truth,_ is come, he will guide you
          into _all truth:_ for he shall not speak of { or _from_ } _himself;_ but whatsoever he
          shall hear, that shall he speak: and he will shew you _things to come._

            * [`John 14:17`](https://biblia.com/books/kjv1900/Jn14.17)
              Even the Spirit of truth; whom the _world cannot receive,_ because it seeth him not,
              neither knoweth him: but _ye_ know him; for he dwelleth _with_ you, and shall be _in_
              you.

        * [`2 Peter 1:20`](https://biblia.com/books/esv/2Pe1.20)
          knowing this first of all, that no prophecy of Scripture comes from _someone’s own
          interpretation._ `21` For know prophecy was ever produced by the _will of man_, but men
          spoke _from God_ as they were _carried along_ by the Holy Spirit.

    * `…` and is profitable for _doctrine_ { or _teaching_ }, for _reproof_ { or _refutation_ },
      for _correction,_ or _instruction in righteousness:_ `17` That the man of God may be perfect,
      thoroughly furnished unto _all good works._

`…` that we through _patience_ `…`

* [`TODO`](#)

`…` and comfort of the scriptures might have _hope_ { the motives that prompted them, the spirit in
which they were endured, and the general principle involved in His whole work—self-sacrifice for the
good of others—furnish our _most perfect and beautiful model_ }.

## trivia

the tributary above is the _second version_ of this research pathway. during my first pass, i used
the version of the Bible presented by the Jehovah Witness website, and its linked references.
however, i wished to be nearer to the source material, so i switched to the King James version, with
text and references provided by [Biblia](http://biblia.com). the `JW` flag indicates a reference
found only at the Jehovah's Witness website.

## pause system-functions

this... _became_ far more \
than i would have guessed \
today... i pushed _into_ \
balanced madness \
and set any intention aside \
[shall i respond to letter??] \
**stopped _trying_ to _decide_** \
suddenly! \
[nail-carved-wall] [bloom] \
_the reclusive recursive clew!_

_so:_ \
i did not manage \
to finish today \
the docx/JW \
to md/KJ \
(will do this soon)
