# Shimmer Widget Demo

This Flutter app demonstrates the use of the **Shimmer** widget to create a loading effect for list items, simulating a real world loading scenario.

## How to Run

1. Clone the repository:
	```bash
	git clone https://github.com/Hannah1563/widget_app.git
	cd widget_app
	```
2. Install dependencies:
	```bash
	flutter pub get
	```
3. Run the app:
	```bash
	flutter run
	```

## Widget Attributes Demonstrated

This demo highlights three key properties of the `Shimmer.fromColors` widget:

1. **baseColor**
	- Default: `Colors.grey[300]`
	- Sets the base color of the shimmer effect.
	- Changing this value alters the underlying shimmer shade.

2. **highlightColor**
	- Default: `Colors.grey[100]`
	- Sets the highlight color that animates across the base color.
	- Adjusting this value changes the brightness and contrast of the shimmer animation.

3. **child**
	- Default: (required, no default)
	- The widget to which the shimmer effect is applied (in this case, a list item skeleton).
	- Modifying the child changes the shape and layout of the shimmer placeholder.

## Screenshot

![Shimmer Demo Screenshot](screenshot1.png)
![Shimmer Demo Screenshot](screenshot2.png)

---

**Presentation Date:** Thur 26/2/2026

## References

- [Shimmer Widget package on pub.dev](https://pub.dev/packages?q=platform%3Amacos+shimmer+widget)
	- Used for implementing the shimmer loading effect in this demo.
- [YouTube: Shimmer Effect in Flutter](https://www.youtube.com/watch?v=yCVIjk5x-Us)
	- Tutorial video used for understanding and implementing shimmer widget.
