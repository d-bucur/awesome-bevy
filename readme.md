# Description
A personal list of projects and resources that enhance the Bevy experience. These can either be libraries that work directly with Bevy or that are easy to integrate with some example integrations provided.

# Contents
- [Description](#description)
- [Contents](#contents)
- [General learning](#general-learning)
- [Tutorials](#tutorials)
- [Libraries](#libraries)
  - [Input](#input)
  - [Physics](#physics)
  - [Networking](#networking)
  - [AI](#ai)
- [Other](#other)
- [Development](#development)
- [Games](#games)
  - [Bevy Game jams](#bevy-game-jams)
  - [Prototypes](#prototypes)
  - [Upcoming](#upcoming)
- [Useful Rust tools](#useful-rust-tools)
- [Uncategorized](#uncategorized)

# General learning
- [Official examples](https://github.com/bevyengine/bevy/tree/main/examples): Has a lot of examples on how to use most of the features of the engine. Are always kept up to date with the latest API
- [Rust API Docs](https://docs.rs/bevy/latest/bevy/): Great descriptions and some simple examples
- [Unofficial Bevy Cheat Book](https://bevy-cheatbook.github.io/): A full book that explains in detail all the concepts of the engine similar to the Rust book
- [Blog posts](https://bevyengine.org/news/bevy-0-11) for each new version often contain code showing how to use the new APIs
- [Community](https://bevyengine.org/community/): a list of all the official communities, with the most active being Discord and Github Discussions
- [Bevy Assets](https://bevyengine.org/assets/): The original awesome list. Always check the version as some of them are quite old and the API has changed a lot since then
- See [Games](#games) section for more source code

# Tutorials
- [Snake](https://web.archive.org/web/20230301215439/mbuffett.com/posts/bevy-snake-tutorial/): Uses an old version and the original site is unavailable, but still a great starter tutorial
- [Minesweeper](https://dev.to/qongzi/bevy-minesweeper-introduction-4l7f): Uses an old version, but if you're struggling with how to structure a classic game using ECS it is still worth a read
- [Best practices](https://github.com/tbillington/bevy_best_practices): Opinionated list of best practices
- [Dependency injection engine](https://promethia-27.github.io/dependency_injection_like_bevy_from_scratch/introductions.html): Covers how to build a simple engine from scratch. Inspired by Bevy

# Libraries
## Dev tools
- [bevy_editor_pls](https://github.com/jakobhellermann/bevy_editor_pls): GUI editor
- [bevy-inspector-egui](https://github.com/jakobhellermann/bevy-inspector-egui): Inspect components and entities with a runtime GUI
- [bevy_mod_debugdump](https://github.com/jakobhellermann/bevy_mod_debugdump): A system execution graph

## Graphics
- [Vello](https://github.com/vectorgameexperts/bevy-vello): vectorial rendering that supports SVG and lottie

## Input
- [Leafwing input manager](https://github.com/Leafwing-Studios/leafwing-input-manager): An input manager for keyboard, mouse and gamepad
- https://github.com/JoJoJet/bevy-mouse-tracking TODO
- https://github.com/johanhelsing/bevy_pancam TODO

## Physics
- [bevy_rapier](https://github.com/dimforge/bevy_rapier): An integration with the popular 2D/3D [Rapier](https://rapier.rs/) Rust physics engine
- [Bevy raycast](https://github.com/aevyrie/bevy_mod_raycast): Simple raycast system
- [Bevy XPBD](https://github.com/Jondolf/bevy_xpbd): 2D and 3D physics engine based on Extended Position Based Dynamics

## Networking
- [Matchbox+GGRS](https://johanhelsing.studio/posts/extreme-bevy): A tutorial that uses [GGRS](https://github.com/gschup/ggrs) and [Matchbox](https://github.com/johanhelsing/matchbox) to create an online p2p multiplayer using rollback netcode in Bevy. Both libraries also have examples on how to integrate them with Bevy
- [Renet](https://github.com/lucaspoffo/renet): Server/Client network library for multiplayer games

## UI
- [Lunex](https://github.com/bytestring-net/bevy-lunex): Path based layout system with an impressive demo

## AI
- [Bonsai](https://github.com/Sollimann/bonsai): Behaviour trees for your AI

# Other
- [bevy_proto](https://github.com/MrGVSV/bevy_proto): Load entity definitions from files. Supports inheritance and hierarchies, similar to Unity prefabs
- [Particular](https://github.com/Canleskis/particular): Nbody simulation library with great performance

# Development
- [GitHub CI Template](https://github.com/bevyengine/bevy_github_ci_template): Get started with GitHub actions for CI/CD. Includes publishing to itch.io
- [VSCode snippets for Bevy](https://github.com/pixldev/bevy-snippets): Save time on typing repetitive code
- [My VSCode snippets](https://github.com/d-bucur/dotfiles/blob/main/.config/Code/User/snippets/rust.json): My personal VSCode snippets for Bevy and Rust in general

# Games
## Bevy Game jams
Most of the games developed for the jam are open source and are a great way to see some real world usage of the engine. Keep in mind that they are a bit harder to read than specific examples since they have the context of a more complex project. And they might not always be the best practices for writing code as game jams are relatively short and people often do nasty workarounds to meet the deadline.

- https://itch.io/jam/bevy-jam-1
- https://itch.io/jam/bevy-jam-2
- https://itch.io/jam/bevy-jam-3
- https://itch.io/jam/bevy-jam-4
- https://itch.io/jam/bevy-jam-5
- https://itch.io/jam/bevy-jam-6

## Prototypes
- [Build A Better Buddy](https://github.com/cart/build_a_better_buddy): a cute auto-battler
- [Card Combinator](https://github.com/cart/card_combinator): A card resource management game, similar to Stacklands
- [Flock fusion](https://github.com/paul-hansen/bevy-jam-2): You're going to make a flocking simulator anyway. Might as well turn it into a game.
- [Subfuse](https://dgriffin.itch.io/subfuse): Great lighting and atmosphere overall
- [One Clicker](https://github.com/Red-Teapot/CombinerClicker): An arithmetic clicker/factory game
- [Fish Folk Punchy](https://github.com/fishfolk/punchy): A 2.5D side-scroller beatemup
- [Digital Extinction](https://github.com/DigitalExtinction/Game): A 3D RTS game
- [Doomé](https://github.com/Patryk27/doome): A Doom clone made for the Game Off 2022 jam. A lot of custom components, but uses some bevy ECS features

## Released
- [Tiny Glade](https://store.steampowered.com/app/2198150/Tiny_Glade/): A small relaxing game about doodling castles. Uses a custom renderer with Bevy ECS
- [Tunnet](https://puzzled-squid.itch.io/tunnet): Build an underground computer network

## Upcoming
- [Jarl](https://www.jarl-game.com/): Norse fantasy colony simulator
- [Times of Progress](https://store.steampowered.com/app/2628450/Times_of_Progress/): City builder in the industrial revolution
- [Settletopia](https://store.steampowered.com/app/3533480/Settletopia/): Colony sim with multiplayer
- [Unhaunter](https://github.com/deavid/unhaunter): 2D isometric investigation game
- [One Planet](https://buttondown.email/oneplanet/archive/one-planet-a-climate-strategy-game/): Grand strategy game about climate crisis

## Cancelled
- [Emergence](https://github.com/Leafwing-Studios/Emergence): An organic factory builder in early stage

## Other
- [Awesome Prod](https://github.com/Vrixyz/bevy_awesome_prod): A more complete list of projects

# Useful Rust tools
- [arewegameyet](https://arewegameyet.rs/): A more general collection of Rust tools for gamedev. Not specific to Bevy
- [rand](https://github.com/rust-random/rand): You're probably going to be using randomness a lot so might as well import the crate
- [Serde](https://github.com/serde-rs/serde): Serialization framework. When you need to save data to disk or send it on the network.
- [Rayon](https://github.com/rayon-rs/rayon): A parallelism library. When Bevy's parallelization is not enough for you, just install this library and you're one `par_iter()` away from (mostly) data race free threading. Get those slacking cores to work!
- [Criterion](https://github.com/bheisler/criterion.rs): Benchmarking library
- [flamegraph](https://github.com/flamegraph-rs/flamegraph): generates easy to read reports to troubleshoot performance issues (haven't tried with Bevy yet)
- [colorgrad](https://github.com/mazznoer/colorgrad-rs): Generates color gradients for beautiful interpolation

# Uncategorized
- https://github.com/zkat/big-brain
- https://github.com/sharkdp/hyperfine ?
- https://github.com/sagiegurari/cargo-make
- https://github.com/samueltardieu/pathfinding
- https://github.com/petgraph/petgraph
- https://github.com/ElliotB256/bevy_combat
- https://github.com/djeedai/bevy_tweening
- https://github.com/vleue/bevy_easings
- https://github.com/james-j-obrien/bevy_vector_shapes
- https://github.com/Nilirad/bevy_prototype_lyon

