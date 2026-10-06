# Zulti Live Draw Calculator

A web-based expected value (EV) calculator for the **Zulti Live Draw** game. 

This tool calculates the optimal number choice (1–50) that maximizes your expected gem returns based on remaining undrawn numbers and non-stacking reward rules.

Live site: [https://cytsunny.github.io/zulti-calculator/](https://cytsunny.github.io/zulti-calculator/)

---

## 🎲 Game Rules & Gem Rewards

- **Grid Layout**: 5 columns wide $\times$ 10 rows high (Numbers 1 to 50).
- **Draw Mechanism**: 1 number is drawn at a time without replacement.
- **Winning Conditions & Priority**:
  1. **Exact Match**: 50 gems *(Highest priority)*
  2. **Same Row**: 20 gems
  3. **Same Column**: 10 gems
  4. **Same Odd/Even**: 5 gems

> **Note**: Conditions do **not** stack. If a draw satisfies multiple conditions with your chosen number, only the highest single reward is awarded.

---

## 🧠 Calculator Features

- **Optimal Recommendation**: Automatically computes the Expected Value (EV) in gems for every undrawn number and recommends the highest EV choice.
- **Tie-Breaking**: If multiple numbers yield the exact same expected gems, the calculator defaults to the smallest number.
- **Interactive Tracking**:
  - Enter drawn numbers using the input form, or
  - Click any cell in the 5x10 table to toggle its drawn state.
  - Reset button to quickly start a new round.

---

## 🛠️ Local Setup

Simply open `index.html` in any modern web browser or serve it using any local HTTP server:

```bash
# Example using Python
python3 -m http.server 8000
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
