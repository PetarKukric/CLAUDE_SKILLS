---

name: kids-shorts

description: Generate original 9:16 kids' YouTube Shorts and render them to MP4 with the Remotion engine in Desktop/VILUXI/kids-shorts. The channel focuses on highly varied, family-friendly animated content including preschool learning, talking animals, funny animal situations, simple mini-stories, visual jokes, satisfying transformations, and short emotional stories. Use when the user says "/kids-shorts", "make more kids shorts", "new kids videos", "generate shorts for kids", optionally with a number and/or format.

---

# Kids Shorts Generator

Create fresh, original, highly varied YouTube Shorts for children.

The channel is NOT limited to educational videos.

The content should rotate between several major categories:

1. **PRESCHOOL LEARNING**
2. **TALKING ANIMALS**
3. **FUNNY ANIMAL SITUATIONS**
4. **SIMPLE MINI-STORIES**
5. **SATISFYING PAYOFF STORIES**
6. **ANIMAL ADVENTURES**
7. **VISUAL COMEDY / GAGS**
8. **CUTE EVERYDAY ANIMAL LIFE**
9. **GUESSING / INTERACTIVE VIDEOS**
10. **MIXED CONCEPTS**

The most important creative requirement is:

# VARIETY

Every new batch should feel noticeably different from previous batches.

Do NOT repeatedly make:

* the same story structure
* the same animal
* the same animation style
* the same camera movement
* the same hook
* the same background
* the same ending
* the same type of joke
* the same learning mechanic

If the previous episode was educational, strongly prefer an animal story next.

If the previous episode was a talking-animal story, consider a visual gag or learning episode next.

Do not produce a batch where all videos belong to the same category unless the user explicitly requests it.

---

# PROJECT

Project:

`C:\Users\User\Desktop\VILUXI\kids-shorts`

Episodes:

`episodes/*.json`

Output:

`out/<id>.mp4`

Cover:

`out/<id>.jpg`

---

# ARGUMENTS

`/kids-shorts [N] [format]`

Default:

`N = 3`

Available format families:

`surprise-box`
`count-stack`
`shadow-guess`
`talking-animal`
`animal-story`
`animal-comedy`
`satisfying-story`
`animal-adventure`
`mix`

If no format is specified, intelligently rotate between different content families.

Do NOT use the same format twice in a row.

For a batch of 3, strongly prefer:

* one educational/interactive video
* one talking/funny animal video
* one short story with a satisfying payoff

However, this is a guideline rather than a rigid rule. Choose whatever combination creates the most varied and entertaining batch.

---

# WORKFLOW

## 1. READ WHAT EXISTS

List:

`episodes/*.json`

Read the existing episodes.

Track:

* highest `epNNN`
* animals already heavily used
* objects already used
* colors
* backgrounds
* story premises
* jokes
* hooks
* endings
* learning concepts
* animation styles
* formats

New episodes must avoid repeating the same combination.

Do not simply check whether an animal has appeared before.

An animal can return, but it should behave differently.

Example:

BAD:

Cat talks in episode 1.

Cat talks again in episode 2.

Cat talks again in episode 3.

GOOD:

Cat talks in episode 1.

Rabbit tries to bake in episode 2.

Bear loses his balloon in episode 3.

---

# 2. GENERATE N CONCEPTS

Before writing JSON, generate N completely different concepts.

Think about:

* What is the hook?
* Who are the characters?
* What is the problem?
* What happens?
* What is the payoff?
* What makes the ending satisfying?
* What visual style fits the idea?

Do not make every video educational.

Some videos should simply be fun.

---

# CONTENT FAMILY 1 — PRESCHOOL LEARNING

Keep the existing educational formats available.

Examples:

* colors
* counting
* shapes
* animals
* sizes
* matching
* simple patterns
* guessing
* object recognition

Existing formats:

### surprise-box

A box appears, shakes and opens.

Items appear one by one.

Teach a color or object.

### count-stack

Blocks or objects stack while counting.

A cute animal lands on the finished tower.

### shadow-guess

A silhouette appears.

Children guess the animal.

Countdown.

Reveal.

Animal makes its sound.

Use these formats when appropriate, but do not make them the majority of the channel.

---

# CONTENT FAMILY 2 — TALKING ANIMALS

Animals should be actual characters with personalities.

They can:

* talk to each other
* ask questions
* misunderstand something
* complain
* tell jokes
* make plans
* try something new
* argue over something silly
* help each other
* react dramatically
* discover something
* have funny conversations

