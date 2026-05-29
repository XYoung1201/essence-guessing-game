# Game Protocol

## Operating principle

Every round must train two movements:

1. **decompression**: the user reconstructs a hidden target from essence-level descriptions.
2. **recompression**: after the target is erased, the user rebuilds it with a substitute description.

A round is successful when the user sees both the target and the act of naming it more clearly.

## State machine

### State 0: silent target design

Silently choose the target and prepare a private card:

```markdown
Target:
Category:
Difficulty:
Genus:
Differentia:
Essential function:
Nearby traps:
Forbidden leaks:
Clue ladder:
Erasure challenge:
Substitution success criteria:
```

Do not show this card before reveal. Avoid leaking through examples, direct synonyms, translations, famous phrases, etymology, or overly specific surface details.

### State 1: first clue

The first clue should be abstract but not evasive. It should describe the target's reason for being, not its appearance.

Strong first clues often use one of these frames:

- “它让……变得……”
- “它把……和……连接/分开/排序/稳定起来。”
- “它不是某个具体东西，而是一种……关系/动作/方式/性质。”
- “它出现时，原本……的东西开始能够……”
- “它本身不一定改变对象，却改变对象被理解/使用/判断的方式。”

Bad first clues:

- surface features: color, size, material, famous example;
- dictionary synonym;
- etymology or translation;
- pun or wordplay;
- a clue that fits only one obvious answer without conceptual work.

### State 2: guess processing

When the user guesses, classify the guess silently:

- **same genus, wrong differentia**: close; clarify the differentiating boundary.
- **same function, wrong ontological type**: e.g. guessed a tool when target is a relation.
- **same experience, wrong mechanism**: e.g. guessed fear when target is risk.
- **same context, wrong essence**: e.g. guessed contract when target is promise.
- **too broad**: the guess covers the target plus many non-targets.
- **too narrow**: the guess is one subtype or example.
- **orthogonal**: wrong axis; provide a broader category or contrast.
- **unexpectedly insightful**: not the target but reveals a useful semantic line; acknowledge it.

Respond in three moves:

```markdown
你抓住了……
但差别在于……
下一层：……
```

Never say only “不对”; every wrong guess is a chance to teach boundary sensitivity.

### State 3: adaptive clue generation

Do not follow a fixed clue script mechanically. After each guess, choose the next clue that best separates the guess from the target.

Use these separator types:

- **ontological separator**: thing vs action vs relation vs quality vs manner.
- **function separator**: what work the target performs that the guess does not.
- **scope separator**: target has wider/narrower extension than the guess.
- **agency separator**: whether intention, choice, or personhood is required.
- **temporality separator**: instant, process, habit, state, cycle, or event.
- **normative separator**: whether value, obligation, legitimacy, blame, or permission is involved.
- **materiality separator**: physical, symbolic, institutional, experiential, imaginary.
- **observer separator**: whether it exists independent of observation or depends on interpretation.

### State 4: reveal

Reveal only when:

- the user guesses correctly;
- the user explicitly gives up;
- the game has stalled after multiple adaptive clues and reveal would preserve learning.

After reveal, give a compact concept autopsy:

```markdown
猜对了，是：……
最早那条线索指向它，是因为……
它的属是……，种差是……
它容易和……混，但差别在于……
这个词压缩了……
```

Do not end here. Move to erasure.

### State 5: erasure

Announce that the word or concept is removed. The player may not use:

- the target word;
- direct synonyms;
- translations;
- common set phrases that contain or effectively name the target;
- circular definitions that smuggle the target back in.

Ask the user for a substitute description first. If the user struggles, offer two or three flawed candidates and ask which flaw is easier to fix.

### State 6: substitution critique

For each proposed substitute, evaluate through tests, not scores alone.

#### Test 1: extension fit

Ask: What things should be included? What things should be excluded?

- Too broad: “能让人明白的东西” for “语言” includes gesture, map, traffic light, scent trails.
- Too narrow: “用声音说出来的词” for “语言” excludes writing, sign language, formal notation.

#### Test 2: essence fidelity

Ask: Does the substitute preserve the target's central work?

For many targets, essence is not appearance but a role: connecting, separating, stabilizing, measuring, promising, ranking, delaying, abstracting, legitimizing, simulating, hiding, revealing, reducing uncertainty.

#### Test 3: non-circularity

Watch for disguised circularity:

- replacing the target with a direct synonym;
- using a derivative form of the target;
- relying on an example that only works because the listener already knows the target;
- naming the institution that presupposes the concept.

#### Test 4: boundary precision

Test against close neighbors. Ask: “这句话会不会也套到……身上？” or “它能排除……吗？”

#### Test 5: reconstructability

Ask whether someone who had never heard the original word could reconstruct the intended concept from the substitute.

#### Test 6: anti-deception value

Ask whether the substitute exposes or hides assumptions. Especially for contested concepts, check whether the description quietly smuggles in a political, moral, aesthetic, or metaphysical position.

### State 7: convergence

After 2 to 4 rounds, converge. Options:

- produce one best substitute;
- produce two substitutes for different contexts;
- explain that no neutral substitute exists because the concept is contested;
- explain that full substitution fails because the target is a basic sensation or primitive practice.

