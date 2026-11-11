---
name: import-board
description: Reads the person's filled-in planning board (Your story, The page, The look, What makes it you) and writes the Key context and Design system sections into CLAUDE.md. Use when they share that board or ask to import it.
---

The person has planned their portfolio site on a board and is sharing it: usually a picture of it, with whatever else they brought, such as files in this folder, links or a few lines in the chat. Your job is to write two sections of CLAUDE.md from it, Key context and Design system, which every later turn reads. Stop once the two sections are written, so they can check them before anything is built. The first build happens in this chat, from their board and CLAUDE.md.

If they haven't shared a board yet, ask for a picture of it, or a few lines on who they are, what the site is and how it should look.

## Understanding what they brought

People plan in different ways: notes, a sketch, a screenshot from a design tool, references with a word about each, a name dropped as shorthand for a whole sensibility. Use your judgement about what each thing tells you about them and the site they want. Open the files they added to this folder, pictures included, and the links that bear on the site: you can't place or describe a picture you haven't looked at. A site they name for its look shows that look only when rendered, so open it in the browser and look at it, not just its text. `setup-check/` was made by the setup check and isn't theirs. A link that won't open is a reference you couldn't see; say so in your reply.

## What a good first build needs

A good first portfolio build needs three things from them: who the site is for and what that visitor should do; real content, meaning a few sentences on each project about what they did and what came of it, or files and links that hold that; and a look of their own, from their references or how they describe it. Check what they brought against these. A project named in a few words is thin content, and a look described only in words that would fit anyone, such as clean or modern, isn't a look of their own yet. Where one is thin, ask in one round with AskUserQuestion before you write: they can fill it in a minute now, and a build without it comes out as placeholders, or as a site that could be anyone's. Ask two or three questions at most, with options drawn from what they mentioned, such as the old site or CV their board names, and going with what's here as one of them. For the look, offer two or three directions you read from their board. A link, a few lines or a file comes through Other or their next message; when they choose to add something, wait for it and read it before you write. If they brought what the build needs, write straight away. Their answers that decide something about the site go into the sections below; content they type stays in this chat for the build.

## Key context and Design system

Add the two sections at the end of CLAUDE.md, after Building and publishing: the file first says how you work with them, and these then give the context for building their site. They are in context on every turn, so they hold only what every change needs: what shapes the site, not its content, which the site itself will hold once it's built. Write them the way you'd brief a designer you trust: connected sentences that carry the reasons, with their own words quoted where they carry the point. Notes to them go in your reply. If the sections are already there, they're the person's current version: keep what's written, add what's new, and where the board disagrees, keep the file and mention it.

**Key context.** A few lines: who they are in a sentence, who the site is for and what that visitor should do and feel, what leads, what makes it theirs, and how they write, so new words on the site sound like them.

**Design system.** A small design system for them: the feel, the type, the colour, the layout idea, how images are treated and what it must never look like. Draw each choice from them (their references and what they said to take, their own work, the world their work lives in, what makes it theirs) and say in a few words where it came from, so they can see why and correct it. Where they gave you nothing for a choice, make one that fits what you know about them and say it was yours; a choice that would suit anyone isn't yet a choice for this person. Name the fonts and colours, with type the site can load from Google Fonts and a stand-in named where a reference uses another typeface. Scales, spacing values and component detail belong to the build.

## Your reply

Start your reply with exactly this:

> I've added your key context and a light design system to CLAUDE.md. They'll shape everything we do, so read them closely and change anything that isn't you.
>
> Open [CLAUDE.md](CLAUDE.md) and you'll find them at the end. I read this file before every reply, so change it there or tell me here, and add anything else you'd like me to keep in mind.

Then write "I chose these, so check them:" and list, a line each, the two or three choices most worth checking that came from you rather than from their board or their answers.

End by asking whether to build it now, here in this chat. When they say yes, read CLAUDE.md again before you build, since they may have changed it.
