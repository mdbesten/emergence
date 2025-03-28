Contributing Guidelines
Welcome, and thank you for your interest in contributing to Emergence, a collaborative project inspired by the game Discovery, focusing on the evolution of peer production.

Your contributions—whether related to data, design, documentation, or code—are valuable and appreciated. Please follow the guidelines below to ensure smooth collaboration.

📁 Project Structure
cards.csv — Main dataset containing the card deck. This is the core of the project.

cards.tex — LaTeX template for generating a printable version of the deck.

README.md — Overview of the project.

wiki/ — Supplementary documentation (terms, history, game rules).

✅ How to Contribute
1. Fork the Repository
Create your own copy of the repository by clicking on "Fork" in the top right corner. Clone it locally:

bash
Copier
Modifier
git clone https://github.com/your-username/emergence.git
cd emergence
2. Set Up
Make sure you understand the structure of cards.csv. Each row corresponds to a card and contains historical or technological information.

For LaTeX rendering, you can use Overleaf with the necessary packages: flashcards, datatool.

3. Contribution Types
Here are the ways you can contribute:

📊 Data Contribution
Add new cards to cards.csv (make sure they are unique and historically relevant).

Standardize fields (e.g., format dates as YYYY, avoid ambiguous terminology).

Categorize entries into time periods or themes (e.g., “Free Software”, “Web 2.0”, etc.).

Enrich cards with relevant metadata (e.g., “Dependency”, “Period Label”).

🛠 Code Contribution
Fix issues with the LaTeX template (cards.tex) or improve formatting.

Create scripts (Python, R, etc.) to validate or process the CSV content.

📖 Documentation
Improve the project README.

Contribute to the wiki: glossary, visual aids, historical context.

Add visual examples to explain the gameplay or historical concepts.

4. Sign Your Contributions
All contributions must be signed with your full name in the commit message or Pull Request description, for academic accountability.

Example:

pgsql
Copier
Modifier
Signed-off-by: Your Full Name <your.email@example.com>
5. Credit Statement
To be listed as a contributor, please add your name to the credits.md file, with a short sentence summarizing your contributions.

6. Code & Data Quality
Be respectful of the structure and formatting rules in cards.csv.

Avoid duplicating cards.

Keep consistent naming for categories and tags.

Use ISO date format: YYYY (e.g., 1991).

Add comments to explain any non-obvious change.

7. Collaboration & Issues
Before large changes, open an issue to discuss it with the team.

Use clear, concise titles and descriptions.

Assign tasks if collaborating with others (e.g., via GitHub Issues or Projects tab).

Tag your issues and Pull Requests with appropriate labels (e.g., data, wiki, enhancement).

8. Pull Requests
One pull request per logical set of changes.

Make sure your branch is up-to-date before submitting.

Describe clearly what your changes include and which files are impacted.

Tag a team member for review if needed.

9. Respect & Inclusion
We are committed to a respectful, inclusive, and collaborative environment. All contributors must follow the Code of Conduct.

