# Offline Family Tree

## Why This Exists

A family tree is a legacy. It belongs to the family, not to a website or a subscription service.

Traditional family tree applications trap your data in proprietary formats, require accounts, depend on cloud services that may disappear, and make sharing difficult. Your grandmother shouldn't need to create an account just to see her grandchildren.

**The solution is simple: a single HTML file.**

An HTML file can be:
- Sent via email or messaging apps
- Opened on any device with a web browser
- Stored on a USB drive, cloud storage, or printed
- Viewed offline, forever
- Shared across generations without technical barriers

This is why Offline Family Tree exists: to create self-contained, portable family trees that work everywhere and belong to no one but your family.

## How It Works

The family tree is a single HTML file that serves as both viewer and editor:

- **On a computer**: Open the file in a browser to view, edit, add family members, and export
- **On mobile devices**: View and navigate the tree (editing requires a computer)
- **On iOS or in email**: The tree displays using a pure CSS fallback that works even when JavaScript is blocked

When you export, you get a complete copy of the application with your family data embedded. This exported file can be:
- Shared with family members for viewing
- Opened on another computer to continue editing
- Re-exported after making changes

**Images are deduplicated**: Each photo is stored once in the CSS, then referenced by class name. This keeps file sizes reasonable even for large families.

## Features

- Add family members with names, birth dates, places, photos, and biographies
- Define parent and spouse relationships (the app infers children and siblings)
- Navigate visually: see parents above, siblings and spouses alongside, children below
- Export the entire tree or a subtree starting from any person
- Open and edit previously exported files
- Works offline - no internet required
- No accounts, no cloud, no subscriptions

## Usage

1. Open the HTML file in any modern web browser
2. Add your first family member
3. Continue adding family members and setting their parents
4. Click "Export HTML" to download a copy of your family tree
5. Share the exported file with family members

To continue editing:
- Simply open any exported file on a computer and make your changes
- Export again to save your updates

## Privacy

- No data is ever sent to any server
- All data stays in your browser or in the HTML file itself
- Exported files contain only what you put in them
- You control where your family data lives

## About This Project

This application is a result of **vibe coding**.

**100% of the code was AI-generated without human intervention in the resulting code.** The human provided requirements, feedback, and direction; the AI wrote every line of HTML, CSS, and JavaScript.

This is an experiment in what's possible when you describe what you want and let AI figure out how to build it.

## License

Released under the ELI-1.0 license. Check the LICENSE file for details. 
