# DESIGN_BRIEFINGS.md - Claude Design Prompt Library

> This document contains all ready-to-paste briefings for Claude Design sessions.
> Each briefing is complete and self-contained — copy, paste, send.
> Read this document at the start of every Claude Design session.
> Updated: 2026-04-23

---

## How to use this document

1. Open claude.ai/design
2. Start with the SESSION OPENER (always — every session)
3. Then paste briefings in order, one at a time
4. Wait for Design to render — give feedback — then next briefing
5. After each section: come back to claude.ai chat for next briefing if needed

---

## SESSION OPENER (paste this first — every Design session)

```
IMPORTANT — READ BEFORE STARTING:

We are continuing an existing design project.
Do NOT start from scratch. Do NOT create new design proposals.

Project: QFit marketing website — role-based persona toggle approach
Design system: Already confirmed — "Precision Performance" light theme

DESIGN SYSTEM REMINDER:
- Page background: #fcf9f8 (warm off-white)
- Section alternates: #f6f3f2 / #ffffff / #f0eded
- Primary: #006d36 / Primary container: #4ece7a
- Gradient: #6be87a → #3dd9a4
- Fonts: Manrope (headings 600/700/800) + Inter (body 400/500/600)
- Cards: bg #f3f4f6, border #e5e7eb, hover border #4ece7a, rounded-xl
- Buttons: rounded-full, primary bg #4ece7a text #005428
- Icons: Material Symbols Outlined
- Stats numbers: Inter 40px, weight 700, letter-spacing -0.03em, color #006d36

CURRENT STATUS:
- Gym & Fitness Club: ALL sections complete ✓
- Athletes & Trainers: Hero + Problem complete ✓
- Sports Clubs & Schools: not started
- Equipment Manufacturers: not started

TODAY'S TASK: [describe what you want to build]

RULE: Do not modify any previously completed sections.
Always state explicitly which persona and section you are building.
Show me each section before continuing to the next.
```

---

## PERSONA 1: ATHLETES & TRAINERS
### Remaining sections: 3–9

---

### ATH-BLOCK-A: Sections 3 + 4 (What QFit Is + How It Works)

```
Building for: ATHLETES & TRAINERS persona (right column)
Do NOT touch: Gym & Fitness Club column (left column)
Do NOT touch: Athlete Hero + Problem (already complete)

Add the following 2 sections to the Athletes & Trainers page:

---

SECTION 3 — WHAT QFIT IS (Athlete & Trainer)

Background: #ffffff, padding 64px vertical, 40px horizontal, max-width 7xl

Blockquote block:
border-left 8px solid #4ece7a, padding-left 40px,
padding-top/bottom 16px, margin-bottom 64px, max-width 3xl
Text: Manrope italic H1 size, color #1c1b1b:
"QFit is not content. It is training intelligence."

Three columns (gap 64px):
Each: icon container w-12 h-12 bg rgba(78,206,122,0.1) rounded-lg
+ Material Symbol icon color #006d36
+ Title: Manrope H3 color #1c1b1b, margin-top 16px
+ Body: Inter body-md color #3d4a3f, margin-top 8px

Column 1 — Icon "psychology"
Title: "Built around you"
Body: QFit starts with your physiology, your history, your goals —
and builds a plan that is genuinely yours. Not a template.
Not someone else's program adapted.

Column 2 — Icon "track_changes"
Title: "Tracks what matters"
Body: Every session is measured against the metrics that determine
real physiological adaptation — not just weight and reps.
You know if it worked.

Column 3 — Icon "bolt"
Title: "Evolves with you"
Body: As you progress, the plan progresses. Every session feeds
back into the next. Your training is never static — it is always
optimal for where you are right now.

Stats row (same style as Gym version):
bg rgba(78,206,122,0.05), rounded-[40px], padding 48px, 4-column grid
Numbers: Inter 40px weight 700 letter-spacing -0.03em color #006d36
Labels: Inter 12px uppercase letter-spacing 0.05em color #3d4a3f

"2,000+" / "EXERCISES"
"11" / "ATHLETIC GOALS"
"600+" / "MUSCLES MODELLED"
"17" / "ONBOARDING STEPS"

---

SECTION 4 — HOW IT WORKS (Athlete & Trainer)

Background: #ffffff, padding 64px, overflow hidden
Same layout and style as Gym version — horizontal stepper

Headline: Manrope H1 text-center: "From goals to gains — four steps."

Steps 1–3: Circle w-16 h-16, border-2 #4ece7a, bg white,
  number Manrope bold #006d36, connector line height 2px bg #f3f4f6
Step 4 (highlight): Circle w-16 h-16, bg #4ece7a, text white,
  shadow-lg shadow-#4ece7a/40, scale-110

Step 1 — "01" / "Athlete assessment"
Text: Your physiological profile, training history, injury background,
and personal goals. 9 data categories. 17 questions.
One complete picture of you as an athlete.

Step 2 — "02" / "Goals & time"
Text: Primary and secondary athletic goals — strength, hypertrophy,
power, endurance, mobility. Combined with your available training
days and session duration.

Step 3 — "03" / "Your equipment"
Text: From a fully equipped commercial gym to a minimal home setup.
QFit works with what you have — no excuses, no compromises.

Step 4 — "04" / "Your plan" (highlighted — the magic moment)
Text: Not a template. Not a copy of someone else's program.
Uniquely built for you — and continuously updated as you train.

Two detail cards below stepper (max-width 3xl, centered, gap 24px):

Card left: bg #f6f3f2, rounded-xl, padding 24px
Title: Manrope H3 #1c1b1b: "What QFit learns about you"
List (Inter body-sm #3d4a3f, — prefix):
— Your physiological baseline
— Training history & experience level
— Injury history & movement limitations
— Primary & secondary goals
— Available equipment & training frequency

Card right: bg rgba(78,206,122,0.08), border #4ece7a, rounded-xl, padding 24px
Title: Manrope H3 #006d36: "What QFit AI (Qi) delivers"
List:
— A plan built for your body specifically
— Exercise selection matching your goals
— Progressive overload calculated per session
— Automatic adaptation when you plateau

---

Show me Sections 3 and 4 for Athletes & Trainers.
Do not touch the Gym column or any previous Athlete sections.
```

