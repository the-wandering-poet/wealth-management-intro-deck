# Wealth Management Intro Deck

Static HTML presentation deck for wealth management / asset allocation discussion.

## Project Structure

- `wealth_management_intro_deck.html` is the full presentation deck.
- `index.html` redirects GitHub Pages visitors to the deck.
- `assets/` contains the supporting charts, logos, and interactive chart page.

## View Locally

Open `wealth_management_intro_deck.html` in a browser.

## GitHub Pages

After pushing this repository to GitHub:

1. Open the repository on GitHub.
2. Go to `Settings` -> `Pages`.
3. Under `Build and deployment`, choose `Deploy from a branch`.
4. Select branch `main` and folder `/root`.
5. Save.

The deck will be available at:

`https://<owner>.github.io/<repo>/`

## Collaboration Workflow

Use branches and pull requests so multiple people can edit the deck safely.

1. Start from latest `main`.
2. Create a branch for the page you are editing, for example:
   - `edit/page-3-dca`
   - `edit/page-8-platforms`
3. Edit `wealth_management_intro_deck.html` and any related files in `assets/`.
4. Commit and push the branch.
5. Open a pull request into `main`.
6. Review the rendered GitHub Pages preview after merge.

If two people edit the same file, GitHub may ask you to resolve conflicts. Avoid conflicts by coordinating page ownership: one person edits Page 1-4 while another edits Page 5-9, or use separate branches and merge frequently.
