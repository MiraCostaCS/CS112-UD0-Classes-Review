## 📋 Project Assessment: UD0 - Classes Review (Playing Cards)

### 1. Git & Workflow
- [ ] **Commit Messages:** Descriptive and incremental (e.g., "Implemented setAll and validated with tester").

### 2. Functional Requirements (Card Class & Tester)
- [ ] **Method Implementation (Passes Tester):**
    - [ ] `toString()`: Correctly displays Card (e.g., `A ♥`).
    - [ ] `setValue()` & `setSuit()`: Returns `boolean`; prevents invalid data.
    - [ ] `setAll()`: Updates both values and returns `boolean`.
    - [ ] **Constructors:** Default, Full, and **Copy Constructor** (must be a deep copy).
    - [ ] **Accessors:** `getSuit()`, `getValue()`, and `getPrintValue()` (A, J, Q, K logic).
    - [ ] `equals()`: Compares instance variables, not memory references.
- [ ] **Driver Program:**
    - [ ] Logic creates an array of 52 `Card` objects.
    - [ ] Correctly prints the full deck using a loop.

### 3. Code Quality & Standards
- [ ] **Documentation:** `Card` class is thoroughly documented (JavaDoc provided is still there).
- [ ] **Naming Conventions:** `camelCase` for methods/variables; `PascalCase` for classes.
- [ ] **OOP Standards:**
    - [ ] Instance variables are `private`.
    - [ ] Validation: Setters error check by returning a boolean, constructors do not allow "bad data" into the object (shutdown program)
- [ ] **Indentation:** Consistent formatting throughout.

### 4. Submit Final Project Idea (Canvas)
- [ ] Don't forget to submit your final project idea (2-3 sentences) on Canvas to start brainstorming what you will build by the end of the semester!

### 5. Hacker Challenge (Optional)
- [ ] **ASCII Art:** Successfully implemented `getPrintCard` logic to display visual cards.
