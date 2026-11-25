# Solo Trial Mode
A single player mode for Final Fantasy TCG, inspired by Magic: The Gathering's Horde Mode.

You play a normal deck against a 50 card AI deck that draws cards into play and attacks
with all available Forwards, every turn. You win by milling the AI's deck to 0 cards.

---

The ruleset can be found here: https://robthefivenine.github.io/fftcg-solo-trial/

## Ruleset

### 1. Setup (Both)

Pick / construct a legal 50 card FFTCG deck for the player and one for the AI.

1. You take 2 full turns before the AI does anything.
2. Draw 2 on each of those turns, as per the normal FFTCG rules.

### 2. Your Turn (Player)

Your turn works exactly as it does in a normal game.

1. Active Phase.
2. Draw 2.
3. Main Phase.
4. Attack Phase.
   - The AI never blocks.
   - For each point of damage you deal to the AI, mill 1 card from the top of its deck.
5. End Phase.

### 3. AI Draw Phase (AI)

The AI doesn't make spontaneous decisions and instead follows a set of rules. It draws cards and plays whatever comes up. The AI never pays the CP cost for playing cards, and its EX Bursts don't trigger.

1. Draw cards from the top of the AI deck until you draw a Forward.
2. Every drawn card enters play immediately, if it legally can.
3. Summons resolve immediately.
4. Monsters enter play as written on the card.
5. If the Forward can't stay in play because of the duplicate name rule, it breaks and the draw phase still stops there.

### 4. AI Backups (AI)

Backups work differently in this mode. Each AI Backup makes the AI's Forwards more powerful, and can be destroyed by winning blocks.

1. Each AI Backup gives all AI Forwards +500 power, up to a maximum of +2,000.
2. The bonus power is applied / removed straight away whenever a Backup enters or leaves play.
3. When you destroy an AI Forward by blocking it, you also destroy the AI's oldest Backup.
4. If the printed power of the destroyed Forward was 8,000 or more, destroy the AI's two oldest Backups instead of one.

### 5. AI Attack Phase (AI)

Every AI Forward attacks on every AI turn, starting from the leftmost Forward to the right.

1. AI Forwards have haste, so they can attack the turn they come into play.
2. AI Forwards don't dull when they attack.
3. You can block as normal.
4. When an AI effect has to choose one of your Characters, it picks the one with the highest current power.

### 6. Duplicate Names (Both)

The normal uniqueness rule applies to both sides.

1. Neither you nor the AI can control two Characters with the same name.
2. If a duplicate enters play, choose one to keep and put the other into the Break Zone.
3. For the AI, always keep the one with the higher printed power.
4. Cards with the Standard Unit icon can have multiple copies in play, as per standard rules.

### 7. Winning & Losing (Both)

A typical game lasts roughly 40 to 50 minutes and has different win conditions to a standard game.

1. You win when the AI's deck reaches 0 cards.
2. You lose when you take 7 damage.

---

*Solo Trial Mode Ruleset v1.1*
