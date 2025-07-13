🌟 Temperature Converter (Java Swing) 🌟

This is a GUI-based Temperature Converter application developed in **Java** using **Swing**. It allows users to convert temperature values between **Celsius**, **Fahrenheit**, and **Kelvin**. The interface includes a virtual number pad, mode selectors, and utility buttons for better usability.

♦️ Features

- Convert temperature between:
  - Celsius ↔ Fahrenheit
  - Celsius ↔ Kelvin
  - Fahrenheit ↔ Kelvin
- Intuitive **number pad** input using buttons (0–9, dot, ±).
- Utility controls:
  - `AC` (All Clear)
  - `±` (Toggle sign)
  - `<--` (Backspace)
- Dropdowns to select **From** and **To** units.
- Results are displayed instantly on clicking **Convert**.



♦️Conversion Formulas Used

| From        | To           | Formula                                      |
|-------------|--------------|----------------------------------------------|
| Celsius     | Fahrenheit   | (°C × 9/5) + 32                               |
| Celsius     | Kelvin       | °C + 273.15                                  |
| Fahrenheit  | Celsius      | (°F − 32) × 5/9                              |
| Fahrenheit  | Kelvin       | ((°F − 32) × 5/9) + 273.15                    |
| Kelvin      | Celsius      | K − 273.15                                   |
| Kelvin      | Fahrenheit   | ((K − 273.15) × 9/5) + 32                     |



♦️Tech Stack

- **Java** (JDK 8+)
- **Swing** for GUI
- **Event-driven programming** (ActionListeners)
