# 🚐 VanLife - React Router Project

This is a **React SPA (Single Page Application)** I built as part of my learning journey on the Scrimba Frontend Developer Career Path. The project simulates a van rental platform called **VanLife**. It was designed to help me strengthen my understanding of **React Router v6**, component structure, and working with dynamic routes and layouts.

This was one of the largest React projects I've built so far, and it really helped me grow my confidence in building modern frontend applications using React.

---

## 📚 What I Learned

During this project, I gained hands-on experience with:

- **React Router v6**: route nesting, dynamic segments, layout routes, and route-based code organization
- Creating shared layouts using `<Outlet />`
- Building user interfaces from real route data
- Organizing React projects into modular components and pages
- Handling dynamic content with `useParams()` and URL-based rendering
- Implementing route protection in a **simulated** way (using simple conditional logic)
- Using **Mirage JS** to simulate backend data (basic usage only)

Even though I didn’t dive deep into backend or full-stack concepts, I focused completely on mastering **frontend development skills**.

---

## 🧭 App Overview

| Path                     | Purpose                                                  |
|--------------------------|-----------------------------------------------------------|
| `/`                      | Homepage with call to action                              |
| `/about`                 | Learn about VanLife and its benefits                      |
| `/vans`                  | Lists all available vans for rent                         |
| `/vans/:id`              | Shows detailed information about a specific van           |
| `/login`                 | Fake login screen (simulates login using static credentials) |
| `/host`                  | Host dashboard (protected area, using basic route logic)  |
| `/host/income`           | Displays host income overview                             |
| `/host/reviews`          | Shows reviews from customers                              |
| `/host/vans`             | Host’s listed vans                                        |
| `/host/vans/:id`         | Management dashboard for individual hosted van            |
| `/host/vans/:id/info`    | Van info tab                                              |
| `/host/vans/:id/pricing` | Van pricing tab                                           |
| `/host/vans/:id/photos`  | Van photos tab                                            |
| `*`                      | Fallback Not Found page                                   |

---

## 🔐 Fake Authentication

This project includes **simulated route protection**, which restricts access to the `/host` section unless the user "logs in."

> ⚠️ Note: This is **not real authentication**. No tokens, sessions, or validation involved.

You simply enter:
- **Email**: `b@b.com`
- **Password**: `p123`

Once submitted, it stores a flag in `localStorage` to simulate a login session. This was done purely to practice how protected routes work in frontend routing—not actual auth logic.

---

## 🛠️ Tech Stack

- **React** (JSX, functional components, hooks)
- **React Router v6** (dynamic client-side routing)
- **JavaScript (ES6+)**
- **Vite** (for fast development server and builds)
- **Mirage JS** (to simulate API responses—basic usage only)
- **Plain CSS** (for layout and styling)

---


## 💾 Mirage JS Usage

While this project included **Mirage JS**, I used it only at a basic level to simulate a backend API. It provided dummy data for vans and host vans, but I didn't focus on advanced mocking, relationships, or request handling.

```js
GET /api/vans
GET /api/host/vans
GET /api/vans/:id

```
## 🏁 Final Thoughts

This project gave me real-world experience in building a **fully routed, component-based frontend React application**.  
It helped me become comfortable with **nested routing**, **shared layouts**, and **organizing code in a scalable way**.

Thanks to **Scrimba**, I was able to learn by building—not just watching.  
It was an enjoyable and rewarding experience that strengthened my frontend skills and prepared me for more complex applications ahead.

---