---

### ATH-BLOCK-B: Sections 5 + 6 (Use Cases + The Science)

```
Building for: ATHLETES & TRAINERS persona
Do NOT touch: anything previously built

Add the following 2 sections to the Athletes & Trainers page:

---

SECTION 5 — USE CASES (Athletes & Trainers tab active)

Background: #fcf9f8, padding 64px, max-width 7xl

Tab row: border-bottom 1px solid #f3f4f6, Manrope bold
Active tab "Athletes & Trainers": color #006d36, border-bottom 2px #4ece7a
Inactive tabs (color #9ca3af): Gyms & Fitness Clubs · Sports Clubs & Schools · Equipment

2-column grid (gap 64px, items centered):

LEFT COLUMN:
Badge: Inter label-caps uppercase #006d36: "ATHLETES & TRAINERS"
Headline: Manrope H1 #1c1b1b:
"Your body. Your goals. Your plan — finally."
Body: Inter body-lg #3d4a3f:
"QFit gives every athlete access to the kind of precision coaching
that used to require an elite support team. And gives every trainer
the tools to deliver that precision — at scale."

4 benefit items (flex gap 12px, icon + text):
Icon: Material Symbol "check_circle" filled, color #4ece7a, size 20px
Text: Inter font-medium #1c1b1b

→ Individual plan built from your physiology — not a generic template
→ 8 performance metrics tracked every session —
  know if your training is working
→ Injury risk flagged before it becomes a problem
→ Trainers: automated reporting saves 12+ hours per week

CTA button: rounded-full bg #4ece7a text #005428 px-8 py-4 Manrope bold:
"Get started"

RIGHT COLUMN — three metric cards (stacked, slight offset):
Card style: bg white, rounded-xl, shadow-sm, border #f3f4f6, padding 24px

Card 1 (full width):
Metric: Inter 40px weight 700 letter-spacing -0.03em color #006d36: "8"
Label: Inter label-caps uppercase #3d4a3f:
"PERFORMANCE METRICS TRACKED PER SESSION"

Card 2 (margin-left 48px):
Metric: "12.5h"
Label: "TRAINER TIME SAVED PER WEEK"
Sub: Inter body-sm #3d4a3f: "Automated reporting handles the admin"

Card 3 (full width):
Metric: "100%"
Label: "INDIVIDUAL"
Sub: "Not a template — built for this athlete"

---

SECTION 6 — THE SCIENCE (Athlete-weighted)

Background: #f6f3f2, padding 64px, max-width 7xl

Headline: Manrope H1 text-center #1c1b1b:
"Workout planning is no longer an art. It's a science."

Intro: Inter body-lg #3d4a3f text-center max-width 3xl margin auto mb-48px:
"Traditional tracking counts weight, reps, and sets. QFit calculates
the metrics that determine whether your training stimulus is achieving
its intended physiological effect."

2×2 card grid (same style as Gym version):
bg white, rounded-xl, padding 32px, border #e5e7eb, hover border #4ece7a
Each: metric name Manrope H2 #006d36 + full name Inter body-sm #3d4a3f
+ definition Inter body-md #1c1b1b + mini chart + relevance tag

Card 1 — MEE (prominent for athletes)
Name: "MEE" / Full: "Mechanical Energy"
Definition: Total physical work in kcal — making completely different
workout plans directly comparable. One number that tells you if
today's session matched the stimulus of last week's.
Mini chart: bar chart comparison (same style as Gym)
Tag: "Session quality · Comparability"

Card 2 — F×TuT
Name: "F×TuT" / Full: "Workout Intensity"
Definition: Force × Time under Tension — the primary driver of
hypertrophy and strength adaptation. QFit optimizes this by muscle
group across your entire program, not just per exercise.
Mini chart: heatmap grid (same style as Gym)
Tag: "Strength · Hypertrophy"

Card 3 — WTM
Name: "WTM" / Full: "Wear & Tear Metric"
Definition: Cumulative mechanical load on joints and musculature
over time, adjusted for recovery. You are alerted when load
approaches your personal threshold — before injury happens.
Mini chart: line chart with threshold (same style as Gym)
Tag: "Injury prevention · Longevity"

Card 4 — Goal Radar
Name: "Goal Radar" / Full: "Plan-to-Goal Match"
Definition: A visual score showing how well your current training
plan maps to your stated goals. See exactly where your plan is
strong — and where it needs adjustment.
Mini chart: radar chart — axes: Strength · Hypertrophy · Power ·
Endurance · Mobility · Recovery (same style as Gym)
Tag: "Progress · Transparency"

---

Show me Sections 5 and 6 for Athletes & Trainers.
Do not touch anything previously built.
```

