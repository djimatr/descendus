# Descendus

A sci-fi/horror novel loosely based on Dante's Inferno, set on an AI-constructed world millions of years into the future.

## Current Progress Tracker
- [ ] Master Lore Definition (`/lore/master_lore.md`)
- [ ] Chapter: Andreia — Beat Sheet
- [ ] Chapter: Andreia — Draft 1 (Scribe Stage)

## Step 1: Feed the Context into the Chat Sidebar
Click into the Continue chat input box on your left sidebar and build your context engine by tagging your folders and individual files using @.

Type this exact instruction structure into the sidebar chat box:

Let's synthesize our workspace into a full prose chapter. Refer to @templates/scribe_rules.md for formatting, @templates/voice_sample.md for the hardboiled prose voice, and @lore/continuity_log.md and @lore/world_rules.md for narrative consistency.

Pull character data from @characters/abernathy.md, @characters/nadia.md, @characters/santos.md, and @characters/virgil.md.

Based entirely on the outline beats inside @chapters/chapter_ONUS_Part_2.md, generate the complete, immersive prose for this chapter below.

## Step 2: Run the Generation
Press Enter. GLM 5.2 will ingest all attached files and begin rendering the drafted chapter prose directly in your sidebar chat pane.

## Step 3: Write it to a Separate Markdown File
Once the model finishes generating the text in the sidebar, you need to save it into your workspace as its own distinct file:

Look at the top right corner of the prose code block that GLM 5.2 generated in the sidebar.

Click the "New File" icon (it looks like a little sheet of paper with a plus sign, or a small page icon next to the "Insert" arrow).

If your extension version doesn't show the direct "New File" shortcut, simply hit the Copy icon on the block.

Press Ctrl + N in VS Code to create a clean, empty file.

Paste your prose inside it (Ctrl + V).

Press Ctrl + S to save, and name it something like chapters/prose_ONUS_Part_2.md to keep your structural beats separate from your final narrative manuscript.