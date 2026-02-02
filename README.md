🌳 Treekipedia

Branch into Knowledge. Treekipedia is an interactive knowledge visualization tool that transforms Wikipedia articles into organic, growing "Trees of Knowledge." Instead of scrolling through text, you plant a topic and watch as its sections sprout into roots, allowing you to dig deep into the history, etymology, and details of any subject in a beautiful, nature-inspired environment.

<br>

🍃 Features

Organic Hierarchy: Visualizes the Wikipedia Table of Contents as a tree structure. The main topic is the Canopy, and sections (like History or Geography) are Roots that burrow into the soil.

Deep Discovery: Click on any root to unearth sub-topics specifically mentioned within that section's text.

Permanent Field Journal: A pinned sidebar with a "Vintage Parchment" aesthetic. It displays a cleaned, easy-to-read summary of the currently selected root.

Advanced Sanitization: A custom engine that strips Wikipedia's administrative clutter, CSS leaks, and metadata to provide a pure reading experience.

Dynamic Environment: A responsive canvas featuring sky gradients, drifting clouds, grass-lined horizons, and textured soil with buried stones.

Exclusive Growth: Clicking a root automatically focuses the view by collapsing irrelevant siblings, keeping your discovery path clear.

<br>

🛠️ Tech Stack

Engine: D3.js for hierarchical tree layouts and smooth SVG transitions.

Styling: Tailwind CSS for layout and glassmorphic UI components.

Icons: Lucide React for nature-themed iconography.

Data: Wikipedia API (Action=Parse and Action=Query) for real-time content fetching.

Typography: Inter (Sans-serif) for UI and Lora (Serif) for the Field Journal.

<br>

🚀 How to Run Locally

Since Treekipedia is built as a single-file application, it is incredibly easy to set up.

Download the Code: Save the index.html file to your computer.

Open in Browser: Double-click index.html.

No Installation Required: All dependencies (D3, Tailwind, Lucide) are loaded via CDN, so no npm install is necessary for a quick start.

<br>

📂 Project Structure

cleanWikiHtml(): The "Nuclear Sanitizer" that removes CSS code and administrative fragments from Wikipedia data.

fetchTOC(): Retrieves the primary branching levels (Sections) for any given topic.

fetchSectionLinks(): A precision-fetching function that isolates HTML content to find links within specific paragraphs.

initCanvas(): Sets up the multi-layered SVG environment (Sky, Grass, Dirt).

updateTree(): The core D3 rendering loop that handles the "growth" animations and organic transitions.

<br>

🌲 Aesthetics

The Great Tree: A majestic, swaying canopy representing your primary search.

The Roots: Tapered, woody tendrils that grow as you explore deeper.

The Soil: A deep brown gradient peppered with pebbles and stones that appear as you scroll down.

The Sky: A bright, floating environment with drifting clouds.

<br>

📜 License

This project is open-source. Feel free to branch out, plant new features, and grow the code!