---

### ATH-BLOCK-C: Sections 7 + 8 + 9 (Capabilities + Technology + CTA)

```
Building for: ATHLETES & TRAINERS persona
Do NOT touch: anything previously built

Add the following 3 sections to complete the Athletes & Trainers page:

---

SECTION 7 — PLATFORM CAPABILITIES (Athlete focus)

Background: #ffffff, padding 64px, max-width 7xl

Headline: Manrope H1 text-center:
"Every tool a trainer needs. Every insight an athlete deserves."

Intro: Inter body-lg #3d4a3f text-center max-width 3xl:
"From plan generation to session guidance to automatic feedback —
QFit handles the science so you can focus on the training."

Feature grid — same card style as Gym version:
bg #f3f4f6, border #e5e7eb, rounded-xl, padding 32px,
hover border #4ece7a

PRIMARY (border-left 4px solid #006d36) — 3 cards:

Card 1 — Icon "fitness_center"
Title: "Program Generation"
Body: "2,000+ exercises · goal + injury + equipment aware ·
uniquely built per athlete · not a template, not a copy —
built from scratch every time."
Tag: "2,000+ exercises · Truly individual"

Card 2 — Icon "play_circle"
Title: "Session Sequencer"
Body: "Real-time session guidance on smartphone, iPad, or Garmin.
Every exercise, every set, every rest — guided by QFit.
Available for solo training or with a trainer."
Tag: "Real-time guidance · Any device"

Card 3 — Icon "sync"
Title: "Auto-Adaptation"
Body: "Plan evolves after every session. If progress stalls →
load adjusted. If compliance drops → plan recalibrated.
If an exercise causes pain → replaced automatically."
Tag: "Always current · Never static"

SECONDARY — 2 cards:

Card 4 — Icon "mark_chat_read"
Title: "Automated Reports"
Body: "Post-workout performance reports and weekly summaries —
generated automatically. Every athlete gets personalized feedback.
Zero trainer admin hours."
Tag: "Zero admin · Personalized"

Card 5 — Icon "analytics"
Title: "Analytics"
Body: "Individual progress tracking across all 8 QFit metrics.
See exactly how each session contributes to your goals —
and where to push harder."
Tag: "8 metrics · Full visibility"

---

SECTION 8 — TECHNOLOGY (Athlete perspective — lighter treatment)

Background: #f6f3f2, padding 64px, max-width 7xl

Headline: Manrope H1 text-center:
"Built on real biomechanics. Powered by AI."

Intro: Inter body-lg #3d4a3f text-center max-width 3xl mb-48px:
"At the core of QFit is a human biomechanics model covering
200+ bones and 600+ muscles. QFit AI (Qi) uses this — together
with your personal data — to generate a plan that is genuinely
built for you."

Architecture diagram (same style as Gym, lighter/simpler):
Container bg white rounded-[32px] padding 48px border #e5e7eb

LEFT — "Your data" (label-caps):
Chips bg #f6f3f2 rounded-lg padding 12px border #e5e7eb:
icon "person" — "Your physiological profile"
icon "flag" — "Your goals & timeline"
icon "fitness_center" — "Your equipment"
icon "watch" — "Your wearables (Garmin · Apple)"

CENTER — "QFit AI (Qi)":
bg gradient #006d36→#006c4e, rounded-xl, padding 24px,
text white centered:
"QFit AI (Qi)"
label-caps rgba(255,255,255,0.7): "biomechanics · 11 goals · equipment-aware"

RIGHT — "Your plan":
icon "assignment" — "Personalized workout plan"
icon "play_circle" — "Session sequencer"
icon "mark_chat_read" — "Automated post-workout reports"
icon "trending_up" — "Progress analytics"

Key message below: Inter body-md #3d4a3f text-center italic:
"Everything built from your data. Everything updated after every session."

Integration badges (same style as Gym):
rounded-full border #bccabb bg white Inter body-sm padding 6px 16px:
Garmin · Apple · VALD · + API-first (dashed border #4ece7a text #006d36)

---

SECTION 9 — CALL TO ACTION + FOOTER (Athlete)

CTA:
Background #f0eded rounded-[40px] margin 0 40px padding 64px text-center

Headline: Manrope display-lg 48px weight 800 max-width 2xl margin auto:
"Ready to train smarter — and prove it?"

Sub: Inter body-lg #3d4a3f max-width xl margin auto mb-40px:
"QFit builds your plan, tracks your progress, and adapts with
every session. No guesswork. No generic programs."

Buttons (flex centered gap 16px):
Primary: rounded-full bg #4ece7a text #005428 px-10 py-5 Manrope bold lg
shadow-lg hover #3dd9a4: "Get started"
Secondary: rounded-full bg white border #bccabb text #1c1b1b
px-10 py-5 Manrope bold lg: "Request a demo"

Small text: Inter text-sm #6d7a6e margin-top 24px: "contact@qfit.ai"

FOOTER (same structure and style as Gym version):
bg #f9fafb border-top #e5e7eb padding 64px 40px max-width 7xl

4 columns: Brand + Product + Company + Legal
Same links and styling as Gym footer.

---

Show me Sections 7, 8, and 9 for Athletes & Trainers.
This completes the Athletes & Trainers prototype.
Do not touch anything previously built.
When complete, export the full Athletes & Trainers page as standalone HTML.
```

