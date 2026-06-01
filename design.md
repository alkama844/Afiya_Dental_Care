# Afiya Dental Care - Design System

## Color Palette
- **Primary Blue**: #1a73e8
- **Secondary Purple**: #6c5ce7
- **Dark Text**: #2c3e50
- **Light Gray**: #666
- **Light Background**: #fff4e6
- **Border Gray**: #eee
- **Warning Orange**: #ffa94d
- **Error Red**: #ff6b6b

## Typography
- **Headings Font**: Poppins (for English), SolaimanLipi (for Bengali)
- **Body Font**: Open Sans, Roboto
- **Main Title Size**: 2.5rem
- **Subtitle Size**: 1.2rem
- **Body Text**: 1rem, 1.1rem
- **Font Weight**: 500-900

## Component Styles

### Service Cards
- Border Radius: 16px
- Box Shadow: 0 10px 30px rgba(0, 0, 0, 0.08)
- Hover: translateY(-8px), shadow 0 15px 35px rgba(0, 0, 0, 0.15)
- Top Border: 5px gradient (blue to purple)
- Max Width: 300px-1fr grid

### Buttons
- Border Radius: 50px (fully rounded)
- Padding: 10px 20px
- Font Weight: 600
- Gradient: linear-gradient(90deg, #1a73e8, #6c5ce7)
- Hover: translateY(-2px), shadow 0 5px 15px rgba(26, 115, 232, 0.3)

### Badges
- Background: #1a73e8
- Border Radius: 50px
- Padding: 8px 20px
- Font Size: 0.9rem

### Spacing
- Container Max Width: 1300px
- Container Padding: 60px 20px
- Grid Gap: 30px
- Margin Bottom (sections): 50px, 40px, 15px

### Animations
- Transition: all 0.3s ease
- Image Hover: transform scale(1.05) 0.5s
- Default opacity: 0, transform: translateY(20px)
- Visible: opacity 1, transform: translateY(0)

## Grid System
- Auto-fit columns: minmax(300px, 1fr)
- Responsive breakpoint: max-width 1024px
- Mobile columns: minmax(280px, 1fr)

## Image Handling
- Height: 220px
- Object-fit: cover
- Transition on hover: scale(1.05) 0.5s ease

## Border Styles
- Card borders: none
- Dividers: 1px solid #eee
- Top accent: 5px solid gradient
- Note borders: 3px solid left #ffa94d

## Special Effects
- Underline accent on titles (::after pseudo-element)
- Width: 80px
- Height: 4px
- Gradient: 90deg from primary to secondary
- Border Radius: 2px
