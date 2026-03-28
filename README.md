Preview Link: https://horvathmartin97.github.io/MayerfeldPracticum/

# MayerfeldPracticum

A multi-page static HTML website built as a practicum project. The site includes pages dedicated to favorite books, movies, hobbies, TV shows, and more.

## 📁 Project Structure
MayerfeldPracticum/
├── images/ # Image assets
├── pages/
│ ├── detailedHinikgPage.html
│ ├── detailedMbPage.html
│ ├── detailedVgPage.html
│ ├── favoriteBooks.html
│ ├── favouriteMovies.html
│ ├── geoStormPage.html
│ ├── HobbiesPage.html
│ ├── onePiecePage.html
│ ├── tedLassoPage.html
└── index.html # Home page


## 📄 Pages Overview

| Page | Description |
|------|-------------|
| `index.html` | Main home page / navigation hub |
| `favoriteBooks.html` | Table of favorite books with authors (Mark Manson, Steve Fenton, Robert Kirkman) |
| `favouriteMovies.html` | Favorite movies listing |
| `HobbiesPage.html` | Personal hobbies overview |
| `onePiecePage.html` | Dedicated page for One Piece |
| `tedLassoPage.html` | Dedicated page for Ted Lasso |
| `geoStormPage.html` | Dedicated page for GeoStorm |
| `detailedHinikgPage.html` | Detailed content page |
| `detailedMbPage.html` | Detailed content page |
| `detailedVgPage.html` | Detailed content page |

## 🛠️ Technologies Used

- HTML5
- No external frameworks — pure semantic HTML

## 🔗 Navigation

Each page includes a footer with a link back to the home page:
```html
<footer><a href="../index.html">Back To Home Page</a></footer>
```

## 🚀 Getting Started

1. Clone or download the repository
2. Open `index.html` in your browser
3. Navigate between pages using the provided links

## 📝 Notes

- The `favoriteBooks.html` page uses an HTML `<table>` to display book and author data
- All internal links use relative paths (`../index.html`)
