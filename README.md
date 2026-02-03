# 🐱 Kitty Secret

A fun social deduction game where players try to identify the confused player among them by giving and analyzing clues.

## Features

- Real-time multiplayer gameplay using Supabase
- Advanced hosting features with player calling system
- Voice-guided gameplay with sound effects and ambient sounds
- Visual animations and smooth UI transitions
- Host takeover functionality for flexible game management
- Spectator mode for late joiners

## How to Play

1. Create or join a room with a 4-digit code
2. Wait for the host to start the game
3. Each player receives a secret word (either the "good" word or the "confused" word)
4. Players give one-word clues about their secret
5. Vote to eliminate the confused player
6. The game continues until the confused player is found!

## Tech Stack

- HTML5 / CSS3 / JavaScript
- Supabase (Real-time database and presence)
- Web Audio API (Sound effects)

## Setup

This game requires a Supabase backend. Configure your Supabase credentials in the `index.html` file.

## Deployment

Deploy to any static hosting service:
- GitHub Pages
- Vercel
- Netlify
- Cloudflare Pages

## Game Modes

- **Easy**: Simple, everyday concepts
- **Medium**: Abstract ideas requiring more thought
- **Hard**: Philosophical and nuanced concepts
