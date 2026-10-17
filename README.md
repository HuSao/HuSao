# 🎡 WheelPage — Small Tools I Enjoy Building

Hi, I'm Funny. I build small things for the web, mostly tools and games that people can open and use without much explanation.

[WheelPage](https://wheelpage.com/) started with a spin wheel. I wanted a place where I could type in a few options, press a button, and let the wheel choose one. It sounded simple enough, and the first version did exactly that.

Once the wheel was working, I began adding other tools. A coin seemed more convenient for two choices, dice made sense for games, and sometimes all I needed was a random number.

That's how WheelPage grew from one page into a small collection of browser tools.

## What You Can Do with WheelPage

### 🎡 [Spin the Wheel](https://wheelpage.com/) · [转盘](https://wheelpage.com/zh/)

This is where the project began. Add your own options, spin the wheel, and see where it lands. You can use it to pick a name, choose an activity, run a small raffle, or settle an everyday decision.

I spent time on the wheel's movement, option editing, colors, and mobile controls. A wheel is easy to understand, but getting it to feel right takes some work.

### 🪙 [Flip a Coin](https://wheelpage.com/coin-flip/) · [抛硬币](https://wheelpage.com/zh/coin-flip/)

For a decision with only two possible outcomes, a coin is usually enough.

Flip for heads or tails, then check the recent results and flip counts. There's not much to learn here, which is exactly how I wanted it.

### 🎲 [Dice Roller](https://wheelpage.com/dice-roller/) · [骰子](https://wheelpage.com/zh/dice-roller/)

The dice roller took more work than I expected.

Generating a random number is straightforward. Making a 3D die roll, collide with other dice, settle into a stable position, and show the correct face is another matter.

I used Three.js and Cannon-ES for the rendering and physics. The page supports D4, D6, D8, D10, D12, and D20 dice, with up to three dice per roll.

### ✊ [Rock Paper Scissors](https://wheelpage.com/rock-paper-scissors/) · [石头剪刀布](https://wheelpage.com/zh/rock-paper-scissors/)

Choose rock, paper, or scissors and play a round against the computer. There's also a best-of-three mode.

I kept this one close to the familiar game. Pick a move, see the result, and play again if you feel like it.

### 🔢 [Random Number Generator](https://wheelpage.com/random-number-generator/) · [随机数生成器](https://wheelpage.com/zh/random-number-generator/)

Set a range and generate one or more random numbers. It supports integers, decimals, unique results, and sorting.

Useful when you need random values without setting up a spreadsheet or writing a script.

### 🔘 [Online Counter](https://wheelpage.com/counter/) · [计数器](https://wheelpage.com/zh/counter/)

A click counter for keeping track of repetitions, quantities, or scores.

You can maintain separate counters, adjust the counting step, and review changes saved in your browser. I wanted something I could leave open while doing another task and return to without losing the count.

WheelPage also has [Español](https://wheelpage.com/es/) and [Русский](https://wheelpage.com/ru/) versions.

## A Little About Building It

WheelPage uses HTML, CSS, and JavaScript. The wheel uses LeaferJS, and the 3D dice use Three.js and Cannon-ES.

A lot of the work doesn't show up in the feature list. It's fixing touch behavior, adjusting animations, checking what happens when someone changes an option, or making a page work on a smaller screen.

I like this kind of work. The problem is small enough to understand, and there's usually something I can improve when I use the tool again.

---

# ⚡ PickTests — How Much Can You Really Test in a Browser?

[PickTests](https://picktests.com/) began with a different question: how fast could I react to something on the screen?

The first version of the reaction time test had a simple flow. Wait for the screen to change, click, and read the result in milliseconds.

After trying it a few times, I wanted to see more than one number. One attempt might be faster than the next. A personal best was interesting, but it didn't tell me much about the other attempts.

So I added multiple rounds and started keeping recent results.

Then I wondered what else could be tested with a small browser interaction. Memory was an obvious direction. Aiming, visual tracking, attention, and spatial thinking led to different challenges.

Those experiments eventually became a collection of human benchmark tests.

You can visit the [Human Benchmark](https://picktests.com/) or the [人类基准测试](https://picktests.com/zh/) homepage.

## The Tests

### Reaction and Aiming

**⚡ [Reaction Time Test](https://picktests.com/reaction-time-test/) · [反应测试](https://picktests.com/zh/reaction-time-test/)**

Wait for the screen to turn green, then react. You can test one round or complete five rounds to compare your fastest and average times. Recent results give you something to compare with the next time you visit.

**🎯 [Aim Trainer](https://picktests.com/aim-trainer/) · [瞄准训练](https://picktests.com/zh/aim-trainer/)**

Click targets as quickly and accurately as you can. This one adds mouse movement and target positioning to the challenge. Seeing a target and actually clicking it are two different steps.

### Memory and Attention

**🧩 [Sequence Memory Test](https://picktests.com/sequence-memory-test/) · [序列记忆测试](https://picktests.com/zh/sequence-memory-test/)**

Watch the tiles light up, remember the order, and repeat it. The sequence grows as you progress.

**🔢 [Number Memory Test](https://picktests.com/number-memory-test/) · [数字记忆测试](https://picktests.com/zh/number-memory-test/)**

Remember a number before it disappears, then type it back. A few digits feel manageable. Longer numbers make it much harder to keep every digit in the right place.

**👀 [Multiple Object Tracking Test](https://picktests.com/multiple-object-tracking-test/) · [多目标追踪测试](https://picktests.com/zh/multiple-object-tracking-test/)**

Remember several marked objects, follow them while everything moves, and find them when the movement stops. The interesting part is what happens when objects cross paths.

**🎨 [Stroop Test](https://picktests.com/stroop-test/) · [斯特鲁普测试](https://picktests.com/zh/stroop-test/)**

Read the displayed color rather than getting distracted by the word. The rule is simple, but conflicting information makes mistakes surprisingly easy.

### Time, Space, and Color

**⏱️ [Time Perception Test](https://picktests.com/time-perception-test/) · [时间感知测试](https://picktests.com/zh/time-perception-test/)**

Estimate a duration, reproduce an interval, or compare two stretches of time. You don't get to rely on watching a running timer.

**🧊 [Mental Rotation Test](https://picktests.com/mental-rotation-test/) · [心理旋转测试](https://picktests.com/zh/mental-rotation-test/)**

Look at 3D shapes and work out whether they represent the same object from different angles. It asks you to turn the shapes in your mind rather than on the screen.

**🌈 [Color Blind Test](https://picktests.com/color-blind-test/) · [色弱测试](https://picktests.com/zh/color-blind-test/)**

Identify subtle differences in color plates. The test includes numbers, directions, and zodiac patterns, with questions that adapt to your answers.

It's an online color-vision screening tool, not a medical diagnosis. Screen brightness and color settings can affect the result.

## Why I Keep Working on PickTests

The site has nine tests now, but adding another card to the homepage isn't the only thing I'm thinking about.

I'm also working on what happens after someone finishes a test.

A result is useful for that attempt. A previous result gives it context. If I measured 205 ms last time and 194 ms today, I have something to compare.

Some tests save recent attempts or personal bests in the browser. There's no account requirement, although that also means local results won't automatically follow you to another device.

For this kind of site, I prefer letting people start a test without making them register first.

---

# 🧁 2048 Cupcakes — A Few Different Ways to Play

I also work on [2048 Cupcakes](https://2048cupcakes.games/).

The rules of 2048 are familiar: slide tiles, merge matching values, and try to reach the next number without filling the board.

I wanted to play around with different themes while keeping that basic idea intact.

## The Games

**🧁 [2048 Cupcakes](https://2048cupcakes.games/) · [纸杯蛋糕 2048](https://2048cupcakes.games/zh/)**

Instead of ordinary numbered tiles, you merge cupcakes. Each merge reveals the next cupcake, from Vanilla Sprinkle up to Rainbow Crown.

**🔢 [Classic 2048](https://2048cupcakes.games/2048/) · [经典 2048](https://2048cupcakes.games/zh/2048/)**

The familiar version with numbered tiles. Slide, merge, and work toward 2048.

**🐕 [Doge 2048](https://2048cupcakes.games/doge-2048/) · [狗狗 2048](https://2048cupcakes.games/zh/doge-2048/)**

The same merging rules, but with Shiba portraits replacing the usual tiles.

**👑 [Princess 2048](https://2048cupcakes.games/princess-2048/) · [公主 2048](https://2048cupcakes.games/zh/princess-2048/)**

A fairy-tale-themed version with illustrated characters. Each merge reveals the next character.

**🕹️ [Flappy 2048](https://2048cupcakes.games/flappy-2048/) · [飞行 2048](https://2048cupcakes.games/zh/flappy-2048/)**

This one changes the gameplay. Instead of sliding tiles on a grid, you control a flying number and pass through matching numbered gates. Each match doubles the value, with 2048 as the goal.

All of these games run in the browser, without requiring an account or installation.

---

## 🌱 What's Next?

I still have things I want to add to these projects, and quite a few things I want to fix.

Some days it's a new tool. Other days it's a bug in an animation, a layout issue on a phone, or a result screen that needs better wording.

They're all small projects, and none of them is finished.

I'll keep working on them and see where they go.

Thanks for stopping by.

**— Funny**
