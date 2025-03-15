# 👋 Welcome to Dendro

`Dendro` is the simple opportunity solution tree tool for product teams.

## What is Dendro

`Dendro` is an app for product managers to easily create Opportunity Solution Trees (OSTs) using text/markdown/code. The goal is to reduce frustration using a whiteboard app and moving around post-its and shapes. New opportunity to map to an outcome no problem, new idea or assumption, no problem, just add a new line at the appropriate place and the app creates your map.

## Usage

The syntax is based on indentation levels with optional status emojis:
- Level 0 (no indent): Objective
- Level 1 (2 spaces): Opportunity
- Level 2 (4 spaces): Idea
- Level 3 (6 spaces): Assumption

Add status emojis at the end of any line using `:emoji_name:`

## Status Emojis

- 🔭 `:telescope:` - Being explored
- ✅ `:white_check_mark:` - Completed/Verified
- 🚧 `:construction:` - In progress
- ❌ `:x:` - Rejected/Invalid
- 💡 `:bulb:` - New idea
- ❓ `:question:` - Needs validation
- 🎯 `:dart:` - On target
- ⭐ `:star:` - Priority

## Example

```
Increase User Engagement 🎯
  Improve DAU 🔭
    Add Gamification ⭐
      Users respond well to rewards ❓
      Competition drives engagement ✅
    Implement Social Features 🚧
      Users want to connect 💡
  Enhance User Experience ⭐
    Simplified Navigation :construction:
      Current navigation is complex :white_check_mark:
```
