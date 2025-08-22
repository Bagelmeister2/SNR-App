# SNR-App
Plots the Signal-to-Noise Ratio (SNR) margin relative to receiver sensitivity as a function of distance, using the  Free-Space Path Loss (FSPL) model.

Features:
- User input fields for transmit power, antenna gains, cable losses, frequency, 
  receiver sensitivity, and user-defined distance.
- Computes Equivalent Isotropically Radiated Power (EIRP) and closed-form 
  distance where SNR margin = 20 dB.
- Displays SNR margin curve with guides for:
    • 0 dB margin (minimum link closure)
    • 20 dB margin (typical design threshold)
    • User-specified distance
- Interactive draggable marker to inspect SNR margin values anywhere along the curve.
- Dual x-axis: distance in nautical miles (bottom) and kilometers (top).
- Parameter summary box with link budget details.

Intended Use:
This tool provides a quick way to visualize link budget margins over distance 
for RF communication systems. It is useful for engineers performing preliminary 
link analysis, system design studies, or educational demonstrations of FSPL effects.
