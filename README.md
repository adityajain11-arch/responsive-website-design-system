# Task 2: Responsive Website Design System & Layouts

## Overview
This repository contains the high-fidelity responsive website design and design system for **Task 2** of the CodeNova UI/UX Internship Program. The project includes a dedicated Design System, a 1440px Desktop Landing Page, and a 375px Mobile Landing Page adaptation.


---

## Project Previews

### 1. Design System (`00_Design_System`)
![Design System](assets/00_Design_System.png)

### 2. Desktop Landing Page - 1440px (`01_Desktop_1440`)
![Desktop Landing Page](assets/01_Desktop_1440.png)

### 3. Mobile Landing Page - 375px (`02_Mobile_375`)
![Mobile Landing Page](assets/02_Mobile_375.png)

---

## Grid & Layout Specifications

| Breakpoint | Type | Columns | Margin | Gutter | Spatial Grid |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Desktop (1440px)** | Column Grid | 12 | 80px | 24px | 8pt System |
| **Mobile (375px)** | Column Grid | 4 | 16px | 16px | 8pt System |

---

## Color Contrast Audit (WCAG AA Compliance)

| Color Role | Hex Code | Background | Contrast Ratio | WCAG AA Result |
| :--- | :--- | :--- | :--- | :--- |
| **Primary Dark Text** | `#111827` | `#FFFFFF` / `#F9FAFB` | **16.1:1** | Pass (AA / AAA) |
| **Primary Accent Text/Button** | `#2563EB` | `#FFFFFF` | **4.6:1** | Pass (AA) |
| **Button Text (Primary)** | `#FFFFFF` | `#2563EB` | **4.6:1** | Pass (AA) |
| **Muted Gray Text** | `#4B5563` | `#FFFFFF` / `#F9FAFB` | **7.1:1** | Pass (AA / AAA) |

---

## Typography Scale

* **Display / H1:** Inter / Bold / 36px (Line Height: 44px)
* **Heading 2:** Inter / Bold / 28px (Line Height: 36px)
* **Heading 3:** Inter / SemiBold / 20px (Line Height: 28px)
* **Body Text:** Inter / Regular / 16px (Line Height: 24px)
* **Caption:** Inter / Regular / 14px (Line Height: 20px)

---

## Key Features & Responsive Adaptations
1. **Component States:** Documented Default, Hover, Active, and Disabled states for interactive elements.
2. **Single-Column Adaptation:** Desktop hero layouts, 3-column feature grids, and footer items collapse logically into single-column vertical stacks on mobile.
3. **Accessible Touch Targets:** Mobile buttons stretch across screen widths with tap heights $\ge 48\text{px}$.
