# Seven Architectures Community Forum

This directory contains the implementation of the Seven Architectures Community Forum - a cosmic gathering space for consciousness explorers practicing the Seven Architectures.

## Features

- **Discussion Forums**: Six themed categories for practice support, experiences, group coordination, and community connection
- **Practice Tracker**: Log daily practice with architecture focus, duration, quality ratings, and notes
- **User Profiles**: Member profiles with practice statistics, streaks, and recent activity
- **User Directory**: Searchable member directory with filters for location and experience level
- **Thread Bookmarking**: Save interesting discussions for later reference
- **Image Upload**: S3-integrated avatar uploads for profile customization
- **Onboarding Tour**: Interactive guided tour for new members
- **Cosmic Design**: Starfield effects and gradient aesthetics matching the Seven Architectures theme

## Technology Stack

- **Frontend**: React 19 + Tailwind CSS 4 + shadcn/ui
- **Backend**: Express + tRPC 11 + Drizzle ORM
- **Database**: MySQL/TiDB
- **Storage**: S3 for file uploads
- **Auth**: Manus OAuth integration

## Live Forum

Visit the community at: https://sevenforum-dxkdha8l.manus.space

## Source Code

The complete source code is deployed via Manus platform. Key features implemented:

### Database Schema
- Users with profiles, bios, locations, experience levels
- Discussion threads with categories and view/reply counts  
- Thread replies with nested conversations
- Practice entries with architecture tracking and quality ratings
- Bookmarks for saving threads
- Practice milestones

### API Endpoints (tRPC)
- Authentication (OAuth, logout)
- Forum operations (threads, replies, categories)
- Practice tracking (log entries, stats, milestones)
- User management (profiles, directory search)
- Bookmarking system
- File uploads (S3 avatar storage)

## Getting Started

New members are greeted with an interactive onboarding tour highlighting:
1. Discussion forum categories
2. Practice tracking features
3. Community directory
4. Profile customization
5. Navigation overview

## Community Guidelines

This platform supports the Seven Architectures practice community with:
- Respectful dialogue and shared learning
- Practice accountability and support
- Experience sharing and collective wisdom
- Connection between local practitioners
- Integration of consciousness work into daily life

---

*Built with love for the consciousness exploration community*
