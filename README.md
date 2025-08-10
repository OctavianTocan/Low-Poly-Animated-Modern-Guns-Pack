# Low Poly Animated — Modern Guns Pack

Clean, stylized FPS-ready weapon art with professional first-person animations, modular attachments, and mannequin-ready rigs — built to help you prototype faster and ship better-looking shooters.

***

## Cover

_(Insert a cover image or GIF showcasing multiple weapons and a short animation loop)_

***

## Overview

This art pack delivers modern, low-poly gun models and first-person animations designed for quick FPS prototyping and polished presentation. Every weapon includes unique animation sets (reloads, inspections, fire variants, holster/equip, and more), plus modular parts and materials so you can iterate visually without friction. The content ships mannequin-ready for easy integration, with organized, commented example Blueprints to demonstrate usage and best practices.

> Important: The asset is rigged to the UE4 Mannequin skeleton and is not compatible with the UE5 Manny skeleton.

***

## What You Get

- First-person animation sets per weapon: Reload (normal/aimed/empty), Fire (hip/aimed), Inspect, Holster/Quick Holster, Unequip/Quick Unequip, Grenade Throw, Knife Attack, Walking Directional, Sprinting, and more
- Mannequin-ready first-person arms: Base Arms and Base Arms with Gloves (customizable materials inside the engine)
- Eight customizable modern weapons (skeletal, rigged, with swappable parts):  
  SMG (SP60), Pistol (X13), Sniper (MR22), Revolver (RC425), Shotgun (MAK12), Rocket Launcher (LRAF9), Assault Rifle (AG14W), Light Machine Gun (HVG7)
- Attachments: Vertical Grip, Angled Grip, Pistol Rail, Red Dot Scope, Silencer, Laser Pointer, Bipod
- 16+ gun materials: modern camos, pattern variants, and iron sight glowing dot variations
- Example Blueprints and Animation Blueprints: Fully commented, cleanly organized, and built to showcase how to use the included models and animations effectively

***

## Why This Pack

- Stylized, modern look with a consistent low-poly art direction that reads cleanly in motion.  
- Production-friendly: mannequin-ready and rigged assets reduce setup overhead so you can focus on gameplay.  
- Clear examples: commented Blueprints demonstrate patterns for importing, wiring, and previewing animations.  
- Extensible: modular weapon parts and a broad material set help you explore variations quickly.

***

## Low Poly Shooter Pack Integration

If you own both products, a dedicated integration is available on our Discord. It sets up these weapons to work with the Low Poly Shooter Pack’s systems. Watch the integration gameplay video to see it in action. Verification is required.

***

## Compatibility & Technicals

- Rigging: Epic UE4 Mannequin skeleton; includes IK bones
- Animations: 809 total, In-Place
- Characters: 2
- Materials & Instances: 129
- Textures: 576 total, with common resolutions (16x16 up to 2048x2048)
- Supported UE versions: 4.26–4.27 and 5.0–5.6
- Target platforms: Windows, Mac, Linux, consoles, mobile, VR (SteamVR/HTC Vive, Oculus), and more

***

## Resources

- Animation Showcase Videos — see every set in motion
- Animation List — browse all included files and coverage
- Windows Demo — try the animation and model showcase
- Discord — support, verification, and integration access
- Changelog — release updates and history

***

## Usage Notes

- This is an art-focused pack with example Blueprints meant for demonstration and learning; the examples are not production gameplay systems. Use the examples as a reference for hooking up models, animations, and presentation flows in your own projects.

***

## What I’m Most Proud Of

- Cohesive, plug-and-play pipeline: Developers can drop the pack into an existing project and have weapons, arms, and animations working with minimal setup thanks to clean Animation Blueprints, sockets, and example logic.  
- Technical animation integrity: Robust state machines, additive layers, and event-driven montages make reloads, inspections, firing states, and movement transitions feel smooth and predictable in first-person.  
- Demo scenes that “just work”: Every showcase level runs end-to-end out of the box, demonstrating practical weapon wiring and interaction without custom tooling.  
- Clear learning path: Documentation and YouTube videos walk users through installation, setup, and customization, accelerating onboarding and reducing support friction.  
- Future-proof structure: Asset organization, naming, and Blueprint patterns make it straightforward to extend with new weapons, materials, or attachments.

***

## My Contributions

- Gameplay and tooling programming: Implemented all Blueprint logic powering the demo scenes, weapon behavior samples, input handling, and presentation flows so developers can explore the pack interactively.  
- Animation Blueprints and state machines: Authored the complete first-person Animation Blueprint stack, including locomotion graphs, layered blends, montage triggers, event notifies, and IK/aim offsets for smooth transitions and reliable timing.  
- Systems integration: Built the glue that connects skeletal meshes, sockets, VFX/SFX placeholders, and animation events—ensuring assets are production-ready and easy to drop into real projects.  
- Documentation: Wrote setup guides, feature overviews, and best-practice notes to help users understand the structure and adapt it to their pipelines.  
- Video tutorials: Produced YouTube walkthroughs that demonstrate installation, configuration, and customization, plus tips for integrating with existing FPS frameworks.  
- Example architecture: Organized content folders, created commented example Blueprints, and provided reference implementations to encourage consistent usage patterns.

***

## How It Was Built

- Technical stack: Unreal Engine Blueprints for weapon logic, input mapping, and presentation; Animation Blueprints for locomotion and montage logic; event notifies for syncing audio/FX; IK and layered blends for first-person polish.  
- Design approach: Separate content into clean layers (assets, anims, ABP, example logic) to keep responsibilities clear; prefer data-driven settings and material instances for fast iteration; document decisions and expose key parameters.  
- Integration focus: Make common hooks obvious—animation events, sockets, and component structure are named and documented to shorten integration time for UE developers.

***

## Who This Is For

- Solo devs and small teams needing a polished FPS weapon foundation that’s easy to set up and iterate on.  
- Students and technical artists looking to study a clean Unreal asset pipeline from modeling and rigging to first-person animation and Blueprint examples.  
- Prototypers who want consistent visuals and animation coverage without building a weapons library from scratch.

***

## Technical Highlights (Optional)

- Layered first-person animation system with montage-driven actions (reloads, inspect, melee/throw) synchronized via notifies.  
- Aim offsets and IK to stabilize weapon/hand alignment during ADS, walk, sprint, and transition states.  
- Data-driven weapon configuration for quick swapping of attachments and materials without structural changes.  
- Clean content organization and naming conventions for predictable retargeting and reuse.

***

## Roadmap Ideas

- Additional weapon variants and attachments aligned to the same rig.  
- More inspect and fidget animations for variety.  
- Optional Manny/UE5 rig support if feasible without compromising the existing pipeline.

***

## Credits

Created and published by Infima Games. Special thanks to the community for feedback and support that helped shape the pack and its examples.

***

## License

Please refer to the license terms of the marketplace where you purchase the asset. Contact support via Discord for verification details and support flow.

***

## Portfolio Notes

This repository showcases the Low Poly Animated — Modern Guns Pack content and structure for portfolio purposes. It does not distribute the original commercial assets. For hands-on evaluation, use the official demo and public videos/resources listed in the Resources section. 
