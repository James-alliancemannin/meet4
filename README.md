# meet4

Casual local hangouts — real people, zero pressure.

**meet4** is a simple platform for discovering and creating low-key, in-person meetups in your neighborhood: walks, coffee runs, board games, park workouts, quiet reading spots, and more. No endless scrolling, no hookup focus — just small groups showing up and connecting.

## Current Status (February 2026)

- **Landing page**: Live static site with splash animation  
  Preview: https://yourusername.github.io/meet4/landing/  
  (Custom domain meet4.com coming soon)

- **Mobile apps**: Planned (iOS + Android) — not started yet  
- **Backend**: Planned (Supabase for auth, events, location queries)

## Folder Structure

meet4/
├── landing/                    # Static landing page (current live version)
│   ├── index.html              # Main page with video splash + content
│   ├── logo.jpg                # Logo with white background
│   └── meet4.mp4               # Animated logo intro video
├── README.md                   # This file
└── .gitignore                  # Standard ignores

Future planned folders (empty for now):
- `/mobile` — React Native / Expo app
- `/backend` — Supabase config, migrations, edge functions
- `/docs` — Wireframes, user stories, API notes

## Live Site

- GitHub Pages preview: https://yourusername.github.io/meet4/landing/  
  (Replace `yourusername` with your actual GitHub username)

- Planned production URL: https://meet4.com

## Tech Stack (current + planned)

**Current (landing page)**
- HTML + Tailwind CSS (via CDN)
- Vanilla JavaScript (splash video controls)
- No build tools yet (simple static site)

**Planned**
- Frontend: React / Next.js (for dynamic features)
- Backend: Supabase (PostgreSQL + PostGIS for location, Auth, Realtime)
- Maps: Leaflet.js or MapLibre (free & open-source)
- Mobile: React Native + Expo (cross-platform iOS/Android)
- Deployment: Vercel or Netlify (for landing) + GitHub Pages (preview)

## Next Steps / Roadmap

1. Deploy landing page to GitHub Pages and connect custom domain meet4.com
2. Add email waitlist / sign-up form to collect early interest
3. Set up Supabase project (auth + profiles + events + location tables)
4. Build basic map view showing nearby events (using browser geolocation + PostGIS)
5. Prototype mobile app (React Native / Expo)
6. Add real-time group features (optional, using Supabase Realtime)

## Contributing

This is currently a duo personal project.  
If you're interested in collaborating (design, code, testing), feel free to open an issue or reach out

## License

MIT License (see [LICENSE](LICENSE) i

---
Built with ❤️ for real connections.
