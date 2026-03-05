# ZenFocus To-Do App

A minimalist to-do list application built with vanilla JavaScript.

Day 2 - Core CSS Styling & Color System
📅 Date: Day 2
Focus: Beautiful design with CSS custom properties

🎯 Today's Goals

 Create styles.css file
 Define color system with CSS variables
 Style header and typography
 Style input card with flexbox
 Add hover effects and transitions
 Make second Git commit


📝 What We're Building Today
Today we transform our plain HTML into a beautiful, zen-inspired design. We'll use CSS custom properties (variables) to create a cohesive color system that's easy to customize.
Why CSS Variables?

Easy to maintain (change color once, updates everywhere)
Professional approach
Simple theme switching later
Industry standard


🎨 Our Color Palette
css--bg: #f8f6f2       /* Warm beige background */
--card: #ffffff     /* White cards */
--text: #2c2416     /* Dark brown text */
--muted: #8a8171    /* Muted secondary text */
--accent: #d48c5c   /* Terracotta accent */
--green: #5b8c6a    /* Sage green for success */
--border: #e8e2d6   /* Subtle borders */
Design Philosophy: Warm, earthy tones that promote calm and focus.

📋 Step-by-Step Instructions
Step 1: Create styles.css
Create a new file called styles.css in your project root.
Step 2: Add CSS Variables
Start with the :root selector to define your colors:
css:root {
  --bg: #f8f6f2;
  --card: #ffffff;
  /* ... more variables */
}
Step 3: Add Base Styles

Reset margins and padding
Set box-sizing to border-box
Define body font and background

Step 4: Style the Header

Use DM Serif Display for h1
Large font size (3rem)
Negative letter spacing for modern look
Muted color for subtitle

Step 5: Style Input Card

White background with border
Flexbox layout with gap
Rounded corners (border-radius: 16px)
Subtle shadow for depth

Step 6: Style Inputs and Button

Inputs with focus states
Button hover effects
Smooth transitions (0.2s)

Step 7: Link CSS to HTML
Update your index.html:
🎨 What You'll See
Refresh your browser. You should see:

Warm beige background - Calming and professional
Centered container - Max 550px wide
Beautiful typography - Serif heading, sans body
Styled input card - White, rounded, with shadow
Hover effects - Button changes color on hover
Proper spacing - Everything breathes


✅ Testing Checklist

 Background is warm beige (not white)
 Container is centered on page
 Heading uses serif font
 Input card has rounded corners
 Button changes color on hover
 Everything is properly spaced
 Fonts match Google Fonts (not default)
 Focus states work on inputs


🐛 Troubleshooting
Problem: No styling appears
Solution:

Check CSS file is named exactly styles.css
Verify <link> tag in HTML is correct
Open browser console (F12) for errors

Problem: Colors don't look right
Solution:

Check hex codes are correct (including #)
Make sure you're using var(--bg) not just --bg

Problem: Fonts still look default
Solution:

Clear browser cache (Ctrl/Cmd + Shift + R)
Check Google Fonts link in HTML

Problem: Layout looks broken
Solution:

Check for typos in CSS property names
Make sure all brackets {} are closed
Validate CSS at jigsaw.w3.org/css-validator


📚 What You Learned Today
CSS Concepts:

✅ CSS Custom Properties (variables)
✅ :root selector
✅ Flexbox (display: flex, gap)
✅ Box model (padding, margin, border)
✅ Pseudo-classes (:hover, :focus)
✅ Transitions
✅ Border-radius
✅ Box-shadow

Design Concepts:

✅ Color palette design
✅ Typography hierarchy
✅ Whitespace importance
✅ Card-based UI
✅ Visual feedback (hover states)
✅ Accessibility (focus states)

Best Practices:

✅ CSS variables for maintainability
✅ Mobile-first approach (max-width)
✅ Semantic class names
✅ Smooth transitions
✅ Consistent spacing


🎓 Key Takeaways
1. CSS Variables Are Powerful
Change one variable, update entire theme. Much better than find/replace!
2. Design System First
Defining colors upfront creates consistency automatically.
3. Flexbox Simplifies Layouts
Old way: floats and clearfix. New way: display: flex; gap: 8px; Done!
4. Transitions Add Polish
A simple 0.2s transition makes interactions feel smooth and professional.

🚀 What's Next? (Day 3)
Tomorrow we'll:

Create script.js
Write our first JavaScript function
Display sample tasks dynamically
Learn DOM manipulation

Preview: By end of Day 3, you'll see tasks appear on the page!

💡 Pro Tips

Use Browser DevTools: Right-click → Inspect to see CSS live
Experiment: Change colors and see what looks good
Mobile Test: Resize browser to see responsive design
Comment Your CSS: Add /* Section Name */ for organization


📊 Progress Tracker
Day 2: ████████████████░░░░░░░░░░░░░░░░ 17%

✅ HTML Structure
✅ CSS Styling
⬜ JavaScript Rendering
⬜ Add Tasks
⬜ Toggle Complete
⬜ Delete Tasks
⬜ LocalStorage
⬜ Progress Bar
⬜ Clear Completed
⬜ Polish & Animations

🎨 Design Inspiration
Your color palette is inspired by:

Zen gardens (earthy, natural)
Minimalist Japanese design
Modern productivity apps
Warm, calming workspaces


🎉 Congratulations!
You've completed Day 2! You now have:

A beautiful color system
Professional typography
Responsive layout
Smooth interactions
A design you can be proud of!

Your app already looks better than many production apps! 🌟html<link rel="stylesheet" href="styles.css">