---

## PERSONA 3: SPORTS CLUBS & SCHOOLS
### All sections: complete prototype

---

### CLB-BLOCK-A: Hero + Problem

```
Building for: SPORTS CLUBS & SCHOOLS — new standalone page
This is a third parallel column / page alongside Gym and Athlete.

Use the exact same design system as the other two personas.
Build sections 1 and 2 only. Show me before continuing.

---

SECTION 1 — HERO (Sports Club active)

Same layout as other personas — 2 columns, same nav, same design.

Eyebrow: "DIGITAL GYM APPLICATION"
Headline: "Better workouts." + "Guaranteed." (gradient text)

Toggle pills: Sports Club active, others inactive:
[Athletes & Trainers] [Gym] [Sports Club ✓] [Equipment]

Sub-headline (Sports Club active):
Inter body-lg #3d4a3f max-width 32rem:
"Individual conditioning plans for every athlete on your squad.
Population analytics for the whole team.
Injury risk flagging before it becomes a problem."

CTAs: "Get started" (primary) + "See how it works" (ghost)

Right column — dark app dashboard panel (#313030):
Squad/team analytics view showing:
- Multiple athlete profiles with individual metrics
- Population overview: squad readiness %
- WTM alert indicator for one athlete
- "AI INSIGHT" strip: "3 athletes approaching load threshold"
- Green accent data on dark background

---

SECTION 2 — THE PROBLEM (Sports Club)

Background: #f6f3f2, same padding

Headline: Manrope H1 text-center:
"A full squad." +
<span color #006d36>"Individual needs. One coaching team."</span>

Intro: Inter body-lg #3d4a3f centered max-width 3xl:
"A sports club has no individual athletes — it has a population.
Every player needs individual conditioning. Every coach needs to
see the whole picture. Managing both manually is impossible."

4 bento cards (same style as other personas):

Card 1 — "Individual conditioning at squad scale"
Icon: "groups" #6d7a6e
Text: 30 players, 200 students, one squad. Creating individual
conditioning plans for every athlete manually is not feasible.
One generic program for all means suboptimal preparation for each.

Card 2 — "Injury risk invisible until too late"
Icon: "warning" #6d7a6e
Text: Overuse accumulates across training cycles. By the time an
athlete reports pain, weeks of avoidable damage have built up.
No system is watching the cumulative load across the whole squad.

Card 3 — "No comparable population baseline"
Icon: "bar_chart_off" #6d7a6e
Text: Without standardized testing across the whole squad, it's
impossible to compare athletes, track cohort fitness, or identify
who needs attention most.

Card 4 — "Data siloed between departments"
Icon: "device_hub" #6d7a6e
Text: Conditioning coaches, trainers, and medical staff work with
different data. A shared intelligence layer that everyone can
read doesn't exist.

---

Show me Hero + Problem for Sports Clubs & Schools.
Do not touch any other persona.
```

