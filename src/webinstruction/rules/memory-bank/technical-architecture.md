# Technical Architecture & Structure

## Project Structure
```
/home/cskade/knowledge/Site/
├── .amazonq/rules/memory-bank/
└── School_2026Build/GS-KYMB-SITE-2026/
    └── src/
        ├── homepage/          # Main landing page
        ├── about/            # School information & history
        ├── academics/        # Academic programs & curriculum
        ├── admissions/       # Enrollment & application process
        ├── enrollment/       # Registration forms
        │   ├── Advanced/     # A-Level registration
        │   └── Ordinary/     # O-Level registration
        ├── sign-in_up/       # Authentication system
        │   ├── staff/        # Staff login/signup
        │   └── student/      # Student login/signup
        ├── staffPortal/      # Staff dashboard
        ├── studentlife/      # Extracurricular activities
        └── studentportal/    # Student dashboard
```

## Technology Stack
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Styling**: Custom CSS with responsive design
- **Icons**: Font Awesome 6.4.2
- **Images**: JPEG format for photos
- **Navigation**: Responsive hamburger menu

## Key Components
1. **Navigation System**: Consistent across all pages
2. **Responsive Design**: Mobile-first approach
3. **Form Systems**: Student/staff registration and enrollment
4. **Portal Systems**: Separate dashboards for students and staff
5. **Content Management**: Static HTML with dynamic JavaScript elements

## File Naming Conventions
- HTML files: lowercase with descriptive names
- CSS files: match corresponding HTML files
- Images: descriptive names (school.jpeg, school1.jpeg)
- Directories: camelCase or lowercase with hyphens