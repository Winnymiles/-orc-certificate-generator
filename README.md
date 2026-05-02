# ORC Certificate Generator

Static HTML certificate generator for the Ottawa Robotics Competition.

## Publish

This project is ready to publish as a static site.

### Option 1: GitHub Pages

1. Create a new GitHub repository.
2. Push this folder to the repository.
3. In GitHub:
   - Open `Settings`
   - Open `Pages`
   - Under `Build and deployment`, choose `Deploy from a branch`
   - Select your default branch and `/ (root)`
4. GitHub will publish `index.html`, which redirects to the generator.

### Option 2: Netlify

1. Create a new site on Netlify.
2. Drag and drop this folder, or connect the Git repository.
3. Publish directory: leave as root.

### Option 3: Vercel

1. Import the repository into Vercel.
2. Framework preset: `Other`
3. Output directory: leave empty

## Main app file

- `outputs/orc_certificate_generator.html`

## Notes

- Uploaded logos are stored in the browser using `localStorage`.
- If different people use the public site, each person manages logos in their own browser.