---

### CLB-BLOCK-B: Sections 3–6 (What QFit Is + How It Works + Use Cases + Science)

```
Building for: SPORTS CLUBS & SCHOOLS persona
Do NOT touch: any other persona or previously built sections

Add sections 3 to 6:

---

SECTION 3 — WHAT QFIT IS (Sports Club accent)

Same structure as other personas. Same blockquote.
"QFit is not content. It is training intelligence."

Three columns — Club-accented copy:

Column 1 — Icon "psychology"
Title: "Intelligence for every athlete"
Body: QFit generates individual plans for every athlete on your squad —
automatically. Same precision for the squad's star performer
and the youngest academy member.

Column 2 — Icon "group"
Title: "Population-level insight"
Body: Every athlete's data feeds into a squad-wide analytics layer.
Coaches see individual progress and population trends
in the same platform.

Column 3 — Icon "health_and_safety"
Title: "Injury prevention built in"
Body: The Wear & Tear Metric monitors cumulative load across
every athlete. Coaches are alerted before overuse becomes absence.

Stats row:
"2,000+" / "EXERCISES"
"600+" / "MUSCLES MODELLED"
"11" / "ATHLETIC GOALS"
"API-first" / "WEARABLE INTEGRATION"

---

SECTION 4 — HOW IT WORKS
Universal — same as other personas, no changes needed.

---

SECTION 5 — USE CASES (Sports Clubs & Schools tab active)

Tab row: Active: "Sports Clubs & Schools", inactive others.

LEFT COLUMN:
Badge: "SPORTS CLUBS & SCHOOLS"
Headline: "Every athlete individually conditioned.
Every coach fully informed."
Body: "QFit brings individual precision to population-level
conditioning — giving every athlete their own plan while giving
coaches a single view of the entire squad."

4 benefits:
→ Individual conditioning plans for every athlete —
  auto-generated, auto-adapted
→ Population analytics: compare all athletes on a single
  metric baseline
→ WTM monitoring across the full squad — injury risk flagging
  before absence
→ Standardized testing: VO2max, CMJ, 1RM — tracked and
  comparable over time

CTA: "Request a demo"

RIGHT COLUMN — stats cards:
Card 1: "Squad" / "INDIVIDUAL PLANS — ONE PER ATHLETE"
Card 2 (offset): "WTM" / "WEAR & TEAR MONITORED ACROSS FULL SQUAD"
Sub: "Flags risk before it becomes injury"
Card 3: "API" / "CONNECTS TO GARMIN · VALD · CATAPULT"

---

SECTION 6 — THE SCIENCE (Club-weighted)

Same structure as other personas.

4 selected metrics for Sports Clubs:

Card 1 — WTM (most important for clubs)
"Wear & Tear Metric"
Cumulative joint load monitoring at squad level. Coaches see
which athletes are approaching their load threshold —
before injury pulls them from the squad.
Tag: "Injury prevention · Squad availability"
Mini chart: line chart with threshold (same style)

Card 2 — APP
"Average Peak Power"
Critical for power-sport athletes. Tracks explosive output
per session and over time — the key metric for speed, jump,
and contact-sport performance.
Tag: "Power sports · Performance tracking"
Mini chart: bar chart showing APP trend over sessions

Card 3 — F×TuT
"Workout Intensity"
Primary driver of strength adaptation. Ensures each athlete's
program delivers the right stimulus for their position and role.
Tag: "Strength · Position-specific training"
Mini chart: heatmap (same style)

Card 4 — Goal Radar (population view)
"Plan-to-Goal Match — Squad View"
Visualizes where each athlete's plan sits relative to their
individual goals — and where the whole squad sits relative
to team conditioning targets.
Tag: "Squad overview · Targeted coaching"
Mini chart: radar chart — axes: Speed · Strength · Power ·
Endurance · Agility · Recovery

---

Show me Sections 3–6 for Sports Clubs & Schools.
Do not touch any other persona.
```

