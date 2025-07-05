# Explore Miño 🌊🌲

A static website built with [Hugo](https://gohugo.io/) to showcase places of interest around **Miño**, a beautiful coastal town in Galicia, Spain. This site is intended to provide useful information to visitors and locals alike, with photos, maps, and curated recommendations.

The site uses the custom Hugo theme [**hugo-theme-walden**](https://github.com/venturarome/hugo-theme-walden) as a Git submodule.

---

## 🚀 Running the Site Locally

To run this Hugo site locally, follow these steps:

### 1. **Clone the Repository with Submodules**

```bash
git clone --recurse-submodules https://github.com/venturarome/explore-mino.git
cd explore-mino
```

If you forgot `--recurse-submodules`, run:
```bash
git submodule update --init --recursive
```

### 2. **Install Hugo**

Make sure [Hugo](https://gohugo.io/getting-started/installing/) is installed:
```bash
hugo version
```
You need the extended version if using SCSS or custom styling.

### 3. **Run the Development Server**
```bash
hugo server -D
```
Then open http://localhost:1313 in your browser to see the site.

