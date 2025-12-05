### 1. Layout & Grid System
The core foundation of any Bootstrap project.

| Utility | Class Syntax | Description |
| :--- | :--- | :--- |
| **Container** | `.container` | Fixed-width container that scales with breakpoints. |
| | `.container-fluid` | Full-width container (100% viewport width). |
| **Rows** | `.row` | Wrapper for columns; creates a horizontal group. |
| | `.g-{0-5}` | Sets gutter (gap) between columns (e.g., `.g-3`). |
| **Columns** | `.col` | Auto-layout column (equal width). |
| | `.col-{1-12}` | Span specific number of grid columns (e.g., `.col-6` is 50%). |
| | `.col-{bp}-{1-12}` | Responsive column spans (e.g., `.col-md-4`). |

**Grid Breakpoints:**
| Breakpoint | Infix | Dimensions |
| :--- | :--- | :--- |
| Extra Small | `None` | <576px |
| Small | `sm` | ≥576px |
| Medium | `md` | ≥768px |
| Large | `lg` | ≥992px |
| Extra Large | `xl` | ≥1200px |
| XXL | `xxl` | ≥1400px |

---

### 2. Spacing Utilities
Bootstrap 5 uses the format `{property}{sides}-{size}` (e.g., `mt-3`, `px-2`).

| Property | Sides | Size Scale |
| :--- | :--- | :--- |
| `m` (Margin) | `t` (Top), `b` (Bottom) | `0` (0) |
| `p` (Padding) | `s` (Start/Left), `e` (End/Right) | `1` (.25rem) |
| | `x` (Left & Right), `y` (Top & Bottom) | `2` (.5rem) |
| | `(blank)` (All 4 sides) | `3` (1rem) |
| | | `4` (1.5rem) |
| | | `5` (3rem) |
| | | `auto` (Auto margin) |

---

### 3. Display & Flexbox
Control layout behavior and element visibility.

| Category | Classes | Description |
| :--- | :--- | :--- |
| **Display** | `.d-none`, `.d-block`, `.d-inline` | Toggle visibility. |
| | `.d-{bp}-none`, `.d-{bp}-block` | Responsive visibility (e.g., `.d-md-none`). |
| **Flex Parent** | `.d-flex`, `.d-inline-flex` | Enables flexbox behaviors. |
| **Direction** | `.flex-row`, `.flex-column` | Sets horizontal or vertical direction. |
| **Justify** | `.justify-content-start` | Align items horizontally (start, center, end, between, around). |
| | `.justify-content-center` | |
| **Align** | `.align-items-center` | Align items vertically (start, center, end, stretch). |
| **Grow/Fill** | `.flex-grow-1` | Forces item to fill remaining space. |

---

### 4. Colors (Theme)
Applied as prefixes to text, backgrounds, and buttons.

| Theme Color | Text Class | Background Class | Button Class |
| :--- | :--- | :--- | :--- |
| **Primary** (Blue) | `.text-primary` | `.bg-primary` | `.btn-primary` |
| **Secondary** (Gray) | `.text-secondary` | `.bg-secondary` | `.btn-secondary` |
| **Success** (Green) | `.text-success` | `.bg-success` | `.btn-success` |
| **Danger** (Red) | `.text-danger` | `.bg-danger` | `.btn-danger` |
| **Warning** (Yellow) | `.text-warning` | `.bg-warning` | `.btn-warning` |
| **Info** (Cyan) | `.text-info` | `.bg-info` | `.btn-info` |
| **Light** (Lt Gray) | `.text-light` | `.bg-light` | `.btn-light` |
| **Dark** (Black) | `.text-dark` | `.bg-dark` | `.btn-dark` |

---

### 5. Typography & Text
Necessary for formatting text content.

* **Headings:** `.h1` through `.h6` (match HTML heading styles).
* **Display:** `.display-1` through `.display-6` (larger, more opinionated headings).
* **Alignment:** `.text-start`, `.text-center`, `.text-end`.
* **Transform:** `.text-uppercase`, `.text-lowercase`, `.text-capitalize`.
* **Weight/Style:** `.fw-bold`, `.fw-light`, `.fst-italic`.
* **Wrappers:** `.text-truncate` (ellipses for overflow), `.text-break` (prevent overflow).

---

### 6. Essential Components
The most frequently used UI elements.

#### **Buttons**
* `.btn`: Base class (required).
* `.btn-{color}`: Solid color (e.g., `.btn-primary`).
* `.btn-outline-{color}`: Outline style (e.g., `.btn-outline-danger`).
* `.btn-sm`, `.btn-lg`: Sizing.

#### **Cards**
* `.card`: Wrapper.
* `.card-body`: Main content container.
* `.card-title`, `.card-text`: Typography specifically for cards.
* `.card-img-top`: Image class for top-aligned images.

#### **Forms**
* `.form-control`: Standard input styling (text, password, email).
* `.form-select`: Styling for `<select>` dropdowns.
* `.form-check`: Wrapper for checkboxes/radios.
* `.form-label`: Styling for `<label>` elements.
* `.input-group`: Grouping inputs with buttons or text addons.

#### **Navbar**
* `.navbar`: Wrapper.
* `.navbar-expand-{bp}`: When to collapse the menu (e.g., `.navbar-expand-lg`).
* `.navbar-light`, `.bg-light`: Color scheme.
* `.container-fluid`: Usually wraps content inside navbar.
* `.navbar-brand`: Logo/Title styling.

---

### 7. General Utilities
Helper classes for quick styling adjustments.

| Category | Classes | Use Case |
| :--- | :--- | :--- |
| **Sizing** | `.w-25`, `.w-50`, `.w-75`, `.w-100` | Width percentage. |
| | `.h-100`, `.vh-100` | Height percentage / Viewport height. |
| **Borders** | `.border`, `.border-0`, `.border-top` | Add or remove borders. |
| | `.rounded`, `.rounded-circle`, `.rounded-pill` | Border radius. |
| **Position** | `.position-relative`, `.position-absolute` | CSS positioning. |
| | `.fixed-top`, `.fixed-bottom` | Fix element to viewport. |
| **Shadows** | `.shadow-sm`, `.shadow`, `.shadow-lg` | Box shadows. |

Detailed visual walkthrough of these classes: [Bootstrap 5 Crash Course](https://www.youtube.com/watch?v=Jyvffr3aCp0)
This video is relevant as it provides a visual breakdown of the grid system, components, and utility classes listed above, reinforcing the practical application of these codes.


http://googleusercontent.com/youtube_content/0
