# Shuffle The Realm — Development checkpoint
November 27, 2026

## Stable playable build
v0.4.20. Ironbound, Goblin Raider, Goblin Archer, Goblin Shaman and Goblin King animations approved. Goblin King is the solo elite in encounter four.

## Current boss: Bone Maw
Approved left-facing flesh-and-bone creature artwork, matching goblin art style. Goblins worship it as a god. On reaching zero HP, it divides into two Lesser Maws (~60% original size); defeat both to win. No further splits. Stats and rewards remain provisional.

## Animation Studio
https://nukohari.github.io/shuffle-the-realm-studio/
Bone Maw Combined Animation Lab v11, labs/bone-maw-combined/part-00.txt. Artwork, bite-art and eruption artwork stored in repository. No local artwork selection required.

### Approved (3/8)
- Idle: continuous jaw deformation, breathing exactly 35%; other sliders at defaults unless otherwise specified.
- Gnaw: v8 articulated leg/torso mesh, shoulder and hip movement, planted paws, short lunge, wind trail, approved illustrated independently animated upper/lower teeth and crimson aura over Ironbound. Preserve the effect and timing.
- Bone Eruption: v11. Full-body airborne jump rather than stretching planted feet; ground shadow changes during flight; landing triggers upright approved painted bone spikes in seven staggered sections only under player; red glow, dust and debris; translation-only screen shake, absolutely no zoom. User approved v11.

### Remaining (5/8)
- Flesh Knit (next): regeneration effect.
- God Roar.
- Rib Guard.
- Division: split into two Lesser Maws.
- Death: Lesser Maw death.

## Workflow
Publish revisions directly to GitHub; update lab source and labs.json version; keep approved animations unchanged. User prefers approving standalone artwork mockups before integrating detailed effects. Numerical slider readouts and Copy Settings are available. Do not guess approved settings. Test in browser before game integration. Bone Maw has not been integrated into the playable Godot build yet.
