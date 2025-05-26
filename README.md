# Personal Dashboard Web App

A modern, responsive personal dashboard built with Next.js and Tailwind CSS. This professional portfolio showcases academic background, work experience, technical skills, and personal goals in a clean, interactive interface.

## 🚀 Live Demo

* **Live URL**: [Your Netlify URL here]
* **GitHub Repository**: [Your GitHub repository URL here]

## ✨ Features

* **Responsive Design**: Mobile-first approach that works perfectly on all devices
* **Modern UI/UX**: Clean, professional design with smooth animations and interactions
* **Performance Optimized**: Built with Next.js for optimal loading speeds
* **Accessibility**: Proper semantic HTML and ARIA labels
* **Interactive Navigation**: Smooth scrolling with active section highlighting
* **Professional Sections**:
   * Profile with contact information
   * Professional experience timeline
   * Education background
   * Technical skills organized by category
   * Featured projects with technology stacks
   * Professional goals
   * Hobbies and interests

## 🛠️ Tech Stack

* **Framework**: Next.js 14
* **Styling**: Tailwind CSS
* **Icons**: Heroicons & Lucide React
* **Deployment**: Netlify
* **Language**: JavaScript (ES6+)

## 📁 Project Structure

```
personal-dashboard/
├── public/
│   └── resume.pdf
├── src/
│   ├── app/
│   │   ├── globals.css
│   │   ├── layout.js
│   │   └── page.js
│   ├── components/
│   │   ├── Dashboard.js
│   │   ├── Navigation.js
│   │   ├── ProfileSection.js
│   │   ├── AcademicsSection.js
│   │   ├── SkillsSection.js
│   │   └── GoalsSection.js
│   └── data/
│       └── profileData.js
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── next.config.js
└── README.md
```

## 🚀 Getting Started

### Prerequisites

* Node.js 18.x or later
* npm or yarn package manager

### Installation

1. **Clone the repository**

```bash
git clone [your-repository-url]
cd personal-dashboard
```

2. **Install dependencies**

```bash
npm install
```

3. **Start the development server**

```bash
npm run dev
```

4. **Open your browser**
   Navigate to `http://localhost:3000`

### Building for Production

```bash
npm run build
npm start
```

## 🧩 Components

Each section is modularized into separate components:

* `ProfileSection.js` - Personal information and contact details
* `AcademicsSection.js` - Education and work experience
* `SkillsSection.js` - Technical skills and projects
* `GoalsSection.js` - Goals and hobbies
* `Navigation.js` - Responsive navigation with smooth scrolling

## 📱 Responsive Design

The dashboard is fully responsive with breakpoints for:

* **Mobile**: < 768px
* **Tablet**: 768px - 1024px
* **Desktop**: > 1024px

## 🚀 Deployment

### Deploy to Netlify

1. **Build the project**

```bash
npm run build
```

2. **Deploy via Netlify CLI**

```bash
npm install -g netlify-cli
netlify deploy --prod --dir=out
```

3. **Or deploy via Netlify Dashboard**
   * Connect your GitHub repository
   * Set build command: `npm run build`
   * Set publish directory: `out`

## 🎨 Customization

### Updating Personal Information

Edit the `src/data/profileData.js` file to update:
* Personal details
* Education history
* Work experience
* Skills and technologies
* Projects
* Goals and achievements

### Styling

* Global styles: `src/app/globals.css`
* Tailwind configuration: `tailwind.config.js`
* Custom components and utilities are defined in the CSS file

### Adding New Sections

1. Create a new component in `src/components/`
2. Import and add it to `Dashboard.js`
3. Update the navigation in `Navigation.js`
4. Add corresponding data to `profileData.js`

## 📬 Contact

**Shaik Nida Afsheen**

* 📧 Email: nidaafsheenshaik@gmail.com
* 📱 Phone: +91 9296109205
* 💼 LinkedIn: https://www.linkedin.com/in/nida-afsheen-shaik/
* 🐙 GitHub: https://github.com/afsheen1604/
* 🌐 Website: https://afsheen1604.github.io/my-portfolio/

## 🏆 Achievements

* Semi-finalist in Google Girl Hackathon 2023 (Top 2.5% of 26,000+ applicants)
* Solved 1000+ coding problems across Leetcode, Codechef, Codeforces
* Secured AIR 6777 in GATE 2025

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues).

## ⭐ Show Your Support

Give a ⭐️ if this project helped you!

---

Built with ❤️ using Next.js and Tailwind CSS#
