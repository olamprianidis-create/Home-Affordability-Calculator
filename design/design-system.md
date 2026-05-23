# Design System — Financial Tools

## Brand Identity
Futuristic, bold, edgy, and accessible. High contrast.
Dark base with electric accents. Feels like the future of finance.
Sharp, elegant edges — modern and confident, never bubbly or soft.

---

## Color Palette

### Backgrounds
- Primary Background:   #0D0D0D  (near-black — base for all tools)
- Secondary Background: #1A1A1A  (slightly lighter dark — for cards/sections)
- Surface / Card:       #222222  (elevated card backgrounds)

### Brand Accents
- Yellow (Primary CTA): #E8FF00  (electric yellow — buttons, highlights, results)
- Purple (Secondary):   #7B3FE4  (vibrant purple — cards, headers, badges)
- Green (Positive):     #39FF14  (neon green — positive results, gains)

### Text
- Primary Text:         #FFFFFF  (white — headings and body on dark bg)
- Secondary / Muted:    #E8E8E8  (light grey — labels, helper text)
- Dark Text:            #0D0D0D  (black — text placed on yellow or green bg)

### Semantic Colors
- Positive / Good:      #39FF14  (green — affordable, within budget)
- Warning:              #E8FF00  (yellow — borderline, caution)
- Negative / Bad:       #FF3B3B  (red — over budget, unaffordable)

---

## Typography

### Font
- Family: Montserrat (Google Fonts)
- Import: https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700;900&display=swap

### Scale
- Hero / Display:   900 weight, 3rem+    (large title text)
- Section Header:   700 weight, 1.75rem  (tool title, section names)
- Label / Input:    600 weight, 1rem     (input field labels)
- Body / Helper:    400 weight, 0.95rem  (descriptions, helper text)
- Result Output:    700 weight, 2rem+    (calculated result numbers)

### Text on Color Rules
- On #0D0D0D background — use #FFFFFF or #E8FF00
- On #7B3FE4 purple      — use #E8FF00 or #FFFFFF
- On #E8FF00 yellow      — use #0D0D0D (always dark text)
- On #39FF14 green       — use #0D0D0D (always dark text)

---

## Border Radius
- Cards / Containers:   border-radius: 12px
- Buttons:              border-radius: 8px   (sharp, elegant — NOT pill-shaped)
- Input Fields:         border-radius: 8px
- Badges / Tags:        border-radius: 6px
- Result Boxes:         border-radius: 10px

---

## Spacing
- Page max-width:       800px, centered
- Section padding:      40px 32px
- Card padding:         28px
- Input gap:            16px
- Between sections:     48px

---

## Components

### Buttons (Primary CTA)
- Background:     #E8FF00
- Text:           #0D0D0D, 700 weight, uppercase
- Border-radius:  8px  (sharp elegant edge — NOT pill)
- Padding:        14px 40px
- Display:        inline-block  (never full width — content-sized + padding)
- No border
- NOT full width on mobile — generous horizontal padding creates breathing room

### Input Fields
- Background:     #1A1A1A
- Border:         1px solid #333333
- Focus border:   1px solid #7B3FE4
- Text:           #FFFFFF
- Label:          #E8E8E8, 600 weight
- Border-radius:  8px
- Padding:        14px 16px

### Result / Output Box
- Background:     #7B3FE4 (purple) OR #E8FF00 (yellow for standout results)
- Text:           #FFFFFF on purple / #0D0D0D on yellow
- Font:           700 weight, 1.75–2.5rem for the key number
- Border-radius:  10px
- Padding:        24px

### Cards
- Background:     #222222
- Border:         1px solid #333333
- Border-radius:  12px
- Padding:        28px
- Box-shadow:     0 4px 24px rgba(0, 0, 0, 0.4)

### Section Dividers
- Use a 1px solid #2A2A2A horizontal rule after every section header
- 8px spacing between the header and the rule
- 12px spacing between the rule and the content below
- 40px spacing above each new section
- HTML pattern:
  <h2>Section Title</h2>
  <hr style="border:none; border-top:1px solid #2A2A2A; margin:8px 0 12px 0;">
  [content]

---

## Mobile-First Rules
- Design for mobile viewport first, scale up for desktop
- All layouts single column on small screens
- Buttons: inline-block with padding — never stretch full width on mobile
- Input fields: full width on mobile is fine
- Cards: full width on mobile, max 800px centered on desktop
- Font sizes scale down slightly on mobile (use rem units)
- Touch targets minimum 44px height for all interactive elements

---

## Aesthetic Rules
- Always dark background — never white or light grey base
- Electric yellow is reserved for the ONE most important action per page
- Purple signals interactivity and brand identity
- Green signals a positive financial outcome
- Red signals a negative or over-budget result
- Sharp 8px radius on buttons — elegant and confident, never bubbly
- Typography is bold and large — numbers should feel powerful
- Less is more — no clutter, no decoration for decoration's sake
- Section dividers use both a visible line AND spacing for clear hierarchy
