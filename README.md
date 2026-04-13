# Sky Larga — Beach Minimal Luxury Portfolio

## 📁 File Structure

```
portfolio/
├── index.html              ← Main portfolio page
├── admin/
│   └── index.html          ← Admin panel
├── data/
│   └── content.json        ← Default content source
├── assets/
│   └── images/             ← Place your images here
│       ├── bg.jpg           (hero background)
│       ├── profile.jpg      (your profile photo)
│       ├── about.jpg        (about section photo)
│       ├── gallery1.jpg
│       ├── gallery2.jpg
│       ├── gallery3.jpg
│       ├── gallery4.jpg
│       └── gallery5.jpg
└── README.md
```

## 🚀 Getting Started

1. Open `index.html` in your browser to view the portfolio
2. Open `admin/index.html` to edit content
3. Use the admin panel to upload photos and edit text
4. Click **Save Changes** — edits are stored in localStorage and reflect instantly
5. To make changes permanent, use **Export / Reset → Download content.json** and replace the file in `/data/`

## 🎨 Theme Colors

| Name        | Hex       |
|-------------|-----------|
| Sand        | `#F4EDE4` |
| Deep Ocean  | `#0A2540` |
| Sea Blue    | `#3A6EA5` |
| Light Sky   | `#A9C5D3` |
| Warm Accent | `#E6B17E` |
| Highlight   | `#FFD6A5` |

## ✏️ What You Can Edit in Admin

- **Hero**: Name, nickname, tagline, intro, profile photo, background image
- **About**: Headline, bio, about photo, floating info tags
- **Services**: Add/edit/remove any service with icon and description
- **Skills**: Add/remove tools and soft skills as pill tags
- **Gallery**: Upload or link 5 portfolio photos with captions
- **Contact**: Email, phone, location, CTA button text

## 📦 Deploying

Simply upload the entire `portfolio/` folder to any static hosting:
- **Netlify**: Drag & drop the folder
- **GitHub Pages**: Push to a repo and enable Pages
- **Vercel**: Import the folder as a project

> Note: Images uploaded via the admin panel are stored as base64 in localStorage. For production, host your images and use URLs instead.
