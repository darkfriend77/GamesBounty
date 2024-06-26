# Name of your Project

> This document will be part of the terms and conditions of your agreement and, therefore, needs to contain all the required information about the project. Don't remove any of the mandatory parts presented in bold letters or as headlines (except for the title)! Lines starting with a `>` (such as this one) should be removed. Please use markdown instead of HTML (e.g., `![](image.png)` instead of `<img>`).
>
> See the [Games Bounty Application](https://github.com/PolkadotPlay/GamesBounty/#pencil-process) on how to submit a proposal.

- **Team Name:** Single Dev or Team (this is to be defined)
- **Funding Details:**
  - **DOT**: 5'000 DOT

> :exclamation: *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*

## Game Project Overview :page_facing_up:

# Game Project Application Form

| <img src="https://github.com/darkfriend77/GamesBounty/assets/17710198/cf787552-e3b6-49bc-a185-34d443ce69db" width="200"/> | <img src="https://github.com/darkfriend77/GamesBounty/assets/17710198/110341ec-4e9f-4210-9e13-bdbaa8750f23" width="200"/> | <img src="https://github.com/darkfriend77/GamesBounty/assets/17710198/3b5427b2-d536-408b-9913-e96aee06ab7c" width="200"/> | <img src="https://github.com/darkfriend77/GamesBounty/assets/17710198/fe2c494c-76f9-4591-b537-eedd9e60a151" width="200"/> |

![image](https://github.com/darkfriend77/GamesBounty/assets/17710198/2e3a7d15-220e-43be-a56e-a9a39bdaa0c7)


## 1. Pitch the Game

### Please describe the game in a short pitch.
"Dot 4 Gravity" combines the strategic depth of classic board games with the excitement of interactive play. Utilizing a dynamic 10x10 board, players drop stones that slide across the board to form patterns or activate bombs. The objective is to strategically place stones and bombs to outmaneuver the opponent and achieve victory. This blockchain-based game allows players to own unique in-game assets, enhancing the gaming experience with real-world value.

### Please describe the game's core loop? (minimalistic)
Place Bombs -> Place Stones -> Form Patterns/Trigger Bombs -> Victory/Defeat

### Are there any existing games that you would consider similar to your project?
Dot 4 Gravity shares similarities with games like Connect Four and Minesweeper, but it offers a unique twist by combining these mechanics with blockchain technology, allowing for asset ownership and strategic depth.

### Do you have a Game Design Document (GDD) for your project?
Yes, there is a GDD, but since the game has all the components already built and developed, it's probably more useful to share a video https://www.youtube.com/watch?v=VXwb8YSnjRQ of the MVP

Outtakes of the GDD

- Game Plattform Mobile only, developed in Unity
- Core Mechanics
  - Board: 10x10 grid
  - Stones: Players drop stones that slide towards the opposite side until blocked.
  - Bombs: Players can place bombs that detonate and remove stones within a 3x3 area.
- Game Phases
  - Initialization Phase
    - 10 random blocks are set on the board. (Obstacles)
  - Bomb Phase
    - Each player can place 3 bombs on the board. Bombs are hidden from the opponent (rock-paper-scissor, hash & reveal) and detonate when a player, sees a strategical advantage through clearing the 3 x 3 area.
  - Play Phase
    - Turn-based gameplay where players drop one stone per round.
    - Stones slide across the board until they reach a blocked position or the edge.
    - Bombs detonate when a stone tries to pass through them, removing stones in a 3x3 area.
  - Objectives
    - Win Condition: Create three square patterns on the board or connect four in a row.
    - Bombs: Strategic placement to remove opponent’s stones.


## 2. Game Dev Experience

### Have you built games prior to this bounty request?
Yes, we do have experience in GameDev, but in this application, we are looking for a single dev, or a team that takes up this work, similar to a contract.

### Do any of the previously mentioned games have a Web3 component?
Yes, we do have experience in building Web3 components, but in this application, we are looking for a single dev, or a team that takes up this work, similar to a contract.

### Do you have experience in working with game engines, such as Unity & Unreal?
Yes, we do have experience in GameDev, but in this application, we are looking for a single dev, or a team that takes up this work, similar to a contract.

The project has already an implementation in Unity, with all the Art and Designs ready.
https://github.com/ajuna-network/game-dot4-unity

## 3. Technical Expertise

### How much of your game logic do you intend to build on the blockchain?
- [ ] None, I just want a token.
- [ ] Only the Game Assets/NFTs should remain on-chain.
- [ ] Some mechanics will need to be on-chain.
- [X] This should be a fully on-chain game.
- [ ] Other: 

### Do you have any expertise in Blockchain Development?
- [ ] No, none at all.
- [ ] I know how the Blockchain works, but never developed anything in crypto.
- [ ] I have EVM / SmartContract experience.
- [ ] I have only used SDK for my games on other platforms.
- [ ] I know Rust & Substrate and can create basic runtime code.
- [X] Other: Polkadot Play will offer assistance for this.

### Would you like a technical Team from Polkadot Play, to help you identify the technical requirements?
A technical engineer from Polkadot Play, will support the team or dev for free. 

## 4. The Team

### Could you share insights about team members who are essential to your project's success? Highlight their specific skill sets and contributions to the game development. 

#### Team member #1
To be found!

### Team Code Repos
https://github.com/ajuna-network/game-dot4-unity
https://github.com/ajuna-network/ajuna-games

### Team LinkedIn Profiles (if available)
To be found!

## 5. Development

### Development Status :open_book:
MVP done, Frontend in Unity MVP, Backend in Substrate done.

### What are the key milestones for your game's development, and what are the estimated completion dates for each?
- **Milestone 1:**
- **Milestone 2:**
- **Milestone 3:**

### Are you intending to raise more funds?
- **If yes,** please describe what you expect to be the full amount needed to finalize the product.

## 6. Detailed Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your game project is related to Substrate, Kusama, Polkadot, or a (System-)Parachain. We *recommend* that teams structure their roadmap as 1 milestone ≈ 1 month.

> :exclamation: If any of your deliverables are based on somebody else's work, make sure you work and publish *under the terms of the license* of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Projects that submit other people's work without proper attribution will be immediately terminated.**

### Overview

- **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
- **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
- **Total Costs:** Requested amount in DOT for the whole project (e.g. 2,500 DOT).

### Milestone 1 Example — Basic functionality

- **Estimated duration:** 3 month
- **FTE:**  1
- **Costs:** 5,000 DOT

> :exclamation: **The default deliverables 0a-0d below are mandatory for all milestones**, and deliverable 0e at least for the last one. Examples of steps are shown in 1 - 8.

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| **0a.** | License | Specify the IP owning entity; ensure proper copyright compliance for all reused materials, including appropriate licenses and attributions, or choose an open-source license (Apache 2.0, GPLv3, MIT, Unlicense). |
| **0b.** | Documentation | Provide comprehensive **inline documentation** of the code and a detailed **tutorial**. The tutorial should guide users on how to set up, play the game, and assess the milestone's deliverables, ensuring functionality and compliance with the milestone objectives. |
| **0c.** | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| **0d.** | Platform | Provide a detailed description of the game's platform compatibility and the infrastructure setup required to host and run the game, including supported operating systems, hardware requirements, and necessary backend services. |
| 0e. | Article | We will publish an **article**/workshop that explains [...] (what was done/achieved as part of the games bounty). (Content, language, and medium should reflect your target audience described above.) |
| 1. | Backend module: dot4gravity pallet | Documentation and feature testing, small minor changes possible, of the core mechnics. |
| 2. | Integration in C# | Write a complete abstraction in C#, which can be used for headless clients, for load testing, with bots, and most of all for a easy implementation into Unity, to abstract substrate based logic. |
| 3. | Frontend module: dot4gravity unity | Whole refactor of the logic, into the Unity UI Toolkit, and min. Unity v2022. Implement the new features for the new bomb logic, and rework on the animations. |
| 4. | Playable NodeTempalte | Create a docker setup that spins up solo chain, with Dot4Gravity pallet, accessible locally, with a headless Bot player as oponent. |
| 5. | Matchmaking Pallet | Refactor and add the UI Workflow for the matchmaking pallet. |
| 6. | (Optional) Elo Ratign Pallet | Add Elo Rating pallet from hexalem, and UI workflow |

## 7. Future Plans

Please include here

- Extend the game to have tournaments, participation fee, elo rating

## 8. Additional Information :heavy_plus_sign:

### While we've covered a range of topics, there might still be questions or areas of uncertainty on your side or ours. We encourage you to share any additional thoughts, questions, or concerns you may have, with us.

### How did you hear about the Grants Program?
- [ ] Polkadot Play Website
- [ ] Twitter
- [ ] Medium
- [x] Personal recommendation
- [ ] Other:
