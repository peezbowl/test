NEOMATH.IN V2

FOLDERS
class8/ = all Class 8 content
class9/ = all Class 9 content
class10/ = all Class 10 content
blogs/ = blog home and all blog articles
templates/ = reusable chapter and blog templates

EASIEST UPDATES
1. YouTube videos: edit data.js. Add a copied video line. youtube.html updates automatically.
2. E-books: edit data.js. Add a copied ebook line.
3. New chapter: copy templates/chapter-template.html into the correct class folder, rename it, edit it, then add one link/card to that class index.html.
4. New blog: copy templates/blog-template.html into blogs/, rename it, edit it, then add one link/card to blogs/index.html.

No database, Node, React, npm or server is needed. This is a simple static GitHub Pages site.

GITHUB PAGES
Create a repository, upload all files, then Settings > Pages > Deploy from a branch > main > root > Save.