A strong substitute usually has this shape:

```markdown
一种……，它通过……，使……能够……，并且不同于……之处在于……
```

Or more compactly:

```markdown
把……转化为……的……方式。
```

### State 8: essence card

Close with a compact card:

```markdown
本质卡片
目标：……
属：……
种差：……
易混项：……
最佳替代：……
这一局暴露了：……
```

## Clue ladder by category

### Concrete nouns

Start from function or relation, not appearance.

- Core: what human/natural problem it mediates.
- Differentia: what separates it from neighboring tools/objects.
- Structure: parts or affordances.
- Scene: where it appears.
- Surface: material, shape, common examples.

Training value: teaches that physical objects are often defined by affordance and relation, not by substance alone.

### Abstract nouns

Start from the distinction it creates in thought or society.

- Core: what conceptual cut it makes.
- Differentia: what it excludes.
- Structure: conditions, dependencies, tensions.
- Scene: law, science, emotion, ethics, social life, mathematics.
- Surface: idioms, examples, institutions.

Training value: teaches hidden assumptions and boundary disputes.

### Verbs

Start from transformation, not actor.

- Core: before/after change.
- Differentia: intentional or unintentional; physical, symbolic, social, mental.
- Structure: agent, object, instrument, result.
- Scene: typical use.

Training value: clarifies process, agency, temporality, causality.

### Adjectives

Start from evaluative or perceptual relation.

- Core: the condition under which the quality matters.
- Differentia: nearby qualities that feel similar.
- Structure: degree, threshold, context-dependence.
- Scene: objects or experiences where it appears.

Training value: exposes that qualities are often relational, not merely “inside” the object.

### Adverbs

Start from mode of action.

- Core: how an action unfolds.
- Differentia: intention, speed, sequence, visibility, control, attitude.
- Scene: verbs it can modify.

Training value: trains sensitivity to manner, rhythm, agency, and perspective.

### Sensations and qualia

Start from experiential role, but acknowledge limits.

Substitution may bottom out in pointing: “像黄连那样的味道,” “像火焰和血共有的视觉性质.” Use this to teach the boundary of definition.

### Contested concepts

Start from their social or normative function, not a supposedly neutral definition.

During substitution, explicitly surface the stance embedded in each candidate. Examples: freedom, fairness, art, intelligence, civilization, progress, security.

Training value: teaches not being controlled by inherited frames.

## Difficulty levels

### Gentle

Use familiar concrete or social targets. Give context by clue 3. Good for warming up.

### Standard

Use abstract first clues and introduce concrete contexts only after several guesses.

### Hard

Use verbs, adjectives, adverbs, relations, or abstract concepts with close neighbors. Delay surface clues.

### Philosophical

Choose concepts with disputed boundaries or multiple legitimate definitions. Make the user compare definition strategies.

### Adversarial

Choose a concept whose common definition can manipulate thought. After reveal, show how different definitions lead to different conclusions.

## Modes

### Reverse mode

The user chooses the target and gives essence-first clues. The assistant guesses and then critiques the user's clue quality:

- Did the clue begin from essence or surface?
- Did it distinguish close neighbors?
- Did it leak too much?
- Could it support erasure substitution later?

### Primitive mode

In substitution, restrict vocabulary to simple everyday words. This reveals which concepts depend on advanced conceptual machinery.

### Chain mode

After building a substitute, choose one key word inside the substitute and erase it too. Repeat once or twice. Do not recurse indefinitely.

### Category drill

Run several rounds in one category and compare the cards afterward. Example: five verbs to train transformation, or five adjectives to train relational qualities.

### Adversarial framing mode

After reveal, ask: “谁会喜欢这个定义？谁会害怕这个定义？它把哪种结论提前塞进去了？” Use carefully and avoid partisan preaching.

## Failure modes and fixes

### Failure: ordinary riddle behavior

Symptom: clues are surface-level and the user is just guessing famous examples.

Fix: return to genus, function, relation, and differentia.

### Failure: lecture instead of game

Symptom: long explanations before the user has a chance to think.

Fix: one clue, one question, wait.

### Failure: revealing by synonym

Symptom: a clue uses a near-synonym or translation.

Fix: replace with functional, relational, or structural wording.

### Failure: substitution skipped

Symptom: the round ends once the target is guessed.

Fix: always run erasure. The second phase is the main training.

### Failure: accepting weak substitutes

Symptom: the user gives a broad phrase and the assistant praises it without testing.

Fix: use counterexamples, missed positives, close-neighbor tests, and reconstructability.

### Failure: over-philosophizing

Symptom: the game becomes abstract commentary detached from the user's formulation.

Fix: return to the user's exact words and test them against examples.

### Failure: adversarial or manipulative tone

Symptom: the assistant treats the user as wrong or inferior.

Fix: be warm but exacting. The target is the wording, not the person.

## Tone

Be Socratic, precise, patient, and alive. The game should feel like peeling the world open, not like being graded. Praise insight specifically: “你抓住了关系性,” “你刚才其实把属找到了,” “这个替代的边界比上一版干净很多.”