---

### CLB-BLOCK-C: Sections 7–9 (Capabilities + Technology + CTA)

```
Building for: SPORTS CLUBS & SCHOOLS persona
Do NOT touch: anything previously built

Complete the Sports Clubs & Schools page:

---

SECTION 7 — PLATFORM CAPABILITIES (Club focus)

Same structure as other personas.

PRIMARY (3 cards, border-left #006d36):

Card 1 — Icon "group"
Title: "Population Analytics"
Body: "Individual progress · squad cohort trends · position-group
comparisons — all in one platform. Know which athletes are
thriving and which need intervention."
Tag: "Squad intelligence · Cohort view"

Card 2 — Icon "fitness_center"
Title: "Individual Program Generation"
Body: "Every athlete gets their own plan — built from their
physiology, position demands, and training history.
2,000+ exercises. Fully equipment-aware."
Tag: "Individual · Position-specific"

Card 3 — Icon "warning"
Title: "Injury Risk Monitoring"
Body: "WTM tracks cumulative load across every athlete.
Automatic alerts when any squad member approaches their
personal threshold. Before pain. Before absence."
Tag: "WTM · Proactive protection"

SECONDARY (2 cards):

Card 4 — Icon "play_circle"
Title: "Session Sequencer"
Body: "Real-time session guidance for every athlete —
individually adapted. Works with Garmin, iPad, smartphone.
Trainer-led or solo."
Tag: "Real-time · Any device"

Card 5 — Icon "science"
Title: "Standardized Testing Protocols"
Body: "VO2max, CMJ, 1RM — standardized and tracked.
Population-comparable results. Repeatable baselines
for every testing cycle."
Tag: "VO2max · CMJ · 1RM"

---

SECTION 8 — TECHNOLOGY (Club perspective)

Headline: "Built on real biomechanics. Powered by AI.
Connected to your ecosystem."

Intro: "QFit connects to the wearables and testing equipment
your squad already uses — enriching their data with
biomechanical insight and feeding it back to every
coach and athlete."

Architecture diagram (same style as Gym):
INPUTS: Athlete profiles · Equipment · Exercise library ·
  Garmin · VALD · Catapult · VO2Master
CENTER: QFit AI (Qi) / biomechanics · 11 goals · population analytics
OUTPUTS: Individual workout plans · Squad analytics dashboard ·
  Injury risk alerts · Testing protocols

Key message: "API-first design. Connects to your existing
ecosystem without disruption."

Integration badges: Garmin · VALD · Catapult · VO2Master · Apple · + API-first

---

SECTION 9 — CTA + FOOTER

CTA headline: "Ready to condition every athlete — individually?"
Sub: "QFit gives every athlete on your squad their own plan —
and gives you the data to coach with confidence."
Primary button: "Request a demo"
Secondary button: "Get started"
Contact: contact@qfit.ai

Footer: Same structure and style as other personas.

---

Show me Sections 7–9 for Sports Clubs & Schools.
This completes the Sports Clubs & Schools prototype.
When complete, export as standalone HTML.
```

---

## PERSONA 4: EQUIPMENT MANUFACTURERS
### All sections: complete prototype

---

### EQP-BLOCK-A: Hero + Problem

