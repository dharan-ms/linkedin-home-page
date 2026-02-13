# LinkedIn Topbar Component

A responsive, professional LinkedIn-style navigation bar built with React.js and functional components.

## Features

✅ **Modular Component Architecture**
- `Topbar.jsx` - Main navigation container
- `TopbarElement.jsx` - Reusable navigation item component
- `Profile.jsx` - User profile section

✅ **LinkedIn-Style Design**
- Sticky top navigation with shadow
- Flex layout with `justify-content: space-between`
- Professional color scheme and spacing
- Smooth hover effects and transitions

✅ **Fully Responsive**
- Desktop: Full navigation with icons and labels
- Tablet: Optimized spacing
- Mobile: Icon-only navigation for space efficiency

✅ **Modern Tech Stack**
- React 18 with functional components and hooks
- Vite for fast development
- Material-UI Icons for professional iconography
- Clean CSS with smooth animations

## Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

## Component Structure

```
src/
├── components/
│   ├── Topbar.jsx          # Main navigation container
│   ├── Topbar.css          # Topbar styles
│   ├── TopbarElement.jsx   # Reusable nav item
│   ├── TopbarElement.css   # Nav item styles
│   ├── Profile.jsx         # User profile section
│   └── Profile.css         # Profile styles
├── App.jsx                 # Main app component
├── App.css                 # Global styles
└── main.jsx               # React entry point
```

## Customization

### Change Navigation Items
Edit the `Topbar.jsx` file to add/remove navigation items:

```jsx
<TopbarElement Icon={YourIcon} title="Your Title" />
```

### Update Profile Avatar
Modify the `Profile.jsx` component to use your own avatar URL:

```jsx
<img src="your-avatar-url.jpg" alt="User Avatar" />
```

### Styling
All components have separate CSS files for easy customization:
- `Topbar.css` - Main navbar styling
- `TopbarElement.css` - Navigation item styling
- `Profile.css` - Profile section styling

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT
