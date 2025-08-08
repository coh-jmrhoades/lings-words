# Words & Web Pages

A collection of web pages inspired by Justin Jackson's [words.html](https://justinjackson.ca/words.html), each exploring different themes while maintaining the same minimalist philosophy.

## Pages

- **Home** (`/`) - Introduction to the collection
- **NFTs** (`/nfts.html`) - Focus on digital ownership and blockchain
- **Convoy of Hope** (`/convoy.html`) - Focus on humanitarian aid and hope
- **Words Museum** (`/words-museum.html`) - Original words.html with museum.lingscars.com styling
- **Ling's Cars** (`/lingscars.html`) - Tribute to the internet's most famous "terrible" website

## Local Development

1. Install Ruby and Jekyll:
   ```bash
   gem install jekyll bundler
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```

4. Visit `http://localhost:4000` in your browser.

## Deployment to GitHub Pages

1. Create a new repository on GitHub (e.g., `words-and-web-pages`)

2. Push this code to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

3. Go to your repository settings on GitHub

4. Scroll down to "GitHub Pages" section

5. Under "Source", select "Deploy from a branch"

6. Choose "main" branch and "/ (root)" folder

7. Click "Save"

8. Your site will be available at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

## Customization

- Edit `_config.yml` to change site settings
- Modify `_layouts/default.html` to change the overall layout
- Add new pages by creating HTML files with front matter
- Update the navigation in the default layout to include new pages

## Credits

Original concept by [Justin Jackson](https://justinjackson.ca/words.html)

## License

This project is open source and available under the [MIT License](LICENSE).