```
Building for: EQUIPMENT MANUFACTURERS — new standalone page
Same design system. Build sections 1 and 2 only.

---

SECTION 1 — HERO (Equipment Manufacturer active)

Eyebrow: "DIGITAL GYM APPLICATION"
Headline: "Better workouts." + "Guaranteed." (gradient)

Toggle: Equipment active, others inactive:
[Athletes & Trainers] [Gym] [Sports Club] [Equipment ✓]

Sub-headline:
"API-first design means QFit connects to your existing
ecosystem without disruption. No rip-and-replace.
Your hardware becomes a platform — powered by
training intelligence."

CTAs: "Request a demo" (primary) + "See how it works" (ghost)

Right column — dark panel:
Equipment/hardware integration view showing:
- Device connected to QFit platform
- Real-time biomechanical data feed
- "POWERED BY QFIT" badge on device mockup
- Usage analytics: sessions, load data, muscle engagement
- "AI INSIGHT" strip: "Peak power output: 1,284W · +4% this session"

---

SECTION 2 — THE PROBLEM (Equipment Manufacturer)

Headline: "Outstanding hardware."
+ <span color #006d36>"But the machine doesn't think."</span>

Intro: "The market is moving toward platforms, not products.
Hardware alone no longer differentiates. The gyms that will
win are the ones with intelligent ecosystems — and the
equipment inside them needs to be part of that intelligence."

4 cards:

Card 1 — "Hardware alone no longer differentiates"
Icon: "devices" #6d7a6e
Text: Competitors build comparable equipment. The next
battleground is data, intelligence, and ecosystem integration.
Without a software layer, hardware is just steel.

Card 2 — "No training intelligence in the device"
Icon: "psychology_off" #6d7a6e
Text: Your equipment captures movement — but doesn't know
whether that movement is serving the athlete's goal,
building toward injury, or wasting effort.

Card 3 — "No data flowing back to product development"
Icon: "data_usage" #6d7a6e
Text: Without real usage data, product decisions are based
on assumption. Which machines are used most? In which
configurations? What load patterns are most common? Unknown.

Card 4 — "Gyms want integrated solutions"
Icon: "hub" #6d7a6e
Text: Gym buyers increasingly evaluate systems, not devices.
Equipment that doesn't integrate with training management
software is a liability in the sales conversation.

---

Show me Hero + Problem for Equipment Manufacturers.
Do not touch any other persona.
```

---

### EQP-BLOCK-B: Sections 3–6

```
Building for: EQUIPMENT MANUFACTURERS persona
Do NOT touch: anything previously built

Add sections 3 to 6:

---

SECTION 3 — WHAT QFIT IS (Equipment Manufacturer accent)

Blockquote (same): "QFit is not content. It is training intelligence."

Three columns:

Column 1 — Icon "layers"
Title: "The intelligence layer"
Body: QFit sits on top of your hardware as a software intelligence
layer — capturing, enriching, and acting on the data your
equipment generates in real time.

Column 2 — Icon "api"
Title: "API-first by design"
Body: No custom integration project. No rip-and-replace.
QFit's open API connects to your existing ecosystem —
devices, apps, CRMs — without disruption.

Column 3 — Icon "trending_up"
Title: "Data that flows both ways"
Body: Session data enriched with biomechanical insight feeds
back to athletes and operators. And back to your product team —
informing the next generation of hardware.

Stats row:
"200+" / "BONES MODELLED"
"600+" / "MUSCLES MODELLED"
"2,000+" / "EXERCISES"
"API-first" / "INTEGRATION"

---

SECTION 4 — HOW IT WORKS
Universal — same as other personas.

---

SECTION 5 — USE CASES (Equipment Manufacturers tab)

Badge: "EQUIPMENT MANUFACTURERS"
Headline: "Your hardware. QFit intelligence.
A platform — not just a product."
Body: "QFit's API-first architecture sits as an intelligence
layer on top of your equipment ecosystem — capturing session
data, enriching it with biomechanical insight, and delivering
value back to athletes, operators, and your product team."

4 benefits:
→ QFit as intelligence layer on your hardware —
  the device becomes smart
→ Real-time session data captured and enriched with
  biomechanical metrics
→ Usage data feeds back to your product development
→ Co-branding: "Powered by QFit" as a quality signal

CTA: "Request a demo"

RIGHT COLUMN — stats:
Card 1: "API" / "FIRST INTEGRATION ARCHITECTURE"
Card 2 (offset): "Real-time" / "BIOMECHANICAL DATA AT THE DEVICE"
Sub: "Velocity · acceleration · joint angles · power output"
Card 3: "IMU" / "EXTENDED PRECISION MOTION CAPTURE"
Sub: "Optional hardware layer for maximum data fidelity"

---

SECTION 6 — THE SCIENCE (Equipment — lighter treatment)

Intro: "QFit's biomechanics model calculates metrics that
traditional sensors can't — turning raw movement data into
meaningful training intelligence."

4 cards — most relevant for equipment context:

Card 1 — MEE / "Mechanical Energy"
Makes completely different equipment setups directly comparable.
Proof that your equipment is delivering measurable training stimulus.
Tag: "Equipment validation · Comparability"

Card 2 — APP / "Average Peak Power"
The key metric for power equipment — barbells, platforms, sleds.
Real-time and session-aggregate power output per athlete.
Tag: "Power equipment · Performance proof"

Card 3 — ARV / "Average Rep Velocity"
Zone-based training prescription using velocity data.
Turns any equipped exercise into a velocity-based training tool.
Tag: "Velocity-based training · Smart equipment"

Card 4 — WTM / "Wear & Tear Metric"
Cumulative joint load — calculated across all equipment usage.
Protects athletes and informs equipment programming recommendations.
Tag: "Athlete protection · Load management"

---

Show me Sections 3–6 for Equipment Manufacturers.
Do not touch anything previously built.
```