The dialogue should be extremely simple.

Keep lines short.

Examples:

DOG:

"IS THAT MINE?"

CAT:

"NO."

DOG:

"...ARE YOU SURE?"

CAT:

"VERY."

Then the dog looks at the camera.

Comedy comes from timing and reactions, not complicated dialogue.

Use expressive faces and body language.

Animals should feel alive.

---

# CONTENT FAMILY 3 — FUNNY ANIMAL SITUATIONS

The animal does something unexpected.

Examples:

* a tiny mouse tries to carry something huge
* a cat tries to fit inside a tiny box
* a dog thinks a reflection is another dog
* a penguin tries to slide but spins around
* a bear tries to secretly eat a cookie
* a rabbit attempts to jump over something and dramatically underestimates it
* a duck becomes obsessed with a bouncing ball

These videos do not need a learning objective.

The goal is:

**HOOK → FUNNY SITUATION → ESCALATION → PAYOFF**

---

# CONTENT FAMILY 4 — SIMPLE MINI-STORIES

Create very simple stories that can be understood visually.

Recommended structure:

### 1. HOOK

Something immediately happens.

### 2. GOAL

The character wants something.

### 3. PROBLEM

Something prevents them from getting it.

### 4. ATTEMPT

They try to solve the problem.

### 5. ESCALATION

Something unexpected happens.

### 6. PAYOFF

The problem is solved in a cute, funny or satisfying way.

### 7. END

A final reaction or visual joke.

Example:

A small bunny sees a giant balloon.

The bunny wants it.

The balloon floats away.

The bunny tries jumping.

Fails.

Tries using a box.

Fails.

A friendly bird notices.

The bird brings the balloon down.

The bunny hugs the bird.

Final shot:

The balloon accidentally lifts BOTH of them slightly off the ground.

Cute reaction.

END.

---

# CONTENT FAMILY 5 — SATISFYING STORIES

These should have an especially strong visual payoff.

The viewer should feel:

"AHHH, NICE."

Examples:

* messy room becomes perfectly organized
* tiny seed becomes a beautiful flower
* animal builds something and finally sees it work
* character completes a difficult tower
* scattered toys perfectly sort themselves
* broken-looking object becomes beautiful again
* character helps another animal and gets an unexpected reward
* a group of objects perfectly fit together
* something that was missing finally appears

Focus on:

**BUILD-UP → ANTICIPATION → PERFECT PAYOFF**

The final moment should be visually satisfying.

Use:

* smooth motion
* clean alignment
* snapping objects
* transformations
* symmetry
* particle effects
* satisfying sound effects
* musical resolution

---

# CONTENT FAMILY 6 — ANIMAL ADVENTURES

Very simple adventures.

Examples:

* rabbit explores a mysterious garden
* duck follows a glowing butterfly
* puppy searches for a lost toy
* little bear discovers a hidden treehouse
* penguin finds something unusual in the snow
* mouse explores a giant kitchen

Keep the stakes low and child-friendly.

No genuine danger.

The adventure should feel exciting without being scary.

---

# CONTENT FAMILY 7 — VISUAL COMEDY

Minimal or no dialogue.

Use physical comedy and visual storytelling.

Examples:

A cat tries to sneak toward a fish.

Every time it gets closer, the fish moves.

The cat tries again.

Again.

Again.

Finally the cat gives up.

The fish swims directly into the cat's bowl.

The cat freezes.

END.

These videos should be understandable even with sound muted.

---

# CONTENT FAMILY 8 — CUTE EVERYDAY LIFE

Show animals doing ordinary human activities.

Examples:

* dog making breakfast
* bear cleaning a room
* cat going shopping
* rabbit painting
* penguin making ice cream
* mouse going to school
* puppy trying to sleep
* duck taking a bath

The humor comes from the contrast between:

**cute animal + ordinary human activity.**

---

# CONTENT FAMILY 9 — INTERACTIVE VIDEOS

Ask the viewer to participate.

Examples:

"WHICH ONE?"

"CAN YOU FIND IT?"

"WHAT COLOR?"

"WHO TOOK IT?"

"COUNT THEM!"

"WHERE DID IT GO?"

"CAN YOU GUESS?"

The answer should appear shortly afterward.

Use these sparingly so the channel does not become repetitive.

---

# ANIMATION STYLE VARIETY

Do not always use the same visual style.

Rotate between:

* polished 3D cartoon
* cute stylized 3D
* soft 3D children's animation
* exaggerated 3D comedy
* 2D cartoon
* hand-drawn 2D
* flat colorful 2D
* storybook 2D
* paper-cutout-inspired animation
* mixed 2D/3D
* simplified graphic animation

The style should match the concept.

For emotional/satisfying stories, use smoother cinematic animation.

For comedy, use exaggerated animation.

For educational videos, use simple readable visuals.

---

# ANIMAL CHARACTER DESIGN

Use original animal characters.

Available animals can include:

* cat
* dog
* bunny
* bear
* frog
* chick
* pig
* fish
* owl
* mouse
* duck
* penguin
* fox
* turtle
* monkey
* elephant
* lion
* panda
* dino

Add new animals when useful.

Characters should have:

* expressive eyes
* clear silhouettes
* exaggerated reactions
* recognizable personalities

Avoid making every animal look identical except for color.

---

# STORY DESIGN

Stories must be simple enough for a preschool child to understand.

Prefer visual storytelling.

Use very little dialogue.

A good short can often be understood without dialogue.

Avoid complicated plots.

Avoid multiple unrelated subplots.

One short should normally contain:

**ONE PROBLEM**

**ONE GOAL**

**ONE PAYOFF**

---

# HOOK

The first second is extremely important.

Do NOT begin with:

"HELLO!"

"HI GUYS!"

"WELCOME!"

Start with action.

Examples:

A dog falls into a giant pile of balls.

A bunny discovers a giant carrot.

A cat screams:

"WAIT!"

A balloon flies away.

A tower suddenly starts falling.

A tiny mouse tries to move a giant cookie.

A mystery box begins shaking.

A character opens a door and freezes.

The viewer should immediately wonder:

**"WHAT IS GOING TO HAPPEN?"**

---

# DIALOGUE

When dialogue is used:

Keep it short.

Use simple vocabulary.

Maximum 1–2 short sentences at a time.

Dialogue should support the visual story rather than explain everything.

Avoid long narration.

Animals can communicate through:

* facial expressions
* gestures
* sounds
* reactions
* short dialogue

---

# SATISFYING ENDINGS

Do not automatically end every episode with:

"YAY!"

"GOOD JOB!"

"CONFETTI!"

Use different types of satisfying endings.

Possible endings:

### COMEDIC

Unexpected punchline.

### CUTE

Characters hug or celebrate.

### VISUAL

Everything perfectly aligns.

### TRANSFORMATION

Something becomes beautiful.

### SURPRISE

Something unexpected happens.

### LOOP

The ending naturally connects to the beginning.

### REWARD

Character gets what they wanted.

### FRIENDSHIP

Characters help each other.

### ABSURD

A funny unexpected final shot.

### MUSICAL

The animation ends exactly on a satisfying beat.

The ending should feel earned.

---

# LOOPING

Whenever possible, create endings that can naturally loop into the beginning.

Example:

Beginning:

A balloon flies toward the bunny.

Ending:

The balloon flies back toward the bunny.

The video can restart seamlessly.

This is especially useful for Shorts.

---

# PACING

Recommended duration:

**10–30 seconds**

Educational videos:

**9–20 seconds**

Animal stories:

**15–30 seconds**

Simple comedy:

**10–20 seconds**

Do not stretch a concept just to reach a specific duration.

If the story works in 12 seconds, make it 12 seconds.

---

# VISUAL PACING

Avoid static shots lasting too long.

Use:

* camera pushes
* character movement
* reactions
* close-ups
* wide shots
* quick cuts
* slow reveals
* zooms
* pans
* object animation

But do not make every scene hyperactive.

Use slower moments before a satisfying payoff to create anticipation.

---

# SOUND

Use original/generated sound effects and music.

Match sound to animation.

Useful sounds:

* footsteps
* pops
* boings
* whooshes
* squeaks
* cartoon impacts
* giggles
* animal sounds
* magical sparkles
* object clicks
* soft environmental ambience

For satisfying videos, sound should reinforce the payoff.

For comedy, timing is critical.

A tiny pause before a punchline can be more effective than another sound effect.

---

# COLOR AND BACKGROUNDS

Use bright, readable colors.

Available backgrounds:

`sky | sunny | mint | grape | peach | night`

Do not always use the same background.

Use the background that fits the story.

Night backgrounds are appropriate for:

* bedtime
* stars
* moon
* nighttime adventures

Do not use dark/scary imagery.

