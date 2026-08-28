# The Long Swim

An educational browser game about the real dangers the ocean's most vulnerable travellers face on their way home.

Choose a **sawfish**, **hammerhead shark**, or **sea turtle** and swim east through fishing grounds — dodging baited hooks, slipping past free-drifting ghost nets, and weaving through reef rock — until you reach the tropical island you call home. The current never stops pushing you forward.

## Play

Open `index.html` in any modern browser — the whole game is a single self-contained file (no build, no dependencies).

- **Swim**: arrow keys / WASD, or drag on touch screens
- **Pause**: P
- Four difficulties: Easy, Medium, Hard, Fiendish

## The educational bits

- No power-ups: every species gets tangled in nets, just like the real ones do
- Sharks snack on fish; turtles hunt jellyfish — but some "jellyfish" are plastic bags, which cost a heart (turtles genuinely make this mistake)
- Rotating **Did you know?** facts about bycatch, ghost nets, and ocean plastic
- Finish or get caught, and you're linked to the [Australian Marine Conservation Society](https://www.marineconservation.org.au/) page for your species (button + QR code)

## Analytics

Google Analytics is wired but dormant. To enable it, set the `GA_ID` constant near the top of the `<script>` in `index.html` to your GA4 measurement id (`G-XXXXXXXXXX`). Gameplay events tracked: `level_start`, `level_complete`, `game_over`, `learn_more_click`.

---

Built with Claude Code.