---

### EQP-BLOCK-C: Sections 7–9 (Capabilities + Technology + CTA)

```
Building for: EQUIPMENT MANUFACTURERS persona
Do NOT touch: anything previously built

Complete the Equipment Manufacturers page:

---

SECTION 7 — PLATFORM CAPABILITIES (Equipment focus)

PRIMARY (3 cards):

Card 1 — Icon "api"
Title: "API-first Integration"
Body: "Open API connects QFit to any hardware ecosystem.
No custom development. No proprietary lock-in.
Your devices become QFit-powered in days, not months."
Tag: "Open API · Fast integration"

Card 2 — Icon "analytics"
Title: "Operational Intelligence"
Body: "Equipment utilization data · session patterns ·
load profiles per exercise — real usage data that informs
your product roadmap and commercial conversations with gyms."
Tag: "Product insights · Commercial intelligence"

Card 3 — Icon "sensors"
Title: "QFit IMU — Extended Capability"
Body: "Precision motion capture layer for environments that
want real-time biomechanical data at the hardware level.
Velocity · acceleration · joint angles · power output —
directly from athlete movement."
Tag: "IMU · Precision motion capture"

SECONDARY (2 cards):

Card 4 — Icon "fitness_center"
Title: "Program Generation"
Body: "2,000+ exercises — all equipment-aware. QFit generates
plans that map to your specific equipment inventory.
Every plan is a recommendation to use your hardware."
Tag: "Equipment-aware · Usage driving"

Card 5 — Icon "mark_chat_read"
Title: "Automated Communications"
Body: "Post-workout reports reference equipment usage.
Athletes receive personalized feedback tied to specific
exercises performed on your hardware."
Tag: "Equipment attribution · Athlete engagement"

---

SECTION 8 — TECHNOLOGY (Equipment — full depth)

Headline: "Built on real biomechanics. Powered by AI.
Integrated into your hardware ecosystem."

Intro: "QFit's architecture is designed from the ground up
to connect to external hardware. Your equipment is an input
layer — and a beneficiary of the intelligence QFit generates."

Architecture diagram (same style — emphasize hardware side):
INPUTS: Your hardware data · Athlete profiles ·
  Exercise library (2,000+) · QFit IMU (optional)
CENTER: QFit AI (Qi) / biomechanics · equipment-aware ·
  real-time processing
OUTPUTS: Personalized workout plans · Equipment usage analytics ·
  Athlete performance data · Product development insights

Key message: "No rip-and-replace. API-first by design.
Your hardware becomes a platform."

IMU callout box (subtle, dashed border #4ece7a):
"Extended capability: QFit IMU adds precision motion capture —
velocity, acceleration, joint angles, and power output
directly from athlete movement at the hardware level."

Integration badges: Garmin · Apple · VALD · VO2Master ·
Catapult · + API-first (highlighted)

---

SECTION 9 — CTA + FOOTER

CTA headline: "Ready to turn your hardware into a platform?"
Sub: "QFit's API-first architecture integrates with your
equipment ecosystem without disruption — adding training
intelligence to every device you make."
Primary: "Request a demo"
Secondary: "Get started"
Contact: contact@qfit.ai

Footer: Same structure and style as other personas.

---

Show me Sections 7–9 for Equipment Manufacturers.
This completes the Equipment Manufacturers prototype.
When complete, export as standalone HTML.
```

---

## FINAL STEP: SIDE-BY-SIDE COMPARISON VIEW

```
We now have 4 complete persona prototypes:
- Gym & Fitness Club ✓
- Athletes & Trainers ✓
- Sports Clubs & Schools ✓
- Equipment Manufacturers ✓

Please create a comparison layout showing all 4 personas
side by side — one column per persona.

Layout: 4-column grid, each column showing all sections
stacked vertically for that persona.

Column headers (one per persona):
P1 · Athletes & Trainers
P2 · Gyms & Fitness Clubs
P3 · Sports Clubs & Schools
P4 · Equipment Manufacturers

Section labels between rows:
Show the section name as a divider label spanning all 4 columns.

This allows the team to see how content adapts per role
for each section — side by side.

Export the comparison view as standalone HTML.
```

---

*Last updated: 2026-04-23 — All briefings prepared from claude.ai planning session.*
*Ready to use from Saturday when Design usage limit resets.*