---

# KID SAFETY

Everything must remain:

* family-friendly
* non-violent
* non-scary
* non-dangerous
* easy to imitate safely

Do not include:

* realistic injury
* weapons
* dangerous challenges
* dangerous dares
* choking
* unsafe food challenges
* frightening horror
* disturbing imagery
* cruelty toward animals

Problems should be solved through:

* creativity
* friendship
* humor
* simple teamwork
* harmless experimentation

---

# ORIGINALITY

Take only broad genre conventions from existing children's content.

Never copy:

* existing characters
* recognizable character designs
* songs
* lyrics
* catchphrases
* scripts
* logos
* brands
* specific video concepts too closely

All characters and stories must be original.

---

# EPISODE SCHEMA

Shared:

`id`

`title`

`format`

`background`

`hookText`

`outroText`

optional:

`music: false`

Existing formats retain their current schemas.

For new formats, extend the Remotion engine when necessary.

---

# NEW FORMAT: TALKING-ANIMAL

Recommended fields:

`characters`

`dialogue`

`setting`

`action`

`punchline`

`duration`

Structure:

HOOK → CONVERSATION → MISUNDERSTANDING/PROBLEM → FUNNY PAYOFF

Example:

DOG:

"IS THAT YOUR COOKIE?"

CAT:

"NO."

DOG:

"THEN CAN I HAVE IT?"

CAT:

"NO."

Camera reveals the cat is sitting on top of TWO cookies.

Dog looks at camera.

END.

---

# NEW FORMAT: ANIMAL-STORY

Fields:

`characters`

`setting`

`goal`

`problem`

`attempts`

`resolution`

`ending`

Structure:

HOOK → GOAL → PROBLEM → ATTEMPT → PAYOFF

Keep the story visually obvious.

---

# NEW FORMAT: SATISFYING-STORY

Fields:

`character`

`initialState`

`goal`

`process`

`buildUp`

`payoff`

`ending`

Prioritize:

* anticipation
* smooth animation
* symmetry
* transformation
* satisfying sound
* clean final composition

The payoff should be the strongest visual moment of the video.

---

# NEW FORMAT: ANIMAL-COMEDY

Fields:

`character`

`setup`

`escalation`

`gag`

`finalReaction`

Prefer little or no dialogue.

The joke should be visually understandable.

---

# NEW FORMAT: ANIMAL-ADVENTURE

Fields:

`character`

`setting`

`discovery`

`obstacle`

`solution`

`ending`

Keep the adventure simple and positive.

---

# BATCH GENERATION RULE

When generating 3 videos with no specified format, prefer something like:

### VIDEO 1

Interactive / educational

### VIDEO 2

Talking animal comedy

### VIDEO 3

Simple satisfying story

But vary this across future batches.

For example, the next batch could be:

### VIDEO 1

Animal adventure

### VIDEO 2

Color-learning video

### VIDEO 3

Visual comedy

The next:

### VIDEO 1

Talking animals

### VIDEO 2

Counting

### VIDEO 3

Cute everyday animal story

Never let the channel become predictable.

---

# QA

After generating each episode:

1. Validate the JSON.
2. Render the MP4.
3. Render a preview frame.
4. Check that:

   * the hook is visible immediately
   * characters are not clipped
   * text is readable
   * animation is smooth
   * the ending is understandable
   * no visual element leaves the safe area
   * the story makes sense without excessive explanation
   * the final payoff is actually satisfying
5. If the episode feels too similar to a previous episode, redesign it before rendering the final version.

---

# REPORT

After rendering, provide a table containing:

* file
* format
* duration
* title
* concept
* suggested YouTube description
* 3–5 hashtags

Remind the user to set:

**"Made for kids: Yes"**

when uploading children's content where applicable.

---

# CORE PRINCIPLE

The channel should NOT feel like a machine producing educational templates.

It should feel like a **library of tiny animated worlds**.

One video might teach colors.

The next might feature a dog having a ridiculous conversation with a cat.

The next might tell a 20-second story about a bunny trying to grow a flower.

The next might simply be a satisfying animation of a messy room becoming perfectly organized.

The next might be a funny penguin trying to make ice cream.

The next might be an interactive animal guessing game.

The viewer should never know exactly what the next video will be.

## **VARIETY + SIMPLE STORIES + EXPRESSIVE ANIMALS + STRONG HOOKS + SATISFYING PAYOFFS = THE CORE CONTENT STRATEGY.**
