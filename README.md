# 🏔️ PANDORA — SLAG Enterprise Village (Deutsches KI-Dorf)

> *"One village. One system. Many specialist teams."*  
> *"Central company operating system connected to the learning engine."*

An aesthetic, interactive modern German alpine AI agent village built for real-world production: book publishing, app development, multimedia generation, enterprise research, and financial governance.

---

## 🌟 Key Features

1. **Modern German Alpine Village Architecture**:
   - Styled after sustainable Black Forest & Bavarian timber-framed chalets (*Fachwerk & Glasarchitektur*).
   - Charcoal slate roofs with solar arrays, floor-to-ceiling panoramic glass windows, and traditional red geranium flowerboxes.
   - Central cobblestone plaza (*Kaiserstein-Platz*) with the **Pandora Core** glass biosphere and water fountain.
   - Gently swaying pine and linden trees in the alpine wind.

2. **Living, Breathing Agent Simulation**:
   - 16+ animated agents walking along the cobblestone pathways.
   - Roles visualized by attire: **Founder** (royal gold), **Chief of Staff** (executive navy), **Department Directors** (purple/alpine suits), and **Workers** (high-visibility safety vests with blueprints, tripods, and manuscripts).
   - Real-time speech bubbles showing inter-department handoffs.

3. **12 Deep Interactive Building Interiors**:
   Click on any building to step inside and watch active production in action:
   - **🎬 Multimedia Production** (*Jonas Keller*): Broadcast studio cameras with flashing tally lights, audio mixing consoles with bouncing EQ visualizer bars, video timelines.
   - **📖 Publishing & Distribution** (*Elena Roth*): High-speed digital printing presses with rolling paper feeds, bookbinding stations, stacks of hardcover proofs.
   - **🪙 Finance & Bookkeeping** (*Daniel Petrescu*): Candlestick market monitors, cash-flow ledger, vault safe, and Apple M4 local cost-savings tracker ($0 API costs).
   - **🎓 Teaching Academy** (*Dr. Anna Weiss*): Tiered timber lecture hall, interactive AI tutor whiteboard, student learning progression dashboards.
   - **💻 IT & Systems** (*Victor Hahn*): Silent eco-cooled server racks with cascading green/cyan activity LEDs, live streaming bash/Python terminal, Ollama cluster status.
   - **🏛️ Town Hall & Management** (*Amelia Hart*): Grand council chamber with timber trusses, Founder podium, strategic roadmaps, and all-hands council meeting room.
   - **👥 HR & Recruitment** (*Sofia Becker*): Interview lounge, candidate Kanban pipeline, teacher development matrix.
   - **📢 Marketing & Growth** (*Leo Marin*): Moodboards, social media analytics feeds, ad copy A/B test boards.
   - **📅 Sales & Events** (*Clara Neumann*): Soundproof webinar booth, CRM deal funnel, strategy call stations.
   - **🎧 Customer Support** (*Laura Munteanu*): Live incoming customer ticket feed, sentiment satisfaction gauges, M4 FAQ knowledge base.
   - **🔬 Research & Innovation** (*Felix Ionescu*): Think-tank lab, trend radar scanning arXiv and AI breakthroughs, mind-mapping whiteboards.
   - **📦 Product Development** (*Mira Novak*): App wireframe drafting table, mobile test rigs, book manuscript chapter progression.
   - **✨ Pandora Core** (*Astra*): Central cognitive engine, holographic neural vectors, daily cross-department intelligence synthesis.

4. **Interactive Enterprise Controls**:
   - **Brief Dispatcher**: Submit real production briefs directly to any Director.
   - **Founder Review Queue ("Stay in Charge")**: Rule #7 enforcement—review and approve critical book layouts, model buffer allocations, or marketing releases.
   - **Time of Day Toggle**: Seamlessly switch between Alpine Day ☀️, Golden Hour Sunset 🌅, and Bavarian Night 🌙 with glowing lantern light.
   - **Generative Alpine Soundscape**: Synthesized mountain wind, birds chirping, and fountain water using the Web Audio API (zero audio downloads needed).

---

## 🚀 One-Click Deployment to Vercel & Cloudflare Pages

### Option A: Deploy to Vercel
1. Push this folder to your GitHub account (or use the attached repository).
2. Go to [vercel.com/new](https://vercel.com/new).
3. Import the repository and select **Other** as the Framework Preset (Root directory: `./`).
4. Click **Deploy**. Your village will be live in 10 seconds!

### Option B: Deploy to Cloudflare Pages
1. Go to your Cloudflare Dashboard $\rightarrow$ **Workers & Pages** $\rightarrow$ **Create Application** $\rightarrow$ **Pages**.
2. Connect your GitHub repository.
3. Build output directory: `./`
4. Click **Save and Deploy**.

### Option C: Run Locally on your Apple M4 Mac
```bash
# Clone the repository or navigate to this folder
cd pandora-village

# Launch a local server
npx serve -s . -l 3000
```
Open your browser at `http://localhost:3000`.

---

## 💻 Apple M4 Local Model Inference (Ollama / MLX)

To operate the village agents 100% locally with zero cloud API token costs on your M4 Mac:
```bash
# Install Ollama (if not already installed)
brew install ollama

# Start the Ollama local daemon
ollama serve

# Pull your preferred local models
# Fast Worker Model (8B–14B):
ollama pull qwen2.5:14b

# Deep Director Model (32B–70B):
ollama pull qwen2.5:32b
# or
ollama pull llama3.3:70b
```
The village interface automatically interfaces with your local Ollama endpoint at `http://localhost:11434`.

---

**SLAG Enterprise System** • *Infinity Learning & Production Infrastructure*
