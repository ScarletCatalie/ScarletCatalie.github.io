---
layout: post
---

<img src="https://raw.githubusercontent.com/ScarletCatalie/ScarletCatalie.github.io/master/assets/header_squids.png" alt=""><br>

Last Monday Rachel went back to work, and I found myself in a bit of a pickle. See, I'd started getting work lined up again, but at time of writing we're still sorting out all the deets (keep an eye out for cool developments soon, though!).

I still needed to get out of the house, mind. I'm still paying for the office down in Leith, and figured I might as well go and work on *something*. But while I'd created a cool environment in Unity over winter, I had no passion for making a "game" out of it.

As an experienced purveyour of YouTube garbage, though, I'd once again been deep in a Source Filmmaker kick. Flipping between [An0nymoose's incredible shorts](https://www.youtube.com/watch?v=I7Tps0M-l64), Maxime Lebled's [stunning Dota 2 films](https://www.youtube.com/watch?v=1HFBwMbJVAM) and some [adorable Splatoon shorts](https://www.youtube.com/watch?v=A6PkBTUaawE), I reckoned it was time I picked up animation again. After all, I'd created one walk cycle for a pre-Can Androids Pray¹ mech a few years back. How hard could it be?


I started, as you do, with a veemo.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">I spent all day learning walk cycles and - while I&#39;m definitely improving, there&#39;s nothing to show for it so uhhhhh<br><br>uhhhhhhhh<br><br>🐙 <a href="https://t.co/AGOn5kvrKp">pic.twitter.com/AGOn5kvrKp</a></p>&mdash; nat clayton (@ScarletCatalie) <a href="https://twitter.com/ScarletCatalie/status/1214567080629981186?ref_src=twsrc%5Etfw">January 7, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Look, alright. I know the software has some baggage. Take a cursory glance at the hashtags and Steam Community hub, and there are basically three kinds of SFM creations in 2020: high-contrast gamer wallpapers, hardcore pornography, and squidposting. I'll happily admit to the latter over the other two, mind. I'm in a bit of a massive Splatoon 2 kick² right now. Don't @ me.

But SFM also gives me a platform to explore animation with ease. I don't need to mess around creating my own models or rigs. There's a bounty of semi-legal assets from beloved IP at my fingertips, letting me get right down to the business of creating a scene. From my brief encounters with other animation software (Blender and Maya), it seems pretty similar anyway.

After a day of messing with the motion editor and basic smoothing, though, I found I wasn't making a huge amount of progress. I'd glanced at Valve's tutorials, but I wasn't following them. If I was gonna get anywhere, though, I needed to get serious.

I picked something fundamental to work on - I'd try and get a walk cycle going, using [this fantastic tutorial](https://www.youtube.com/watch?v=bUvTEPw3FAk) from Jesse Baumgartner.

The first attempt was... stiff.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">We&#39;ll work on the arms later. <a href="https://t.co/pWgfjfsHqC">pic.twitter.com/pWgfjfsHqC</a></p>&mdash; nat clayton (@ScarletCatalie) <a href="https://twitter.com/ScarletCatalie/status/1214941722024796161?ref_src=twsrc%5Etfw">January 8, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Okay for a first draft, I think. But I was discovering an issue with the way Baumgartner blocks his poses - all at once, each keyframe at a time. Fair enough, I figure, but I was finding myself easily stumped, struggling to keep track of arm/spine/leg/head movements all at once.

So I started again, this time focussing on one region at a time. I'd get the legs - arguably, the most important part of a walk cycle - nailed down first, then build myself upwards through parts of the body.

I think it paid off well - this Soldier, for example, doesn't look nearly as constipated as his Sniper companion.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">a little bit more swagger, a little bit of light. <a href="https://t.co/zUbS7URIcq">pic.twitter.com/zUbS7URIcq</a></p>&mdash; nat clayton (@ScarletCatalie) <a href="https://twitter.com/ScarletCatalie/status/1214981602528432130?ref_src=twsrc%5Etfw">January 8, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

You'll notice the low-angle camera shot obscuring the feet, mind. While it definitely looks more natural, I found foot tracking was very poor. Feet sliding, he didn't feel physically connected to the ground.

So I tried another approach I'd seen kicking around. I moved a new character step by step, placing the feet and pelvis first before building the rest of the motion around that. That did it, and while this Demoman looks (fittingly) drunk, he's connected firmly to the ground. His footsteps make *sense*. I even returned to the motion editor to add a little character.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">I&#39;m still... animating... help <a href="https://t.co/2kBzLrkJ0c">pic.twitter.com/2kBzLrkJ0c</a></p>&mdash; nat clayton (@ScarletCatalie) <a href="https://twitter.com/ScarletCatalie/status/1215035460847882240?ref_src=twsrc%5Etfw">January 8, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

At this point, I was feeling confident enough to leave the comfortable, grid-marked safety of SFM's stage. My heart's in scene-building, and I set about putting what I'd learned into practice with a short squidpost. Another walk cycle, this time with a bit of a meandering pace and some secondary motion.

Now that I'd gotten more comfortable with the editor, the process was speeding up: I did the following in a few hours after returning from the office. Getting the base walk took about two hours, and then the rest of the night was spent tidying up - making sure feet didn't slide, preventing the basic biped rig from skewing knees into the stratosphere.

It's far from perfect, but it's the first piece I created that felt wholly convincing. Everything I've done up to this was practice, an exercise in something. Here, I'd created a mood I wanted to explore.

<blockquote class="twitter-tweet" data-conversation="none"><p lang="en" dir="ltr">All building off this from last night. <a href="https://t.co/Hsg9GXgo0N">pic.twitter.com/Hsg9GXgo0N</a></p>&mdash; nat clayton (@ScarletCatalie) <a href="https://twitter.com/ScarletCatalie/status/1215607045090631681?ref_src=twsrc%5Etfw">January 10, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

The next day, I decided to push further into this (as I'd repeatedly refer to it throughout the day) *vibe*. I was a bit exhausted with walk cycles, so I started messing with smaller motions and - more importantly - environmental tricks.

I started work on a little slice-of-life sequence, an early morning commute for our Octoling friend here. Nothing too ambitious, just a series of short shots to sell that hazy dawn commuter feeling. Admittedly, I'm beyond proud of how well the train short works, using a simple repeating light sweep and some minor rotation in the carriage ahead.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Running off for the day, pretty chuffed with how these vibes are coming along.<br><br>Considering I installed SFM like, 4 days ago, it&#39;s no too shabby. Plenty of polish and work to do yet. <a href="https://t.co/fzI7EtfBYu">pic.twitter.com/fzI7EtfBYu</a></p>&mdash; nat clayton (@ScarletCatalie) <a href="https://twitter.com/ScarletCatalie/status/1215688683074080771?ref_src=twsrc%5Etfw">January 10, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

Again, it's far from done. A lot of secondary motion is missing, and I never got around to the animating the fourth shot that day. I'm still not quite at a point where I've created something I want to publish, but I'm (slowly, surely) getting there.

My biggest complaint against many other early SFM vids I catch online is the same thing I'm seeing in my own pieces, too - motion without momentum, characters moving too smoothly, without the weight and speed and start/stop of convincing human action. That's something I'm very keen on training myself out of.

I'm really happy with my progress over the last week, though. I usually hesitate over picking up a new hobby or skill - I feel I very quickly hit a point where I'm "okay" at something, whether that's an instrument or artistic discipline, but can't quite push myself into a level I'm proud of.  But animating in SFM makes a lot of sense to me right now. It's time-consuming but relaxing, complex but manageable, lots of tiny decisions and an endless well of things you can do a little better, given a little more time.

When I started this little dabble into Source Filmmaker, I didn't see myself taking it very far. Then I spent 40 hours in one week getting noticeable better. Right now, I'm having an absolute blast learning something and seeing myself progress. Creating enjoyable stories? Well, that's a whole 'nother hurdle, and we'll see if any good shorts ever actually come outta this adventure.

'Til then, I'm happy to keep improving my vibes.

<br>

¹ *Learning to animate that first Mech led directly to the development of Can Androids Pray, by way of a short Mech-Adventure demo. Somewhat ironically, Can Androids Pray is completely lacking in animated elements.*

² *(I touched on it in my [2019-in-games](https://scarletcatalie.github.io/blog/2019/12/22/Games-wot-I-played-in-2019) post, but I'm really, truly stuck deep into Splatoon 2. It's a hard love to reckon with, though. If I were younger, I'd happily be diving into forums and communities. But in my mid-twenties, with a modest Twitter following, deep hang-ups over things I've loved before and a strong uncertainty of what it actually means to be seen as an "adult", I still struggle to earnestly enjoy things.*

*That's, perhaps, something to write my way through another time.*
