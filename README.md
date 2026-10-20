# Dessert RecycleView App 🍩🍦

An Android application built with Kotlin and Jetpack Components to demonstrate the implementation of `RecyclerView` using custom list items (`DessertAdapter`), data models (`Dessert`), and modern Material design styling.

## Features
- **RecyclerView**: Efficiently displays a vertical list of dessert items.
- **Custom Adapter**: `DessertAdapter` with dynamic background circle coloring (`GradientDrawable`).
- **Data Model**: Structured `Dessert` data class holding description, image resources, and color HEX values.
- **Edge-to-Edge Support**: Modern edge-to-edge UI layout handling system bar insets.

## Tech Stack
- Language: **Kotlin**
- UI: **XML Layouts**, **RecyclerView**, **LinearLayout**
- Framework / Android Jetpack: `AppCompatActivity`, `ViewCompat`, `WindowInsetsCompat`, `RecyclerView`

## Project Structure
- `lat.pam.dessertrecycleview.Dessert`: Data class representing a dessert item.
- `lat.pam.dessertrecycleview.DessertAdapter`: RecyclerView Adapter binding dessert data to view holders.
- `lat.pam.dessertrecycleview.MainActivity`: Main screen hosting the RecyclerView and dessert dataset.
