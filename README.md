# SuperLunge


SuperLunge is a Paper plugin that adds a powerful off-hand spear lunge mechanic using the vanilla Lunge enchantment.


## Usage


### Outside-Game


- Drop the .jar file into your plugins folder, then reload the server. You should see a new folder there titled "SuperLunge". If this happens, the plugin worked without any issues.


### In-Game


- Hold a spear with Lunge in your off-hand
- Right-click to launch
- Jump first for best results
- Certain angles may not work


## Config
All force values are configurable per spear tier, in plugins\SuperLunge\config.yml.


## Permissions
- superlunge.reload


This reloads the configuration file for SuperLunge.


## Optional


- Drop `superlunge_airborne.json` into:
  `plugins/SuperLunge/advancements`


This enables an optional advancement for staying airborne for 30 seconds using SuperLunge alone.


## Platforms


- Paper (Tested)
- No others have been testred, you are welcome to try any of them







Description:

SuperLunge

SuperLunge brings high-risk, high-reward movement mechanics to Minecraft by enabling off-hand spear lunging with extreme momentum, physics-based traversal, and combat synergy.

This plugin is built around one core idea:

Movement matters. Physics matter. Power is earned — not free.

If you like chaotic mobility, skill-based traversal, and turning yourself into a guided missile, SuperLunge is for you.
Core Features
Off-Hand Spear Lunging

Use right-click while holding a spear in your off-hand

Applies a powerful directional launch based on where you’re looking

Works in any direction:

Forward

Upward

Downward

Designed to feel fast, weighty, and dangerous
Vanilla Enchantment Integration

Fully uses the vanilla Lunge enchantment

Higher enchantment levels increase launch power

No custom enchants required — works with existing game mechanics

Tier-Based Force Scaling

Each spear tier applies different base force:

Wooden Spear → lowest force

Stone / Iron → moderate force

Diamond / Netherite → extreme force

This ensures:

Early-game usability

Late-game chaos

Clear progression without power drops

Configurable Force Values

Every spear tier’s force is configurable via config.yml.

You can:

Nerf it for survival servers

Crank it up for chaos servers

Fine-tune values down to decimals (1.0 → 0.999999 if you want)

No rebuild required — just reload or restart.
Fall-Damage Immunity (WARNING: THIS IS BUGGY AND WILL SOMETIMES ALLOW YOU TO FALL COMPLETELY FINE WITHOUT USING THE LUNGE)

After using SuperLunge, players are temporarily immune to fall damage

Immunity is removed once the player safely touches the ground

Encourages:

Vertical traversal

Risky aerial movement

Skillful landings
Durability Cost (Balanced Risk)

Using SuperLunge consumes spear durability

Prevents infinite use

Makes repeated lunges a strategic choice rather than a free escape

Built-In Anti-Spam (Physics-Based)

Instead of artificial cooldowns:

Consecutive lunges can cause momentum loss

Excessive use may trigger Minecraft’s internal movement checks

Rewards timing and positioning

This creates an organic cooldown that:

Feels natural

Preserves speed

Prevents using the lunge at the speed of light
Traversal & Combat Synergy

SuperLunge excels at:

Long-distance traversal

Vertical movement without Elytra

High-impact melee engagements

Momentum-based combat (especially when paired with vanilla mechanics)

Yes — it can absolutely turn you into a warden-deleting missile if used correctly.
Lightweight & Self-Contained

No dependencies (other than a plugins folder and a paper plugin loader)

No required resource packs

No client mods

Works on Paper

Designed to be simple, fast, and stable
Intended Playstyle

SuperLunge is not designed to be safe.

It is:

High speed

High risk

High reward

Misuse it, and you’ll lose momentum or break your spear. Master it, and you’ll bend Minecraft’s physics to your will.
Server Owner Notes

Extremely high force values may trigger:

“Moved too quickly!” warnings

Momentum loss on consecutive uses

This is intentional and acceptable behavior

Server owners are encouraged to tune force values to match their gameplay vision
Philosophy

Minecraft is at its best when:

Physics matter

Movement matters

Risk matters

Power is earned

SuperLunge is built around that belief.
