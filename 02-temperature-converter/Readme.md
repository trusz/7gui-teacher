# Temperature Converter

**Challenges:** Bidirectional data flow, user text validation.

![Temperature Converter task screenshot](../assets/temperature-converter.png)


Build a UI with two text inputs:
- `TC` (Celsius)
- `TF` (Fahrenheit)

Behavior:
- both start empty
- typing a valid number in `TC` updates `TF`
- typing a valid number in `TF` updates `TC`
- invalid input in one field does **not** update the other

Formulas:
- `F = C * (9/5) + 32`
- `C = (F - 32) * (5/9)`

Focus on clarity of two-way updates without loops.
