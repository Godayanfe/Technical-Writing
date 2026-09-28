# Git vs GitHub

To avoid confusion, let's briefly differentiate the two — because these are two of the most mixed-up terms for anyone just starting out.

## Git

Git is a software application installed directly on your computer. Its job is to save and track the history of every change made to your code, locally, without needing an internet connection.

Think of it like a **CCTV camera** — but instead of recording activity in a room, it records activity in your code: what was added, what was removed, and exactly when it happened. Just like footage lets you rewind and see what occurred at any point in time, Git lets you look back at any previous version of your project.

Because Git runs entirely on your own machine, collaboration is actually possible using Git alone, without GitHub at all:

- **Peer-to-peer** — developers can send updates directly to each other over a local network
- **Email** — developers can share code patches back and forth as file attachments
- **Private servers** — a team can set up and host their own private Git server, independent of any third-party platform

This shows that Git itself is the core engine doing the tracking — GitHub is simply one (very popular) way of using it.

## GitHub

GitHub, on the other hand, is a cloud platform built on top of Git, designed for storing and sharing code online.

If Git is the camera recording locally, GitHub is the cloud where that footage gets uploaded — making it visible, searchable, and usable by anyone you give access to, from anywhere in the world.

This is why most teams prefer using GitHub over relying on Git alone. GitHub adds a visual, user-friendly layer over Git that makes teamwork significantly easier:

- **Central hub** — everyone has one shared online location to push updates to and pull updates from, instead of manually sending files back and forth
- **Pull Requests** — before any change is merged into the main project, teammates can review it, leave comments, request edits, or approve it
- **Project management tools** — built-in features for tracking bugs, assigning tasks, and holding discussions, all attached directly to the code they relate to

## Putting It Together

A helpful way to remember the difference: **Git is the tool, GitHub is the platform.** Git does the actual work of tracking changes on your machine; GitHub takes that tracked history and makes it accessible, reviewable, and shareable with anyone else working on the project — whether that's one collaborator or an entire team spread across different locations.
