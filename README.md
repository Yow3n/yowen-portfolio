Yowen Naidoo — Public Portfolio Website
A static, deploy-ready portfolio website created from the supplied professional portfolio HTML.
Included
index.html — main public portfolio site
assets/ — local asset folder for portfolio/gallery images
README.md — deployment notes
Important: image assets
The supplied HTML references these image filenames:
1001843003.jpg
1001659325.jpg
1001659326.jpg
1001659328.jpg
1001659329.jpg
1001659331.jpg
1001839900.jpg
1001839899.jpg
1001659346.jpg
1001389667.jpg
1001668261.jpg
Those image files were not included with the uploaded HTML, so the package does not invent or substitute personal photographs. Add the original files to assets/ and update the image paths in index.html to assets/<filename> before deployment.
Deploy
Vercel
Create a new Vercel project.
Upload the contents of this folder, with index.html at the project root.
Deploy as a static site.
Optional: connect a custom domain.
Netlify
Drag the yowen-portfolio folder into Netlify's deploy area, or connect it to a Git repository.
GitHub Pages
Create a repository, upload the package contents, then enable GitHub Pages from the repository settings.
Existing public URL
The supplied HTML already points to: https://yowen-naidoo.vercel.app/
If that is the intended existing Vercel project, deploy this index.html and the image assets to that project rather than creating a second site.
